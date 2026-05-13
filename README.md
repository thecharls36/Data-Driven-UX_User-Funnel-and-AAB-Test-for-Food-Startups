# Data-Driven UX: Embudo de Usuario y Test A/A/B para Startups de Alimentos

## Análisis de conversión y toma de decisiones basada en experimentos

### 📋 Introducción
Este proyecto presenta un análisis integral del embudo de conversión de usuarios y un test A/A/B para la aplicación móvil de una startup de productos alimenticios. El objetivo es identificar cuellos de botella en el recorrido del usuario y evaluar si un cambio propuesto en la tipografía (fuentes) de la aplicación impacta significativamente en el comportamiento y las tasas de conversión.

### 🎯 Objetivos
1. **Análisis del Embudo**  
   Mapear y analizar el camino de conversión del usuario para identificar puntos críticos de abandono.

2. **Experimento A/A/B**  
   Evaluar estadísticamente el impacto de las nuevas fuentes en las acciones de los usuarios entre grupos de control y prueba.

3. **Decisión Basada en Datos**  
   Proporcionar insights accionables para optimizar la UX y respaldar decisiones de diseño.

### 📊 Descripción de los Datos
El conjunto de datos `logs_exp_us.csv` contiene registros de interacciones de usuarios con la siguiente estructura:

| Columna   | Descripción                                                           | Tipo de dato |
|-----------|-----------------------------------------------------------------------|--------------|
| `event`   | Nombre de la acción/evento del usuario                                | `object`     |
| `user_id` | Identificador único de usuario                                        | `int64`      |
| `datetime`| Marca de tiempo del evento (en segundos)                              | `int64`      |
| `group`   | Identificador del grupo experimental (`246`, `247` = control, `248` = prueba) | `int64`      |
