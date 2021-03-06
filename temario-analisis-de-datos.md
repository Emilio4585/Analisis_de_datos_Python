---
title: "Temario Analisis de datos"
tags: ""
---

-   1.Preliminares
    -   1.1 ¿De qué trata este taller?
        -   ¿Qué tipo de datos?
    -   1.2 ¿Por qué Python para el análisis de datos?
        -   Python como pegamento
        -   Resolver el problema de los "dos idiomas"
        -   ¿Por qué no Python?
    -   1.3 Bibliotecas Python esenciales
        -   NumPy
        -   pandas
        -   matplotlib
        -   IPython y Jupyter
        -   SciPy
        -   scikit-learn
        -   statsmodels
    -   1.4 Instalación y configuración
        -   Windows
        -   Apple (OS X, macOS)
        -   GNU / Linux
        -   Instalación o actualización de paquetes de Python
        -   Python 2 y Python 3
        -   Entornos de desarrollo integrados (IDE) y editores de texto
    -   1.5 Comunidad y conferencias
          

-   2.Conceptos básicos del lenguaje Python, IPython y Jupyter Notebooks
    -   2.1 El intérprete de Python
    -   2.2 Conceptos básicos de IPython
        -   Ejecutando el Shell de IPython
        -   Ejecución del cuaderno Jupyter
        -   Finalización de pestaña
        -   Introspección
        -   El comando% run
        -   Ejecutar código desde el portapapeles
        -   Atajos de teclado de terminal
        -   Acerca de los comandos mágicos
        -   Integración con Matplotlib
    -   2.3 Conceptos básicos del lenguaje Python
        -   Semántica del lenguaje
        -   Tipos escalares
        -   Flujo de control

-   3.Estructuras de datos, funciones y archivos integrados
    -   3.1 Estructuras y secuencias de datos
        -   Tupla
        -   Lista
        -   Funciones de secuencia integradas
        -   diccionario
        -   conjunto
        -   Comprensiones de listas, conjuntos y diccionarios
    -   3.2 Funciones
        -   Espacios de nombres, alcance y funciones locales
        -   Devolver varios valores
        -   Las funciones son objetos
        -   Funciones anónimas (Lambda)
        -   Currying: aplicación de argumento parcial
        -   Generadores
        -   Manejo de errores y excepciones
    -   3.3 Archivos y sistema operativo
        -   Bytes y Unicode con archivos
    -   3.4 Conclusión
         

-   4.Conceptos básicos de NumPy: matrices y computación vectorizada
    -   4.1 El ndarray de NumPy: un objeto de matriz multidimensional
        -   Creando ndarrays
        -   Tipos de datos para ndarrays
        -   Aritmética con matrices NumPy
        -   Indexación y corte básicos
        -   Indexación booleana
        -   Indexación elegante
        -   Transposición de matrices e intercambio de ejes
    -   4.2 Funciones universales: funciones de matriz rápidas basadas en elementos
    -   4.3 Programación orientada a matrices con matrices
        -   Expresando lógica condicional como operaciones de matriz
        -   Métodos matemáticos y estadísticos
        -   Métodos para matrices booleanas
        -   Clasificación
        -   Lógica única y de otro conjunto
    -   4.4 Entrada y salida de archivos con matrices
    -   4.5 Álgebra lineal
    -   4.6 Generación de números pseudoaleatorios
    -   4.7 Ejemplo: caminatas al azar
        -   Simular muchos paseos al azar a la vez
    -   4.8 Conclusión

-   5.Comenzando con pandas
    -   5.1 Introducción a las estructuras de datos de pandas
        -   Series
        -   DataFrames
        -   Objetos de índice
    -   5.2 Funcionalidad esencial
        -   Reindexar
        -   Eliminación de entradas de un eje
        -   Indexación, selección y filtrado
        -   Índices enteros
        -   Alineación aritmética y de datos
        -   Aplicación y asignación de funciones
        -   Clasificación y clasificación
        -   Índices de eje con etiquetas duplicadas
    -   5.3 Resumir y calcular estadísticas descriptivas
        -   Correlación y covarianza
        -   Valores únicos, valor contable y membresía
    -   5.4 Conclusión

-   6.Carga de datos, almacenamiento y formatos de archivo
    -   6.1 Lectura y escritura de datos en formato de texto
        -   Leer archivos de texto en pedazos
        -   Escribir datos en formato de texto
        -   Trabajar con formatos delimitados
        -   Datos JSON
        -   XML y HTML: Web Scraping
    -   6.2 Formatos de datos binarios
        -   Uso del formato HDF5
        -   Leer archivos de Microsoft Excel
    -   6.3 Interacción con API web
    -   6.4 Interacción con bases de datos
    -   6.5 Conclusión

-   7.Limpieza y preparación de datos
    -   7.1 Manejo de datos faltantes
        -   Filtrar datos faltantes
        -   Completar los datos que faltan
    -   7.2 Transformación de datos
        -   Eliminación de duplicados
        -   Transformar datos usando una función o mapeo
        -   Reemplazo de valores
        -   Cambiar el nombre de los índices de eje
        -   Discretización y Binning
        -   Detectar y filtrar valores atípicos
        -   Permutación y muestreo aleatorio
        -   Indicador de cálculo / variables ficticias
    -   7.3 Manipulación de cadenas
        -   Métodos de objetos de cadena
        -   Expresiones regulares
        -   Funciones de cadena vectorizadas en pandas
    -   7.4 Conclusión

