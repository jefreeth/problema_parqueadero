# problema_parqueadero

# Simulación de Cajeros en un Centro Comercial

## Descripción

Este proyecto desarrolla una simulación de eventos discretos para analizar el comportamiento de los cajeros de salida de un centro comercial. El objetivo principal es determinar si la cantidad actual de tres cajeros es suficiente para atender la demanda de usuarios o si es necesario aumentar la capacidad del sistema.

La simulación considera diferentes tipos de usuarios con distintas probabilidades de ocurrencia y tiempos de atención, permitiendo evaluar el desempeño del sistema mediante técnicas estadísticas y análisis de colas.

## Objetivos

- Simular el proceso de atención de usuarios en los cajeros.
- Identificar el cajero con menor y mayor tiempo promedio de atención.
- Calcular la distribución de usuarios por tipo.
- Determinar el estado estable del sistema mediante la técnica de la media acumulada.
- Eliminar el período transitorio para obtener resultados más confiables.
- Evaluar si tres cajeros son suficientes para atender la demanda.

## Tecnologías Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

## Metodología

1. Generación aleatoria de usuarios según probabilidades definidas.
2. Asignación de tiempos de servicio mediante distribuciones exponenciales.
3. Análisis estadístico de los datos generados.
4. Determinación del estado estable utilizando la media acumulada.
5. Eliminación del período transitorio.
6. Simulación de colas para evaluar el desempeño de los cajeros.
7. Comparación de escenarios con diferentes cantidades de cajeros.

## Resultados Principales

- El sistema alcanzó estabilidad aproximadamente a partir de la réplica 30.
- La media con transitorio fue de 3.4579 minutos.
- La media sin transitorio fue de 3.4654 minutos.
- El tiempo promedio de espera fue aproximadamente 0.17 minutos.
- La comparación entre 3 y 4 cajeros no mostró mejoras significativas.
