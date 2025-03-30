[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/awJdrMxa)
# Practica 1.1. Manipuación de datos

## Objetivo

En esta práctica, aprenderás a aplicar técnicas de análisis de datos utilizando Pandas para explorar un dataset relacionado con la salud mental. El objetivo es que pongas en práctica tus habilidades de manipulación, limpieza y análisis de datos para obtener conclusiones interesantes.

---

## Paso 1: Carga del Dataset

Primero, vas a cargar el archivo CSV que contiene la información sobre diferentes factores que influyen en la salud mental. Utiliza la biblioteca Pandas para leer el archivo y observa las primeras filas del dataset. Esto te ayudará a familiarizarte con la información que vas a analizar.

### Preguntas:

1. ¿Cuántos registros y columnas tiene el dataset?
2. ¿Qué tipo de datos predominan?

---

## Paso 2: Exploración Inicial

Ahora que ya tienes los datos cargados, es momento de explorar un poco más. Consulta información general como el tipo de datos en cada columna, cuántos datos no nulos hay, y revisa las primeras filas. También obtén estadísticas básicas como la media y el rango de los datos. Esto te ayudará a detectar si algo llama la atención o si hay datos fuera de lo normal.

### Preguntas:

1. ¿Existen columnas que podrían ser categóricas pero aparecen como tipo `object`?
2. ¿Hay valores que parecen inconsistentes o fuera de rango?

---

## Paso 3: Limpieza de Datos

Es hora de "limpiar" los datos. Revisa si hay valores nulos o datos duplicados. Decide qué hacer con ellos: ¿los eliminarás, los reemplazarás o aplicarás otra estrategia? También asegúrate de que los tipos de datos de cada columna son correctos y convierte aquellos que no estén en el formato adecuado.

### Preguntas:

1. ¿Qué porcentaje del dataset contiene valores nulos?
2. ¿Qué estrategia decidiste aplicar para tratar los valores nulos y por qué?

---

## Paso 4: Análisis Estadístico

En este paso, vas a calcular algunas estadísticas básicas para tres columnas importantes: `Anxiety_Score`, `Depression_Score` y `Stress_Level`. Queremos saber cuál es la media, la mediana y la desviación estándar de estos valores. Esto te permitirá tener una idea general sobre cómo están distribuidos estos puntajes.

### Preguntas:

1. ¿Cuál de los tres puntajes tiene mayor variabilidad?
2. ¿Qué observas sobre la diferencia entre media y mediana en cada caso? ¿Qué te dice esto sobre la distribución?

---

## Paso 5: Filtrado de Datos

Aquí vas a enfocarte en subconjuntos específicos del dataset. Primero, identifica a las personas que tienen un puntaje alto en ansiedad (puedes elegir un valor alto, como por encima de 80). Luego, clasifica a las personas según las horas de sueño que reportan (menos de 5 horas, entre 5 y 7 horas, y más de 7 horas) y analiza cómo varía el nivel de estrés en cada grupo.

### Preguntas:

1. ¿Qué porcentaje del total presenta niveles altos de ansiedad?
2. ¿Existe una relación visible entre las horas de sueño y el nivel de estrés?

---

## Paso 6: Ordenamiento

Ahora vas a ordenar el dataset para encontrar a las personas con mayor satisfacción de vida y menor puntaje de soledad. ¿Puedes descubrir algún patrón? ¿Qué tienen en común estas personas?

### Preguntas:

1. ¿Qué características comunes encuentras en estas 10 personas?
2. ¿Qué hipótesis podrías plantear sobre el vínculo entre satisfacción y soledad?

---

## Paso 7: Guardado de Resultados

Filtra el dataset para encontrar a las personas que reciben terapia y que además tienen un nivel bajo de estrés (por debajo de la mediana). Una vez que tengas este subconjunto, guarda la información en un nuevo archivo CSV para tenerlo listo para futuros análisis.

### Preguntas:

1. ¿Cuántas personas cumplen con ambas condiciones?
2. ¿Qué conclusiones puedes hacer sobre la relación entre terapia y nivel de estrés en este conjunto?

---

## Paso 8: Visualización Opcional

Para finalizar, crea un gráfico que muestre la media de autoestima (`Self_Esteem_Score`) según el género. Observa si hay diferencias entre géneros y reflexiona sobre los factores que podrían influir en esos resultados.

### Preguntas:

1. ¿Hay diferencias notables entre los géneros en cuanto a autoestima?
2. ¿Qué factores del dataset podrían explicar estas diferencias?

---

## Entrega

Cuando termines, sube tu archivo `.ipynb` completo, incluyendo todas tus respuestas, observaciones y el análisis que realizaste.
