# Análisis de Churn de Clientes – Telco

## Problema de Negocio

La pérdida de clientes representa una disminución directa en los ingresos recurrentes de empresas de suscripción.  
Este proyecto analiza el comportamiento de cancelación para identificar los segmentos con mayor riesgo y cuantificar el impacto financiero mensual.

## Objetivos

- Calcular la tasa general de churn.
- Identificar los segmentos de mayor riesgo según antigüedad.
- Cuantificar el ingreso mensual perdido.
- Proponer recomendaciones de retención basadas en datos.

## Métricas Clave

- Tasa general de churn: 26.54%
- Tasa de churn (< 12 meses): 47.44%
- Ingreso mensual total perdido: $139,130.85
- % del ingreso perdido correspondiente a < 12 meses: 49.56%

## Hallazgos Principales

- Los clientes con menos de 12 meses presentan el mayor riesgo de cancelación.
- Los contratos mes a mes están fuertemente asociados con mayor churn.
- El primer año del cliente es el período más crítico para estrategias de retención.

## Recomendaciones de Negocio

1. Implementar estrategias de fidelización durante los primeros 12 meses.
2. Incentivar la migración a contratos de mayor duración.
3. Crear alertas tempranas de riesgo de churn para intervención proactiva.

## 🛠 Herramientas Utilizadas

- Power BI
- DAX
- Modelado de datos
- Análisis de negocio

## 📂 Estructura del Repositorio

- data/ → Dataset utilizado
- dashboard/ → Archivo .pbix
- images/ → Capturas del dashboard