-   8.Disputa de datos: unir, combinar y remodelar
    -   8.1 Indexación jerárquica
        -   Reordenación y clasificación de niveles
        -   Resumen de estadísticas por nivel
        -   Indexación con columnas de DataFrame
    -   8.2 Combinar y fusionar conjuntos de datos
        -   Uniones de DataFrame de estilo de base de datos
        -   Fusionando en el índice
        -   Concatenación a lo largo de un eje
        -   Combinar datos con superposición
    -   8.3 Remodelación y pivotaje
        -   Remodelación con indexación jerárquica
        -   Giro de formato "largo" a "ancho"
        -   Giro de formato "ancho" a "largo"
    -   8.4 Conclusión

-   9.trazado y visualización
    -   9.1 Una breve introducción a la API de matplotlib
        -   Figuras y subtramas
        -   Colores, marcadores y estilos de línea
        -   Garrapatas, etiquetas y leyendas
        -   Anotaciones y dibujos en una subtrama
        -   Guardar parcelas en archivo
        -   Configuración de matplotlib
    -   9.2 Conspiración con pandas y seaborn
        -   Gráficos de línea
        -   Gráficos de barras
        -   Histogramas y gráficos de densidad
        -   Gráficos de puntos o de dispersión
        -   Cuadrículas de facetas y datos categóricos
    -   9.3 Otras herramientas de visualización de Python
    -   9.4 Conclusión

-   10.Agregación de datos y operaciones grupales
    -   10.1 Mecánicas GroupBy
        -   Iterando sobre grupos
        -   Seleccionar una columna o subconjunto de columnas
        -   Agrupar con dictados y series
        -   Agrupación con funciones
        -   Agrupación por niveles de índice
    -   10.2 Agregación de datos
        -   Aplicación de función múltiple y de columna inteligente
        -   Devolver datos agregados sin índices de fila
    -   10.3 Aplicar: general dividir-aplicar-combinar
        -   Suprimir las teclas de grupo
        -   Análisis cuantiles y de cangilones
        -   Ejemplo: completar valores perdidos con valores específicos de grupo
        -   Ejemplo: muestreo aleatorio y permutación
        -   Ejemplo: correlación y promedio ponderado de grupo
        -   Ejemplo: regresión lineal de grupo
    -   10.4 Tablas dinámicas y tabulación cruzada
        -   Tabulaciones cruzadas: tabla cruzada
    -   10.5 Conclusión

-   11.Serie temporal
    -   11.1 Tipos de datos y herramientas de fecha y hora
        -   Conversión entre cadena y fecha y hora
    -   11.2 Conceptos básicos de las series temporales
        -   Indexación, selección, subconjunto
        -   Series temporales con índices duplicados
    -   11.3 Rangos de fechas, frecuencias y cambios
        -   Generación de rangos de fechas
        -   Frecuencias y compensaciones de fechas
        -   Datos cambiantes (adelantados y retrasados)
    -   11.4 Manejo de zona horaria
        -   Conversión y localización de zona horaria
            -   Operaciones con objetos de marca de tiempo con reconocimiento de zona horaria
            -   Operaciones entre diferentes zonas horarias
    -   11.5 Períodos y aritmética de períodos
        -   Conversión de frecuencia de período
        -   Frecuencias del período trimestral
        -   Conversión de marcas de tiempo en períodos (y viceversa)
        -   Crear un PeriodIndex a partir de matrices
    -   11.6 Remuestreo y conversión de frecuencia
        -   Submuestreo
        -   Sobremuestreo e interpolación
        -   Remuestreo con períodos
    -   11.7 Funciones de ventana móvil
        -   Funciones ponderadas exponencialmente
        -   Funciones de ventana móvil binaria
        -   Funciones de ventana móvil definidas por el usuario
    -   11.8 Conclusión


-   12 pandas avanzados
    -   12.1 Datos categóricos
        -   Antecedentes y motivación
        -   Tipo categórico en pandas
        -   Cálculos con categóricos
        -   Métodos categóricos
    -   12.2 Grupo avanzado por uso
        -   Transformaciones de grupo y GroupBys "no envueltos"
        -   Remuestreo de tiempo agrupado
    -   12.3 Técnicas para el encadenamiento de métodos
        -   El método de la tubería
    -   12.4 Conclusión

-   13.Introducción a las bibliotecas de modelado en Python
    -   13.1 Interfaz entre pandas y código de modelo
    -   13.2 Creación de descripciones de modelos con Patsy
        -   Transformaciones de datos en fórmulas Patsy
        -   Datos categóricos y Patsy
    -   13.3 Introducción a los modelos de estadísticas
        -   Estimación de modelos lineales
        -   Estimación de procesos de series de tiempo
    -   13.4 Introducción a scikit-learn
    -   13.5 Continuación de su educación

-   14.Ejemplos de análisis de datos
    -   14.1 1.Datos de USA.gov de Bitly
        -   Contando zonas horarias en Pure Python
        -   Contando zonas horarias con pandas
    -   14.2 Conjunto de datos MovieLens 1M
        -   Medición del desacuerdo en las calificaciones
    -   14.3 Nombres para bebés de EE. UU. 1880-2010
        -   Análisis de tendencias de nombres
    -   14.4 Base de datos de alimentos del USDA
    -   14.5 Base de datos de la Comisión Electoral Federal de 2012
        -   Estadísticas de donaciones por ocupación y empleador
        -   Montos de donación agrupados
        -   Estadísticas de donaciones por estado
    -   14.6 Conclusión
