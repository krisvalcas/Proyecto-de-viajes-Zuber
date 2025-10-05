# 🚕 Análisis de Preferencias de Pasajeros y Clima en Chicago

## Resumen del Proyecto

Este proyecto analiza datos de viajes en taxi en la ciudad de Chicago para la empresa Zuber. El objetivo es identificar patrones de viaje, determinar las preferencias de los pasajeros y comprender cómo las condiciones climáticas afectan la duración de los trayectos. Los resultados ayudarán a Zuber a entender mejor el mercado y a optimizar sus operaciones.

---

### 🎯 Objetivos del Análisis

* Identificar las compañías de taxis más populares en Chicago.
* Determinar los barrios de destino con mayor número de viajes.
* Analizar la relación entre las condiciones climáticas y la duración de los viajes.
* Probar la hipótesis de si la duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia durante los sábados lluviosos.

---

### 🔧 Metodología

1.  [cite_start]**Extracción de Datos con SQL:** Se realizaron consultas a una base de datos para extraer y unir información de diferentes tablas, incluyendo datos sobre compañías de taxis, barrios de destino y número de viajes[cite: 2].
2.  **Análisis de Datos en Python:** Se importaron los datos a un entorno de Python para un análisis más profundo. Se identificaron las principales compañías y los destinos más frecuentes.
3.  **Integración de Datos Climáticos:** Se integró un segundo conjunto de datos con información sobre las condiciones meteorológicas en Chicago durante las fechas de los viajes.
4.  **Prueba de Hipótesis Estadística:** Se formuló y probó una hipótesis para determinar si existía una diferencia estadísticamente significativa en la duración de los viajes en sábados lluviosos en una ruta específica (Loop a O'Hare). Se utilizó una prueba de Levene para la igualdad de varianzas y una prueba t de Welch para muestras independientes.

---

### 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python, SQL
* **Librerías:**
    * **Pandas:** Para la manipulación y análisis de los datos.
    * **Matplotlib:** Para generar visualizaciones.
    * **SciPy (stats):** Para realizar la prueba de hipótesis.
    * **Jupyter Notebook:** Como entorno de trabajo.

---

### 💡 Resultados y Conclusiones Clave

* [cite_start]**Compañías Populares:** La compañía "Flash Cab" es la más popular en términos de número de viajes, seguida de cerca por "Taxi Affiliation Services"[cite: 2].
* [cite_start]**Destinos Principales:** Los barrios de "Loop", "River North" y "Near North Side" son los destinos más comunes para los viajes en taxi[cite: 2].
* **Impacto del Clima (Prueba de Hipótesis):** La prueba de hipótesis no encontró una diferencia estadísticamente significativa entre la duración promedio de los viajes desde el Loop hasta O'Hare en sábados con buen tiempo y sábados lluviosos. [cite_start]El valor p obtenido fue de 0.53, lo que es considerablemente mayor que el nivel de significancia alfa (0.05), por lo que no se pudo rechazar la hipótesis nula[cite: 2]. Esto sugiere que, para esta ruta específica, la lluvia no es un factor determinante en la duración del viaje.
