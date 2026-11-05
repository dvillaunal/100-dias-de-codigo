# 100 días de código · #100DaysOfCode

**EN** — Daily coding log from the #100DaysOfCode challenge (Universidad Nacional de Colombia, March–June 2021): 100 consecutive days, from Python fundamentals to statistical learning in R (logistic regression, discriminant analysis, decision trees, k-NN, SVM, cross-validation, bootstrap and clustering).

**ES** — Bitácora del reto #100DaysOfCode (Universidad Nacional de Colombia, marzo a junio de 2021): 100 días seguidos de código, desde fundamentos de Python hasta aprendizaje estadístico en R.

| Bloque | Días | Temas |
|---|---|---|
| Python | 00–38 | Tipos de datos, control de flujo, funciones, archivos (txt, Excel), fechas, NumPy, pandas, Matplotlib, scikit-image, expresiones regulares, web scraping, POO |
| R: fundamentos | 39–59 | Tipos de datos, estructuras (vectores, listas, matrices, data frames, factores), funciones, archivos, gráficos, datos faltantes |
| R: funciones y datos | 60–73 | Funciones built-in y propias sobre cada estructura de datos, isogramas, normalización y variables ficticias, JSON/XML, fechas con lubridate |
| R: análisis y visualización | 74–83 | Tidyverse, mapas, modelo lineal, text mining (Twitter), correlación, matrices de confusión, climadiagramas, Naïve Bayes |
| R: aprendizaje estadístico | 84–99 | Regresión logística y ROC/AUC, árboles de decisión, k-NN, Bland-Altman, LDA/QDA, validación cruzada, bootstrap, SVM, clustering |

## Estructura

```
Python/   días 00–38 (un archivo o una carpeta por día)
R/        días 39–99 (una carpeta por día, con datos y salidas)
```

Cada día vivía antes en su propio repositorio (`Dia_XX_fecha`); en noviembre de 2026 se unieron aquí para dejar el perfil ordenado. Los repositorios originales siguen existiendo como privados.

## Índice

