# Criterios de Elaboración de Planillas de Cálculos Judiciales

**Fuero Civil y Comercial - Provincia de Córdoba**

**Documento de trabajo - Fase 0**
**Fecha: 24 de julio de 2026**

---

## 1. Filosofía General del Sistema

El sistema debe seguir estrictamente la siguiente prelación de decisiones:

### 1.1 Primacía de la Sentencia
Lo que la sentencia disponga de forma expresa tiene **prioridad absoluta** (monto, fecha de mora, tasa si la fija, rubros, etc.).

### 1.2 Criterio Vigente del Fuero
Cuando la sentencia no especifica algún aspecto, se aplica el criterio oficial vigente del fuero Civil y Comercial (Planilla General del TSJ actualizada en mayo 2026).

### 1.3 Beneficio del Cliente dentro de la Legalidad
Cuando exista margen de interpretación jurídica, se elegirá la opción más favorable para el cliente, siempre que sea defendible y quede debidamente documentada.

---

## 2. Ejes de Decisión al Elaborar una Planilla

Al elaborar una planilla en fuero Civil y Comercial, se deben tomar decisiones en los siguientes ejes:

### 2.1 Tipo de Cálculo (Clasificación del Rubro)
Se debe identificar a qué categoría corresponde cada rubro de la sentencia.

**Rubros frecuentes en Civil y Comercial:**
- Daño emergente
- Lucro cesante
- Daño moral
- Honorarios profesionales
- Intereses
- Capital
- Gastos

**Criterio:** Seguir la descripción más adecuada según la práctica habitual y el contenido de la sentencia.

### 2.2 Período (Desde - Hasta)
**Regla general:**
- Se toma la fecha de mora indicada en la sentencia.
- Si la sentencia no la especifica, se utiliza la fecha desde la cual se considera exigible la obligación.

### 2.3 Elección de Tasa de Interés

| Situación de la Sentencia | Tasa recomendada | Observaciones |
|-----------------------------|------------------|-------------|
| Fija expresamente una tasa | La tasa de la sentencia | Prioridad máxima |
| No fija tasa (caso general) | **TIM** (opción principal) | Herramienta oficial incorporada en mayo 2026 |
| No fija tasa + rubro de honorarios | Tasa del **Banco de la Provincia de Córdoba** | Vinculada a la reforma arancelaria (Ley 11.042) |
| Riesgo de TIM excesiva (según Cámara) | Tasa de uso judicial o Banco de la Provincia | Ej: posición de la Cámara 9ª |
| Máxima beneficio del cliente (con margen) | TIM + evaluar Plus | Siempre documentar |

### 2.4 Plus de Interés
Campo que permite agregar un adicional sobre la tasa base elegida.

**Criterio:** Se utiliza cuando el abogado considera que corresponde un adicional. No es automático.

### 2.5 Factor
Campo incorporado en mayo 2026 que permite aplicar un **multiplicador** al monto calculado.

**Uso principal:** Útil para computar intereses de forma más flexible o aplicar coeficientes.

**Momento de aplicación:** Después de calcular los intereses.

### 2.6 Moneda (Pesos / JUS)
- **JUS**: Especialmente relevante en honorarios y conceptos arancelarios (reforma Ley 11.042).
- El sistema debe soportar ambos tipos de moneda.

### 2.7 Criterio por Cámara y TSJ

| Ámbito | Criterio conocido | Observaciones |
|---------|-------------------|-------------|
| **TSJ (General)** | TIM como herramienta de referencia (no obligatoria) | Incorporada en la planilla oficial mayo 2026 |
| **Cámara 9ª Civil y Comercial** | Rechaza aplicación automática de TIM en algunos casos | Prefiere tasa de uso judicial (ej. ejecución de honorarios) |
| **Otras Cámaras** | Sin posición pública clara (a julio 2026) | Se aplica criterio general TSJ |

**Nota:** Esta tabla es dinámica y se irá actualizando a medida que aparezca nueva jurisprudencia.

---

## 3. Resumen de la Prelación de Decisiones

1. **Sentencia** (datos expresos)
2. **Criterio oficial del TSJ** (planilla actualizada 2026)
3. **Criterio específico de la Cámara** (cuando exista)
4. **Beneficio del cliente** (dentro de la legalidad y documentado)

---

## 4. Estado del Documento

Este documento es una **versión inicial** (Fase 0). Se irá completando y corrigiendo a medida que se realicen más investigaciones y pruebas.

**Próximos pasos sugeridos:**
- Implementar el Motor de Cálculo (Fase 1)
- Seguir investigando criterios por Cámara
- Probar con casos reales