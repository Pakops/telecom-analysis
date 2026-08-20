# Análisis ConnectaTel

## 📂 Contenido del repositorio

- Este repositorio contiene el análisis realizado durante el Sprint 7 con información registrada hasta el año 2024, lo cual permitirá analizar el comportamiento del negocio dentro de ese periodo.

🎯 Objetivo del proyecto

- Evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.
- Identificar patrones de uso, segmentos de clientes y oportunidades de negocio a partir de los datos de planes, usuarios y consumo. 

📊 Datasets utilizados:

`plans.csv` → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)

`users.csv` → información de los clientes (edad, ciudad, fecha de registro, plan, churn)

`usage.csv` → detalle del uso real de los servicios (llamadas y mensajes)

Los archivos deben ubicarse en la carpeta `/datasets/` relativa a la ubicación del notebook

🧩 Etapas del análisis

1. Carga y exploración — importación de librerías, lectura de los 3 datasets y revisión inicial de estructura (.shape, .info()).
2. Identificación de problemas de calidad de datos — detección de valores nulos, sentinels inválidos (ej. age = -999) y valores categóricos inconsistentes.
3. Limpieza básica de datos — corrección de sentinels, manejo de nulos y fechas inválidas.
4. Summary statistics de uso por usuario — agregación de mensajes, llamadas y minutos por cliente.
5. Visualización de distribuciones y outliers — histogramas, boxplots y cálculo de límites IQR por variable de consumo.
6. Segmentación de clientes — creación de grupos por edad (Joven, Adulto, Adulto Mayor) y por nivel de uso (Bajo, Medio, Alto).
7. Insight ejecutivo para stakeholders — síntesis de hallazgos, segmentos más valiosos y recomendaciones de negocio.
8. Documentación y entrega — carga del notebook y este README a GitHub.

▶️ Cómo ejecutar el notebook

- Google Colab
  
1. Abre el archivo S7_Version-Estudiante-Project-ConnectaTel.ipynb en Google Colab.
2. Sube los tres archivos CSV (plans.csv, users_latam.csv, usage.csv) a la carpeta /datasets/ de tu entorno de Colab.
3. Ejecuta las celdas en orden.

🔁 Guía de reproducción

1. Abre `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`.
2. Ejecuta las celdas en orden.
3. El notebook está diseñado para ejecutarse de forma secuencial (Paso 1 → Paso 8).


