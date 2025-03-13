# Análisis del proceso de admisión 2025 a la UNMSM
## 🔗Links para cada proceso de admisión
Imágen de la página del proceso 2025-1
![Imágen link 2025-1](imagenes/20251.png)
Link del [proceso de admisión 2025](https://admision.unmsm.edu.pe/Website20251/)

Imagen de la página del proceso 2025-2
![Imágen link 2025-1](imagenes/20252.png)
Link del [proceso de admisión 2025](https://admision.unmsm.edu.pe/portal/admision2025-ii/)

# Modelo para el análisis de datos en Power BI
## 📊 Descripción del modelo
Este modelo de base de datos sigue un esquema en estrella, optimizado para consultas rápidas y eficientes en el análisis de resultados académicos. La estructura permite gestionar información relacionada con alumnos, áreas, modalidades de evaluación, procesos y carreras de manera centralizada.
![Imágen vista 1 Power BI](imagenes/ModeloEstrellaPowerBI.png)
## 📌 Justificación del Diseño
El diseño en estrella se utilizó:

- Optimización para consultas: La tabla Resultados actúa como la tabla de hechos, permitiendo la agregación y análisis eficiente de puntajes, méritos, y estadísticas como número de ingresantes y ausentes.
- Estructura simple y comprensible: Las tablas dimensionales (Alumno, Área, Modalidad, Proceso y Carrera) almacenan información descriptiva que facilita la segmentación y categorización de los datos.
- Flexibilidad en reportes: Se pueden generar informes detallados sobre el desempeño de los alumnos según área, modalidad, proceso o carrera sin afectar el rendimiento de la base de datos.
- Facilidad de escalabilidad: Es sencillo agregar nuevas dimensiones o métricas sin alterar la estructura central.