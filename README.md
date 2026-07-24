# Planilla de Cálculos Judiciales - Córdoba

**Sistema Autónomo Soberano para generar planillas judiciales a partir de sentencias**

## Objetivo

Crear un sistema que, a partir del texto de una sentencia, sea capaz de:

- Identificar el fuero
- Extraer los datos relevantes
- Calcular los intereses respetando la prelación legal
- Generar una planilla profesional lista para uso forense

**Prioridad principal:** Fuero Civil y Comercial

## Filosofía del Motor

El motor sigue estrictamente esta prelación:

1. **Primacía de la Sentencia** (lo que el juez disponga de forma expresa)
2. **Criterio vigente del fuero** (cuando la sentencia no lo especifica)
3. **Beneficio del cliente dentro de la legalidad** (cuando hay margen, eligiendo la opción más favorable, siempre documentada)

Nunca se actúa fuera del marco legal.

## Estado Actual

Estamos en fase de **prueba y error** controlada. Estamos probando la lógica del motor con casos reales e hipotéticos para refinarlo antes de implementar el código completo.

## Estructura del Repositorio

- `docs/` → Documentación jurídica y de diseño
- `motor/` → (Futuro) Código del motor de cálculo
- `extractor/` → (Futuro) Lógica de extracción desde sentencias
- `generador/` → (Futuro) Generación de planillas XLSX

## Principios

- Legalidad por encima de todo
- Fidelidad a lo que dice la sentencia
- Transparencia y trazabilidad de decisiones
- Beneficio del cliente dentro del marco legal

---

**Proyecto soberano de Maximiliano Taranto**