# ¿Qué es la Bioinformática?💻
Se define como la aplicación de herramientas computacionales para la captura e interpretación de información biológica. Es una disciplina que involucra el uso de la computación para recolectar, almacenar, analizar y difundir datos biológicos e información (Bayat A, 2002).

La bioinformática utiliza ciencias como la biología, química, matemáticas, estadística y ciencias de la computación para formar una disciplina única (T P, Aneesh. 2011). 

## ¿Por qué aprender bioinformática con Linux? 🤔💡
* La mayoría de herramientas bioinformáticas solo pueden usarse a través de líneas de comando. Ejemplo de ello es [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi), el cual ofrece funciones avanzadas disponibles para usuarios familiarizados con el uso de un un Shell.
* El uso de Shell permite la automatización de tareas repetitivas que implican grandes cantidades de archivos.
* Utilizar un Shell reduce significativamente la probabilidad de errores en comparación con la ejecución manual de tareas repetitivas. Mientras que los humanos pueden cometer errores al repetir una tarea cientos de veces, las computadoras pueden realizarla miles de veces sin errores.
* El registro de los pasos realizados facilita la reproducibilidad del trabajo, lo que es fundamental en la investigación científica.
* Las tareas bioinformáticas suelen requerir una gran potencia informática, que puede obtenerse mediante el acceso a computadoras remotas o a través de servicios en la nube, accesibles mediante un Shell.

Las siguientes definiciones permiten un mejor entendimiento de los pasos posteriores que realizaremos al instalar o ejecutar Linux.

## Sistemas Operativos (SO)🐧🪟

Son una forma de software que gestiona los procesos informáticos. Interactúan con el hardware de un dispositivo y coordinan las funciones entre el software y las aplicaciones, lo que permite que los dispositivos funcionen sin problemas. Las computadoras portátiles, de escritorio y los teléfonos móviles tienen sistemas operativos que administran sus funciones de software y hardware. 

⚠️⚠️⚠️ A partir de este momento, será importante visualizar los componentes como si se tratase de un sistema en conjunto, por ello, las siguientes definiciones están en viñetas  para evitar confundirnos y relacionarlas fácilmente.⚠️⚠️⚠️
 
Habíamos mencionado que el SO es la interfaz entre el usuario y el hardware. El que utilizaremos será:

### 💻LINUX

Este SO es de código abierto, desarrollado por una comunidad, funcional para computadoras, dispositivos móviles, etc. 

 *  **💻 S h e l l** :
Es un programa informático que funciona como intérprete de órdenes o comandos. De esta forma, recibe instrucciones y las traduce para que el equipo las ejecute (Epitech Spain, 2023).
 Permite que el usuario ingrese comandos de texto para relizar diferentes tareas en el sistema.

    - **💻B a s h**:
      
Abreviación de Bourne Again Shell. Es un tipo especial de Shell. También es un lenguaje de programación, utilizado en SO como MacOs y Linux. os sirve para editar archivos, obtener páginas web y automatizar trabajos.

Se puede usar Bash en la mayoría de sistemas operativos Linux y OS abriendo una terminal.

En general, el shell puede aparecer de esta forma en  tu ordenador o en el editor de código que utilizarás. 
![image](https://github.com/landalab0/IntroduccionBioinformaticaLinux/assets/160525027/43ca7d68-3750-4ff4-8334-d48901651729)


Ahora que ya conocemos estos conceptos súper importantes, es importante conocer sobre la **secuenciación masiva** 

# Secuenciación masiva 🧬 
También conocida como secuenciación de nueva generación son estrategias nuevas que han surgido debido a la necesidad de realizar secuenciaciones a gran escala, así como para acortar tiempos y costos.

Existen distintas técnicas de secuenciación de nueva generación que utilizan diferentes tecnologías. Sin embargo, la mayoría comparte características como:
-  Altamente paralelas: ocurren muchas reacciones de secuenciación al mismo tiempo.
-  Microescala: las reacciones son diminutas y se pueden hace mucgas a la vez en un chip.
-   Rápidas: como las reacciones se realizan en paralelo, los resultados están listos más rápido.
-   Bajo costo: menor costo que la secuenciación de Sanger.
-  Longitudes más cortas: las lecturas se obtenien con fragmentos de entre 50-700 nucleótidos de longitud.

Un experimento de secuenciación masiva consta de 4 etapas principales: 
1. La extracción del ADN de la muestra o aislado.
2. La preparación de las bibliotecas o librerías.
3. La secuenciación.
4. El análisis bioinformático e interpretación de los resultados.

La bioinformática es importante para las secuenciaciones ya que se necesita utilizar herramientas computaciones para poder realizar el aliniamiento de las secuencias
y posteriormente generar una base de datos con las variantes obtenidas.
Las plataformas de secuenciación masiva más comunes son Illumina, Ion Torrent y PacBio. Las lecturas obtenidas en las secuenciaciones son
almacenadas en archivos fastq. 

Si quieres conocer más sobre el proceso de la secuenciación masiva, visita el video que te dejamos en el siguiente link 😆
https://www.youtube.com/watch?v=p9vSvJKUyRE 

⏩Después de conocer estos conceptos, laccederemos al Shell en la [unidad 2](https://github.com/landalab0/IntroduccionBioinformaticaLinux/blob/main/Unidad2_Acceso.md)


### Referencias
1. Bayat A. 2002. Science, medicine, and the future: Bioinformatics. BMJ (Clinical research ed.). 324(7344), 1018–1022. 

2. T P, Aneesh. 2011. Bioinformatics-The Explosion of Modern Science and Technology. Drug Invention Today. 3. 262-264. 
Nature Human Genome Research Institute. 2024.



