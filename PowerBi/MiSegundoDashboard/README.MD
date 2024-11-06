# Mi Segundo Dashboard

Este dashboard fue creado siguiendo un tutorial de YouTube, que era un poco más avanzado que el primero. Para mejorar la visualización y el formato, se modificaron ciertos parámetros.

- [Ver el tutorial en YouTube](https://www.youtube.com/watch?v=aLV4Qe60VK4&ab_channel=MavenAnalytics)

Puedes encontrar tanto el modelo de datos en la imagen como el tablero en el tutorial.

## Descripción del Modelo

Este modelo es algo más complejo y contiene algunos campos sin normalizar entre las tablas (archivos .csv). El dataset completo, incluyendo el archivo de códigos IATA, se puede descargar desde el siguiente enlace:

- [Descargar Dataset Completo](https://maven-datasets.s3.amazonaws.com/Airline+Flight+Delays/Airline+Flight+Delays.zip)

## Estructura del Dashboard

El modelo se compone de:
- **3 Tablas de LookUp**: `airlines`, `airports`, `cancellation_code`
- **1 Tabla de Hechos (Fact)**: `flights`
