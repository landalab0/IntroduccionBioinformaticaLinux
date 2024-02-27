# Conoce los comandos ⌨️
Empezaremos a familiarizarnos con los comandos básicos que necesitaremos para trabajar.

Para saber en donde nos encontramos utilizaremos el comando **`pwd`**
*     pwd

**`cd`**      nos lleva al directorio home

**`ls`** nos muestra la lista de contenido de un directorio

*      ls                            

**`cd + nombre de la carpeta`**  para cambiar la ubicación o abrir un archivo

**`cd ..`** para regresar

**`cd ../../..`** para surbir/regresar más de un nivel

Para acceder a carpetas con espacio en el nombre, colocamos cd + el nombre de la carpeta en comillas  
*      cd "nombre de la carpeta"

**`ls-f`** poner / al final del nombre de carpetas (directorios)

Si sabes la dirección, pones **`cd`** y la dirección con /
*      Ej. cd dc_workshop/data/untrimmed_fastq

**`ls-l`** para mostrar los detalles de los archivos 

**`FASTQ`** es un formato para almacenar información sobre lecturas de secuenciación y su calidad.
fastq.gz-> la gz significa que es un archivo comprimido 

**`gunzip`** para descomprimir archivos

**` * `** es un carácter llamado comodín (funciona como una n) 
      Ej. *fastq -> mostrará todos los archivos que terminan en .fastq

**ls*R1.fastq** enumera sólo el archivo que termina en R1.fastq

Para repetir comandos que se ejecutaron anteriormente, se puede usar ⬆️ o ⬇️ para avanzar en el historial.

`Atajos:` 

**`ctrl + c`**   cancela lo que estás escribiendo y da un mensaje nuevo

**`ctrl + R`**   hará una búsqueda inversa a través del historial de comandos

**` ctrl + L `** o **`clear`** borrará la pantalla

**` history `** para revisar comandos recientes

**`!`** (número de comando)

**`cat`** para imprimir en pantalla el contenido de un archivo.

     cat JC1A_R2.fastq 


**`less + nombre del archivo`** abre el archivo en modo lectura y podrás navegar en él.


`Comandos de navegación en less `


| Llave         | Acción           |
| ------------- | -------------    |
|   space       | seguir adelante  |
|     b         | ir hacia atrás   |
|     g         | ir al principio  |
|     G         | llegar al final  |
|     q         |  abandonar       |


**` head + nombre del archivo `** ver el principio del archivo

**` tail + nombre del archivo `**  ver el final del archivo

**` head - n  `**  imprimir la primera n línea de un archivo 

**` tail - n  `**  imprimir la última n línea de un archivo 

**` mkdir`** para crear un directorio 
Hay que poner **mkdir** seguido de un espacio y luego el nombre del directorio a crear

**`mv`** para mover archivos

*     Ej. mv JC1A_R2- copy.fastq backup

**`mv`** también sirve para cambiar el nombre de los archivos

*   Ej.  mv JC1A_R2-copy.fastq JC1A_R2-backup.fastq

**` rm - r + nombre del archivo o directorio`** para eliminar

**` grep`** permite navegar entre archivos sin tener que abrirlos

**` wc`** cuenta la cantidad de palabras, líneas y carácteres de un archivo`**

**`nano`** es un editor de texto, con este comando podemos crear un archivo y escribir en él

     nano README.txt

Después de estar satisfechos con lo que escribimos podemos presionar **Ctrl + O + enter**  para guardar 

Para salir de nano presiona **Ctrl + X + enter** 












