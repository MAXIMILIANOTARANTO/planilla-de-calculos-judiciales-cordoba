# Diferencia por Fuero – Prioridad: Civil y Comercial

**Sistema Autónomo de Planillas de Cálculos Judiciales de Córdoba**

Este documento formaliza la comprensión jurídica de la diferencia entre fueros y establece la **prioridad clara en el fuero Civil y Comercial** para el desarrollo del sistema.

## 1. Resumen Ejecutivo

El sistema debe tener **dos modos principales de cálculo** claramente diferenciados:

- **Modo Laboral**: Basado en la doctrina de la Sala Laboral del TSJ (precedentes Romero y Seren) y en las planillas oficiales .xlsm que el propio Tribunal provee.
- **Modo Civil y Comercial (Prioritario)**: Basado en la Planilla General de Cálculos Judiciales / CalculadoraTasa del TSJ, actualizada conforme a la reforma del Código Arancelario (Ley 9.459 modificada por Ley 11.042).

Dado que el usuario indicó explícitamente que **el fuero que más le importa es el civil y comercial**, todo el desarrollo del sistema (extracción desde sentencia, motor de cálculo, generador de planilla y bucle de aprendizaje) priorizará la calidad, precisión y profesionalismo en este fuero.

## 2. Diferencia Jurídica y Práctica entre Fueros

### Fuero Laboral
- Órgano: Sala Laboral del Tribunal Superior de Justicia de Córdoba.
- Doctrina específica: Precedentes "Romero" (LRT) y "Seren".
- Herramientas oficiales: Planillas .xlsm dedicadas (disponibles para descarga en el sitio del TSJ).
  - Planilla LRT – conforme fallo Romero
  - Planilla conforme fallo Seren
- Tasa de interés característica: Tasa pasiva promedio del BCRA + adicional (generalmente 2% o 3% nominal mensual, según contexto).
- En LRT puede intervenir el RIPTE en forma diaria.
- Cálculo más estructurado y con menor flexibilidad que el fuero civil.
- Menor peso de la moneda JUS y los honorarios en la mayoría de los casos.

### Fuero Civil y Comercial (Prioridad del Sistema)
- Órgano: Juzgados Civiles y Comerciales, Cámaras Civiles y Comerciales, etc.
- Marco normativo principal: 
  - Código Civil y Comercial de la Nación (art. 768 inc. c) para intereses moratorios.
  - Código Arancelario de Córdoba: **Ley 9.459 modificada por Ley 11.042** (reforma clave que impacta honorarios y actualizaciones).
- Herramienta oficial: **Planilla General de Cálculos Judiciales / CalculadoraTasa** (https://www.justiciacordoba.gob.ar/planillacalculosjudiciales).
- Actualización relevante (mayo 2026): Incorporación de TIM (Res. BCRA 1/2026), tasa del Banco de la Provincia de Córdoba, campo Factor y soporte de moneda JUS.
- Características principales:
  - Alta flexibilidad: permite múltiples conceptos en una misma planilla (capital, intereses, honorarios, daño emergente, lucro cesante, daño moral, etc.).
  - Soporte nativo de **moneda JUS** (fundamental para honorarios profesionales).
  - Campo **Factor** para multiplicadores.
  - Opciones de tasa: TIM, tasa Banco Córdoba, Plus de Interés manual.
  - Cálculo de períodos con calendario (Desde – Hasta).

## 3. Implicancias para el Sistema Autónomo

### Detección de Fuero (Extractor Inteligente)
El primer paso crítico del sistema será detectar correctamente el fuero a partir del texto de la sentencia. Se priorizarán patrones típicos del fuero civil y comercial:
- Juzgado o Cámara Civil y Comercial.
- Reclamos de: daños y perjuicios, ejecución de honorarios, cobro de pesos, responsabilidad civil, contratos, etc.
- Ausencia de referencias a Ley de Contrato de Trabajo, LRT, indemnización por despido, multas laborales, etc.

### Modos de Cálculo
- **Modo Civil y Comercial (principal)**: Usa la metodología de la CalculadoraTasa general actualizada.
  - Tasa base preferente: TIM (nueva referencia) o tasa Banco de la Provincia de Córdoba.
  - Soporte completo de JUS, Factor y múltiples conceptos.
  - Notas legales automáticas que citen Ley 9.459 + 11.042 y Res. BCRA 1/2026.
- **Modo Laboral (secundario pero preciso)**: Respeta los criterios de la Sala Laboral (Romero / Seren) y referencia las planillas oficiales del TSJ.

### Generador de Planilla
La planilla final generada para casos civiles y comerciales tendrá:
- Formato profesional estilo TSJ Córdoba.
- Desglose claro por concepto.
- Totales fáciles de leer.
- Fundamentación jurídica visible (citas normativas).
- Log de decisiones del sistema (trazabilidad).

## 4. Bucle de Aprendizaje por Fuero

El proceso iterativo de buscar ejemplos reales, generar planillas, comparar y corregir se realizará de forma **separada por fuero**:
- Civil y Comercial: se usarán como referencia principal la estructura y lógica de la CalculadoraTasa oficial + ejemplos públicos de planillas civiles.
- Laboral: se usarán como gold standard las planillas oficiales Romero y Seren del TSJ.

Esto garantiza que el sistema no mezcle lógicas y que el modo Civil y Comercial (prioridad) alcance el más alto nivel de fidelidad.

## 5. Próximos Pasos Prioritarios (Civil y Comercial)

1. Fortalecer el Extractor para detectar con alta precisión casos civiles y comerciales.
2. Definir los "Tipo de Cálculo" más frecuentes en la práctica civil y comercial cordobesa.
3. Implementar el motor de cálculo con calendario optimizado para el modo general (TIM, Banco Córdoba, Factor, JUS).
4. Generar plantillas de ejemplo de alta calidad para casos civiles típicos.
5. Ejecutar el primer ciclo de comparación usando ejemplos civiles.

---

**Documento generado bajo los principios del ecosistema soberano de Maximiliano Taranto.**
**Prioridad explícita: Fuero Civil y Comercial.**
**Fecha: 24 de julio de 2026**