# 📊 Telecom X LATAM — Análisis de Churn de Clientes

## Contexto
Telecom X enfrenta una alta tasa de cancelación de clientes (churn).  
El objetivo de este proyecto es analizar los datos de clientes para identificar los factores que influyen en el abandono y proponer estrategias que ayuden a mejorar la retención.


## Objetivo
Analizar los factores asociados al abandono de clientes (churn) para:
- Detectar patrones relevantes.
- Generar insights accionables.
- Proponer estrategias de retención basadas en datos.


## Tecnologías utilizadas
- Python
- PySpark
- Pandas
- Matplotlib / Seaborn
- Google Colab
- API REST


## Proceso ETL

### Extracción
- Obtención de datos desde una API REST en formato JSON.

### Transformación
- Normalización de estructuras anidadas.
- Limpieza de valores nulos.
- Conversión de tipos de datos.
- Creación de dataset final plano para análisis.

### Carga
- Dataset listo para análisis exploratorio y visualización.


## Análisis Exploratorio (EDA)

Se analizaron variables clave como:
- Tipo de contrato.
- Antigüedad del cliente (tenure).
- Método de pago.
- Cargos mensuales y totales.
- Servicios contratados.

Se realizaron visualizaciones para identificar relaciones entre estas variables y el churn.


## Principales Hallazgos

- Los clientes con **contrato mensual** presentan mayor tasa de abandono.
- Los clientes con **baja antigüedad** tienen mayor probabilidad de churn.
- Los métodos de pago **manuales** están asociados con mayor cancelación.
- Los clientes con **cargos mensuales elevados** presentan mayor churn.


## Recomendaciones de Negocio

- Incentivar la migración hacia **contratos de mayor duración**.
- Implementar **beneficios de fidelización temprana**.
- Fomentar el uso de **pagos automáticos**.
- Diseñar campañas preventivas para clientes con **alto riesgo de churn**.

