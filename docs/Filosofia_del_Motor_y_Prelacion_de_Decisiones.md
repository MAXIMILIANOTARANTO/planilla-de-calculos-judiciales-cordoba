# Filosofía del Motor de Cálculo

**Sistema Autónomo de Planillas de Cálculos Judiciales de Córdoba**

## Principio Fundamental

El motor de cálculo debe operar con la siguiente **prelación estricta** de decisiones:

### 1. Primacía de la Sentencia (Máxima Prioridad)

Lo que la sentencia disponga de forma expresa tiene **prioridad absoluta**.

Esto incluye:
- Monto o capital condenado.
- Fecha desde la cual corren los intereses (o fecha de mora).
- Tasa de interés si el juez la fija expresamente.
- Tipo de concepto o rubro.
- Cualquier otra indicación concreta sobre cómo debe liquidarse.

El sistema **nunca** se apartará de lo que la sentencia ordene de manera clara.

### 2. Criterio Vigente del Fuero (Cuando la sentencia guarda silencio)

Si la sentencia no especifica algún aspecto del cálculo (tasa, período exacto, forma de cálculo, etc.), el motor aplicará el **criterio oficial vigente** para el fuero correspondiente:

- **Fuero Civil y Comercial (Prioritario)**: Metodología de la Planilla General de Cálculos Judiciales del TSJ, actualizada conforme a la reforma del Código Arancelario (Ley 9.459 modificada por Ley 11.042). Se priorizará el uso de TIM (Res. BCRA 1/2026) y la tasa del Banco de la Provincia de Córdoba.
- **Fuero Laboral**: Criterios establecidos por la Sala Laboral del TSJ en los precedentes Romero y Seren, y las planillas oficiales .xlsm que el Tribunal provee.

### 3. Beneficio del Cliente (Dentro de la Legalidad)

Cuando existan varias opciones válidas desde el punto de vista jurídico (por ejemplo, distintas tasas defendibles, interpretación de períodos, aplicación de Factor, etc.), el motor seleccionará la opción **más favorable para el cliente**, siempre que:

- Sea jurídicamente sostenible.
- Esté dentro del marco legal vigente.
- Quede debidamente documentada la decisión y su fundamento.

**Nunca** se tomará una decisión que se aparte de la legalidad, aunque sea más beneficiosa para el cliente.

## Principios Rectores del Motor

- **Legalidad por encima de todo**: El sistema opera dentro del derecho vigente de la Provincia de Córdoba.
- **Fidelidad a la sentencia**: La voluntad del juez expresada en la resolución es la fuente primaria.
- **Transparencia**: Toda decisión relevante queda registrada y explicada.
- **Beneficio del cliente**: Se maximiza el resultado a favor del cliente dentro de los límites legales.
- **Auditabilidad**: El motor deja rastro claro de qué criterio aplicó y por qué.

## Ejemplo de Aplicación

Una sentencia civil condena al pago de una suma "con más sus intereses desde la fecha de la mora". No especifica tasa.

- El motor respeta la fecha de mora indicada.
- Como la sentencia no fija tasa, aplica el criterio vigente del fuero Civil y Comercial (TIM o tasa Banco Córdoba según corresponda).
- Si hubiera margen para elegir entre dos tasas defendibles, seleccionaría la más alta (beneficio del cliente), documentando la elección.

---

**Documento incorporado al ecosistema soberano.**
**Prioridad: Civil y Comercial.**
**Fecha: 24 de julio de 2026**