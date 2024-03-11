# CONOCIENDO A R

## Contenido
En esta unidad, conoceremos una una herramienta *R* , la instalación del programa y funciones que podemos llevar a cabo con herramientas que este programa nos proporciona.

## ¿Qué es R?🤨
Es un lenguaje de programación de software libre, que funciona en sistemas operativos como Windows, MacOS y linux. ([Universidad Intyernacional de Valencia,2023](https://www.universidadviu.com/es/actualidad/nuestros-expertos/lenguaje-de-programacion-r-que-es-caracteristicas-e-importancia-en-el-big-data))
R está especializado en informática estadística y gráfica.

## Ventajas de trabajar con R
- El código R es reproducible
- R produce gráficos de alta calidad
- R tiene una gran comunidad
-  R es interdisciplinario
- R funciona con datos de todos los colores y tamaños.
- ¡R es gratis!

## ¿Qué es R Studio?

RStudio es un entorno de desarrolllo integrado (IDE por sus siglas en inglés) para R, que facilita la tarea de uso interactivo de R y la programación de scripts. Proporciona una iinterfaz de usuario amigable que facilita la escritura, depurado y la visualización de código R. 

## Y si aún no tengo R?🥲
No te preocupes, solo seguiremos unos cuantos pasos para poder instalarlo. 

Primero instalaremos R:
 https://cran.rstudio.com/

Entraremos al link y seleccionaremos la descarga para nuestro sistema operativo.

 ![Pink and beige Data Visualization Basics modern presentation](https://github.com/landalab0/IntroduccionBioinformaticaLinux/assets/160524982/fafc53fa-095f-4cee-8238-1073f1a77324)

Cuando lo hayamos elegido seleccionaremos la opción *intall R for the first time* y después lo podremos descargar.

Después podremos descargar R Studio:
https://posit.co/download/rstudio-desktop/

## Descubriendo RStudio

Después de instalar RStudio, podemos abrirlo y lo que nos encontraremos son cuatro páneles de trabajo.
1. Consola: se encuentra en la esquina inferiror izquierda: es el lugar en donde R está esperando a que le digas que hacer. En ella se puede escribir, ejecutar código y ver los resultados de lo que se va ejecutando.
2. Editor de código: ubicado en la esquina superior izquierda. En este panel se abren los archivos en pestañas.


## Tener un diálogo con R

Existen dos formas con las que podemos interactuar con R en RStudio:
- Usando la consola.
- Creación y edición de archivos de script.

La **consola** es en donde se pueden escribir y ejecutar comandos inmediatamente, asímismo aquí se mostraran los resultados de los comandos ejecutados.

Si R está listo para aceptar comandos, la consola mostrará el "**>**" mensaje. Puedes escribir instrucciones directamente en la consola y presionar **Enter**, pero se olvidarán cuando cierre la sesión. 

Sabemos que los humanos olvidamos muchas cosas, por lo tanto, es importante hacer anotaciones para no olvidar. En en el caso de R, podemos hacer comentarios poniendo  "**#**" antes del texto, y con esto podríamos recordarr porque escribimos un comando en nuestro script.


**getwd** nos mostrará el directorio de trabajo

## Tipos de datos

Hay 5 tipos de datos en RStudio
- Numérico (numeric o double): numeros enteros como decimales.

      > x <- 5
      > y <- 3.14

- Enteros (integer)
- Lógicos (logical): True or False
- Caracteres (character)


R provee varias funciones para examinar las características de los objetos que creamos.

**class()** : ¿qué tipo de objeto es?

**typeof()** : ¿qué tipo de dato es?

**length()** : ¿de que tamaño es (cuantos elementos tienen los vectores y listas)?

**attributes()** : ¿tiene el objeto algún metadato?

## Estructuras de datos
Existen diferentes maneras de organizar los datos en R llamados **estructuras de datos**.

Las colecciones o conjunto de datos en R se organizan por su  dimensión (1, 2, o varias dimensiones) y si son homogéneas (todos los objetos deben ser del mismo tipo) o heterogéneas ( el contenido puede ser de diferentes tipos).Las más utilizadas son:

| Dimensión  |   Homogénea   |   Heterogénea  |
| -----------|---------------|----------------|
|     1      |     Vector    |     Lista      | 
|     2      |     Matriz    |   Data Frame   |
|     n      |     Array     |                |


### 🟢 Vector

La estructura de datos más simple es el vector, que es una secuencia de datos del mismo tipo. Podemos crear un vestor usando la función "**c()**" que signifca concatenar o combinar.

*Input*

       > char_vector <- c("a", "a", "b", "b", "c", "c")
       > typeof(char_vector)

*Output*

       [1] "character"

### 🟡 Factor

El factor es una estructura más compleja, que contiene los nombres de categorías (llamadas niveles) y una secuencia de las ocurrencias de esas categorías.

*Input*
       > char_factor <- as.factor(char_vector)
       > char_factor

*Output*

        [1] a a b b c c
        Levels: a b c
        
Y si queremos sabwe la estructura de este objeto, pondríamos:

*Input*

       > str(char_factor)

*Output*

    Factor w/ 3 levels "a","b","c": 1 1 2 2 3 3
    
Podemos ver los niveles de los factores y la secuencia de números. Cada número representa un  nivel, y esta secuencia contiene la información sobre qué va en cada posición. Por eso obtendremos un "entero" si preguntamos por el tipo de datos del objeto.

*Input*

    > typeof(char_factor)

*Output*

    [1] "integer"

Los factores son la mejor manera para organizar datos categóricos.
### 🟣 Lista

A diferencia de una vector, la lista es el conjunto de elementos de distinto tipo.

Se crean con la función **list** 

### 🟠 Matriz

Es una estructura bidimensional.

La función **matrix()** permite crear matrices

### 🔵 Data Frame

Es una estructura de datos bidimensional similar a una matriz, pero funciona distinto. Un data frame es una lista de vectores de la misma longitud, permite tipos de datos mixtos. Esto permite almacenar diferentes tipos de variables.