| Día | Fecha | Lenguaje | Tema |
|---|---|---|---|
| 00 | 16 mar 2021 | Python | [Funciones predeterminadas (print, input)](Python/Dia_00_16marzo.py) |
| 01 | 17 mar 2021 | Python | [Strings](Python/Dia_01_17marzo.py) |
| 02 | 18 mar 2021 | Python | [Listas](Python/Dia_02_18marzo.py) |
| 03 | 19 mar 2021 | Python | [Diccionarios](Python/Dia_03_19marzo.py) |
| 04 | 20 mar 2021 | Python | [Sets](Python/Dia_04_20marzo.py) |
| 05 | 21 mar 2021 | Python | [Tuplas](Python/Dia_05_21marzo.py) |
| 06 | 22 mar 2021 | Python | [Expresiones lógicas y operadores](Python/Dia_06_22marzo.py) |
| 07 | 23 mar 2021 | Python | [Condicionales](Python/Dia_07_23marzo.py) |
| 08 | 24 mar 2021 | Python | [Bucle for](Python/Dia_08_24marzo.py) |
| 09 | 25 mar 2021 | Python | [Bucle while](Python/Dia_09_25marzo.py) |
| 10 | 26 mar 2021 | Python | [Ejercicio: canasta familiar con diccionarios](Python/Dia_10_26marzo.py) |
| 11 | 27 mar 2021 | Python | [Funciones](Python/Dia_11_27marzo.py) |
| 12 | 28 mar 2021 | Python | [Documentación de funciones (docstrings)](Python/Dia_12_28marzo.py) |
| 13 | 29 mar 2021 | Python | [Funciones built-in](Python/Dia_13_29marzo.py) |
| 14 | 30 mar 2021 | Python | [Módulos y librerías](Python/Dia_14_30marzo.py) |
| 15 | 31 mar 2021 | Python | [Excepciones try/except](Python/Dia_15_31marzo.py) |
| 16 | 1 abr 2021 | Python | [Manejo de archivos de texto](Python/Dia_16_1abril) |
| 17 | 2 abr 2021 | Python | [Manejo de archivos de Excel](Python/Dia_17_2abril) |
| 18 | 3 abr 2021 | Python | [Librería string](Python/Dia_18_3abril) |
| 19 | 4 abr 2021 | Python | [Fechas y años bisiestos (datetime, calendar)](Python/Dia_19_4abril) |
| 20 | 5 abr 2021 | Python | [Calculadora de fechas (datetime)](Python/Dia_20_5abril) |
| 21 | 6 abr 2021 | Python | [Módulo calendar](Python/Dia_21_6abril.py) |
| 22 | 7 abr 2021 | Python | [Diferencias de tiempo (timedelta)](Python/Dia_22_7abril) |
| 23 | 8 abr 2021 | Python | [NumPy](Python/Dia_23_08abril.py) |
| 24 | 9 abr 2021 | Python | [NumPy con archivos de Excel](Python/Dia_24_09abril) |
| 25 | 10 abr 2021 | Python | [Pandas: estadísticas básicas de inmuebles](Python/Dia_25_10abril) |
| 26 | 11 abr 2021 | Python | [Pandas: DataFrames](Python/Dia_26_11abril) |
| 27 | 12 abr 2021 | Python | [Librería MatPlotLib](Python/Dia_27_12abril) |
| 28 | 13 abr 2021 | Python | [Librería MatPlotLib](Python/Dia_28_13abril) |
| 29 | 14 abr 2021 | Python | [Librería scikit-image](Python/Dia_29_14abril) |
| 30 | 15 abr 2021 | Python | [Expresiones regulares (regular expressions)](Python/Dia_30_15abril) |
| 31 | 16 abr 2021 | Python | [Web Scraping (BeautifulSoup & Requests)](Python/Dia_31_16abril) |
| 32 | 17 abr 2021 | Python | [`*args` y `**kwargs`](Python/Dia_32_17abril) |
| 33 | 18 abr 2021 | Python | [Funciones lambda](Python/Dia_33_18abril) |
| 34 | 19 abr 2021 | Python | [Listas por comprensión](Python/Dia_34_19abril) |
| 35 | 20 abr 2021 | Python | [Librería Collections](Python/Dia_35_20abril) |
| 36 | 21 abr 2021 | Python | [Programación Orientada a Objetos. Clases, Objetos(instancias), método constructor `__init__()`](Python/Dia_36_21abril) |
| 37 | 22 abr 2021 | Python | [Programación orientada a objetos: atributos de clase y de instancia](Python/Dia_37_22abril) |
| 38 | 23 abr 2021 | Python | [Herencia en Python](Python/Dia_38_23abril) |
| 39 | 24 abr 2021 | R | [Hola mundo en R](R/Dia_39_24abril) |
| 40 | 25 abr 2021 | R | [Tipos de datos en R](R/Dia_40_25abril) |
| 41 | 26 abr 2021 | R | [Variables en R (creación, asignación de valores, modificación, eliminación de variables) y tipos de operadores en R](R/Dia_41_26abril) |
| 42 | 27 abr 2021 | R | [Condicionales (if y switch)](R/Dia_42_27abril) |
| 43 | 28 abr 2021 | R | [Ciclos en R (repeat, while y for)](R/Dia_43_28abril) |
| 44 | 29 abr 2021 | R | [Funciones en R. Clases de funciones. Funciones incorporadas (built-in)](R/Dia_44_29abril) |
| 45 | 30 abr 2021 | R | [Creación, documentación e invocación de funciones en R](R/Dia_45_30abril) |
| 46 | 1 may 2021 | R | [Manejo de strings en R](R/Dia_46_1mayo) |
| 47 | 2 may 2021 | R | [Manejo de vectores en R](R/Dia_47_2mayo) |
| 48 | 3 may 2021 | R | [Manejo de listas en R](R/Dia_48_3mayo) |
| 49 | 4 may 2021 | R | [Manejo de matrices en R](R/Dia_49_4mayo) |
| 50 | 5 may 2021 | R | [Manejo de arreglos en R](R/Dia_50_5mayo) |
| 51 | 6 may 2021 | R | [Manejo de Data Frames en R](R/Dia_51_6mayo) |
| 52 | 7 may 2021 | R | [Manejo de Factors en R](R/Dia_52_7mayo) |
| 53 | 8 may 2021 | R | [Manejo de paquetes en R](R/Dia_53_8mayo) |
| 54 | 9 may 2021 | R | [Manejo de archivos `*.csv`](R/Dia_54_9mayo) |
| 55 | 10 may 2021 | R | [Manejo de archivos `*.xlsx`](R/Dia_55_10mayo) |
| 56 | 11 may 2021 | R | [Manejo de archivos `*.txt`](R/Dia_56_11mayo) |
| 57 | 12 may 2021 | R | [Gráficos con R: tortas, barras, boxplots, histogramas, gráficos de dispersión](R/Dia_57_12mayo) |
| 58 | 13 may 2021 | R | [Cálculo de media, moda y mediana con R](R/Dia_58_13mayo) |
| 59 | 14 may 2021 | R | [Formas de eliminar la información que falta o remplazarla](R/Dia_59_14mayo) |
| 60 | 15 may 2021 | R | [Funciones built-in in R con valores numéricos](R/Dia_60_15mayo) |
| 61 | 16 may 2021 | R | [Funciones built-in in R con cadenas de texto](R/Dia_61_16mayo) |
| 62 | 17 may 2021 | R | [Cree funciones SIN argumentos en R con cadenas de texto y con valores numéricos](R/Dia_62_17mayo) |
| 63 | 18 may 2021 | R | [Cree funciones CON argumentos en R con cadenas de texto y con valores numéricos](R/Dia_63_18mayo) |
| 64 | 19 may 2021 | R | [Cree funciones que manejen vectores en R](R/Dia_64_19mayo) |
| 65 | 20 may 2021 | R | [Cree funciones que manejen listas en R](R/Dia_65_20mayo) |
| 66 | 21 may 2021 | R | [Cree funciones que manejen matrices en R](R/Dia_66_21mayo) |
| 67 | 22 may 2021 | R | [Cree funciones que manejen arreglos en R](R/Dia_67_22mayo) |
| 68 | 23 may 2021 | R | [Cree funciones que manejen Data Frames en R](R/Dia_68_23mayo) |
| 69 | 24 may 2021 | R | [Cree funciones que manejen factores en R](R/Dia_69_24mayo) |
| 70 | 25 may 2021 | R | [Un isograma es una palabra, o frase, que no contiene letras repetidas. Utilice el archivo ListaPalabras_v20210520.txt como archivo de entrada (en la columna de referencias se indica la ruta para acceder al archivo) y genere un archivo de isogramas en orden alfabetico. Además imprima por pantalla un reporte de la cantidad de isogramas que tienen cuatro, cinco, seis y siete letras](R/Dia_70_25mayo) |
| 71 | 26 may 2021 | R | [Manejo de Archivos JSON, XML e incrustado de tablas en formato HTML](R/Dia_71_26mayo) |
| 72 | 27 may 2021 | R | [normalizacion y creación de variables ficticias](R/Dia_72_27mayo) |
| 73 | 28 may 2021 | R | [Manejo de Fechas en R (Lubridate)](R/Dia_73_28mayo) |
| 74 | 29 may 2021 | R | [Manejo de la libreria Tidyverse](R/Dia_74_29mayo) |
| 75 | 30 may 2021 | R | [Mapas con R](R/Dia_75_30mayo) |
| 76 | 31 may 2021 | R | [Modelo lineal](R/Dia_76_31mayo) |
| 77 | 1 jun 2021 | R | [Ejercicios con la App Science Journal de Google](R/Dia_77_1junio) |
| 78 | 2 jun 2021 | R | [Text mining con R: ejemplo práctico Twitter](R/Dia_78_2junio) |
| 79 | 3 jun 2021 | R | [Correlación de Datos, Ilustrados en Graficas](R/Dia_79_3junio) |
| 80 | 4 jun 2021 | R | [Matrices de Confusión y Diagramas de Mosaico](R/Dia_80_4junio) |
| 81 | 5 jun 2021 | R | [ClimaDiagramas](R/Dia_81_5junio) |
| 82 | 6 jun 2021 | R | [Naïve Bayes con R](R/Dia_82_6junio) |
| 83 | 7 jun 2021 | R | [Librería (e1072), Ejerciciocomplementario al del Dia_82_6junio (Continuación del tema de Clasificadores Bayesianos) y corrección de Laplace](R/Dia_83_7junio) |
| 84 | 8 jun 2021 | R | [Regresión logística binaria: Modelos (glm) y Curvas ROC & AUC](R/Dia_84_8junio) |
| 85 | 9 jun 2021 | R | [Regresión logística binaria: Modelos de impacto combinado & Optimización de un modelos (glm)](R/Dia_85_9junio) |
| 86 | 10 jun 2021 | R | [Árboles de decisión](R/Dia_86_10junio) |
| 87 | 11 jun 2021 | R | [Método de los "k vecinos más cercanos"](R/Dia_87_11junio) |
| 88 | 12 jun 2021 | R | [Análisis gráfico de Bland-Altman](R/Dia_88_12junio) |
| 89 | 13 jun 2021 | R | [Análisis discriminante lineal y cuadrático](R/Dia_89_13junio) |
| 90 | 14 jun 2021 | R | [Análisis discriminante lineal y cuadrático (parte 2)](R/Dia_90_14junio) |
| 91 | 15 jun 2021 | R | [Análisis discriminante lineal (parte 3)](R/Dia_91_15junio) |
| 92 | 16 jun 2021 | R | [Análisis discriminante lineal y cuadrático (parte 4)](R/Dia_92_16junio) |
| 93 | 17 jun 2021 | R | [Métodos de remuestreo y validación de modelos: validación cruzada y bootstrap (parte 1)](R/Dia_93_17junio) |
| 94 | 18 jun 2021 | R | [Métodos de remuestreo y validación de modelos: validación cruzada y bootstrap (parte 2)](R/Dia_94_18junio) |
| 95 | 19 jun 2021 | R | [Métodos de remuestreo y validación de modelos: validación cruzada y bootstrap (parte 3)](R/Dia_95_19junio) |
| 96 | 20 jun 2021 | R | [Máquinas de Vector Soporte (Parte 1)](R/Dia_96_20junio) |
| 97 | 21 jun 2021 | R | [Máquinas de Vector Soporte (Parte 2)](R/Dia_97_21junio) |
| 98 | 22 jun 2021 | R | [Máquinas de Vector Soporte (Parte 3)](R/Dia_98_22junio) |
| 99 | 23 jun 2021 | R | [Métodos de clustering](R/Dia_99_23junio) |

## Reglas del reto

- Un ejercicio por día, con el nombre `Dia_XX_fecha`.
- Del día 00 al 38 en Python 3; desde el día 39, en R.
- Cada código lleva un encabezado (autor, lenguaje, tema y fuentes) y comentarios que explican cada paso, con al menos dos ejemplos propios por tema.

Sitio oficial del reto: <https://www.100daysofcode.com/>
