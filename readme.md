# 📊 Evaluación del Módulo 3 - Bootcamp de Adalab

¡Hola! 👋 Bienvenida a la evaluación del Módulo 3 del Bootcamp de Adalab. En este proyecto, he trabajado de manera individual para analizar un conjunto de datos sobre la actividad de vuelos y el historial de lealtad de clientes. A continuación, te presento un resumen de las fases y los resultados obtenidos. 🚀

## 📋 Contenido

1. [Fase 1: Exploración y Limpieza](#fase-1-exploración-y-limpieza)
2. [Fase 2: Análisis Exploratorio de Datos](#fase-2-análisis-exploratorio-de-datos)
3. [Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo](#fase-3-evaluación-de-diferencias-en-reservas-de-vuelos-por-nivel-educativo)

---

## 🧹 Fase 1: Exploración y Limpieza

### 1. Exploración Inicial

- **Carga de Datos:** 📂 Cargué los datos desde archivos CSV para su análisis.
- **Exploración de DataFrames:** 👀 Examiné las primeras y últimas filas, así como muestras aleatorias de los DataFrames para entender su estructura y contenido.
- **Funciones de Exploración:** 🔍 Definí funciones para obtener información detallada sobre los DataFrames, incluyendo estadísticas descriptivas, tipos de datos, y valores nulos.
- **Unión de DataFrames:** 🔗 Uní los DataFrames `df1` y `df2` usando la columna 'Loyalty Number' y guardé el resultado.

### 2. Limpieza de Datos

- **Relectura y Eliminación de Duplicados:** 🔄 Leí el archivo CSV unido, verifiqué y eliminé duplicados.
- **Eliminación de Columnas Irrelevantes:** ❌ Eliminé columnas innecesarias que no aportan información relevante.
- **Normalización de Nombres y Valores:** ✏️ Normalicé nombres de columnas y valores categóricos para estandarizar el DataFrame.
- **Manejo de Valores Nulos:** 🚫 Reemplacé valores nulos y negativos con valores apropiados.
- **Imputación de Valores Faltantes:** 🧮 Imputé valores faltantes en 'salary' utilizando la media de categorías cercanas.
- **Guardado del DataFrame Limpio:** 💾 Guardé el DataFrame limpio para su uso en análisis futuros.

---

## 📈 Fase 2: Análisis Exploratorio de Datos

En esta fase, exploré diversos aspectos de los datos para obtener información valiosa:

1. **Distribución de Vuelos Reservados por Mes:** 📅 Analicé cómo varía el número de vuelos reservados a lo largo del año para identificar patrones estacionales o tendencias.

2. **Relación entre Distancia y Puntos Acumulados:** 🌍 Investigé si existe alguna correlación entre la distancia de los vuelos y los puntos acumulados por los clientes.

3. **Distribución de Clientes por Provincia:** 🗺️ Observé la cantidad de clientes en diferentes provincias para identificar áreas con mayor o menor presencia.

4. **Comparación del Salario Promedio por Nivel Educativo:** 🎓 Comparé el salario promedio entre diferentes niveles educativos para entender mejor la relación entre educación y salario.

5. **Proporción de Clientes con Diferentes Tipos de Tarjetas de Fidelidad:** 💳 Evalué la proporción de clientes con distintos tipos de tarjetas de fidelidad para comprender mejor la distribución de tipos de lealtad.

6. **Distribución de Clientes según Estado Civil y Género:** 👥 Analicé cómo se distribuyen los clientes según su estado civil y género para identificar posibles patrones demográficos.

---

## 🧪 Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo

En esta fase, evalué si hay diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes:

1. **Preparación de Datos:** 🗂️ Filtré y categoricé los datos para centrarnos en el número de vuelos reservados y el nivel educativo de los clientes.

2. **Análisis Descriptivo:** 📊 Calculé estadísticas descriptivas como la media, mediana y desviación estándar del número de vuelos reservados para cada grupo educativo. También visualicé la distribución de los datos para entender mejor las diferencias entre grupos.

3. **Pruebas Estadísticas Realizadas:**
   - **Prueba de Normalidad (Shapiro-Wilk):** 🔍 Evalué si los datos de vuelos reservados siguen una distribución normal.
   - **Prueba de Homogeneidad de Varianzas (Levene):** 📏 Verifiqué si las varianzas entre los grupos educativos eran homogéneas.
   - **Prueba de Chi-cuadrado:** 📊 Evalué la independencia entre el nivel educativo y el número de vuelos reservados.
   - **Prueba t para Comparar Medias:** 🧮 Comparé las medias de vuelos reservados entre los grupos de diferentes niveles educativos.
   - **Prueba de Mann-Whitney U:** 📉 Comparé las medianas de vuelos reservados entre grupos con niveles educativos 'universitario' y 'no universitario'.

### Conclusión General
- **Prueba de Normalidad (Shapiro-Wilk):** No sigue un patrón normal.
- **Prueba de Chi-cuadrado:** Hay una relación significativa entre el nivel educativo y el número de vuelos reservados.
- **Prueba t:** No se encontró una diferencia significativa en la media del número de vuelos reservados entre los grupos educativos.
- **Prueba de Mann-Whitney U:** Se encontró una diferencia significativa en las medianas de vuelos reservados entre los grupos 'universitario' y 'no universitario'.

Esto sugiere que, aunque el nivel educativo puede influir en la distribución de los vuelos reservados, las diferencias en las medias entre los grupos no son significativas. Esto podría ser útil para ajustar estrategias o políticas específicas según el nivel educativo.

---

¡Gracias por revisar el README del proyecto! Si tienes alguna pregunta o necesitas más información, no dudes en contactarme. 😊

Nota: La evaluación y análisis de los datos fueron realizados de manera individual por mí. 💪

