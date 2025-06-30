# Conoce los comandos ⌨️


## Diagrama  de organización de archivos

![image](https://github.com/landalab0/IntroduccionBioinformaticaLinux/assets/160525027/539c9c88-8b8a-4b46-a6bf-b185b71b712a)

Este diagrama es importante para entender la organización de nuestros archivos. 

El signo de dólares es un *prompt*, nos muestra que la terminal está esparando para un input.

 ``` bash 
 $
 ```

## Comandos básicos

Empezaremos a familiarizarnos con los comandos básicos que necesitaremos para trabajar.

Para saber en donde nos encontramos utilizaremos el comando **`pwd`** 
*     pwd

**`cd`**      nos lleva al directorio home
*     cd
  
**`ls`** nos muestra la lista de contenido de un directorio

*      ls                            

**`cd + nombre de la carpeta`**  para cambiar la ubicación o abrir un archivo

**`cd ..`** para regresar

**`cd ../../..`** para subir/regresar más de un nivel

Para acceder a carpetas con espacio en el nombre, colocamos cd + el nombre de la carpeta en comillas  
*      cd "nombre de la carpeta"

**`ls -f`** poner / al final del nombre de carpetas (directorios)

Si sabes la dirección, pones **`cd`** y la dirección con /
  *     cd dc_workshop/data/untrimmed_fastq

**`ls -l`** para mostrar los detalles de los archivos 

**`FASTQ`** es un formato para almacenar información sobre lecturas de secuenciación y su calidad.
fastq.gz-> la gz significa que es un archivo comprimido 

**`gunzip`** para descomprimir archivos

**` * `** es un carácter llamado comodín (funciona como una n) 
       *fastq -> mostrará todos los archivos que terminan en .fastq

**ls *.fastq** enumera sólo el archivo que termina en fastq

Para repetir comandos que se ejecutaron anteriormente, se puede usar ⬆️ o ⬇️ para avanzar en el historial.

O puedes usar el comando **` history `** para ver una lista de los comandos que has usado recientemente.

Si te interesa alguno en particular, puedes escribir:

**`!`** (número de comando) 

`Atajos:` 

**`ctrl + c`**   cancela lo que estás escribiendo y da un mensaje nuevo

**`ctrl + R`**   hará una búsqueda inversa a través del historial de comandos

**` ctrl + L `** o **`clear`** borrará la pantalla


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

**`cp`** nos ayuda a copiar archivos

 ``` bash 
 cp JC1A_R2.fastq JC1A_R2-copy.fastq
 ls -F
 ```


**`mv`** para mover archivos -> Moveremos JC1A_R2-copy.fastq a backup

*      mv JC1A_R2-copy.fastq backup    

**`mv`** también sirve para cambiar el nombre de los archivos

*     mv JC1A_R2-copy.fastq JC1A_R2-backup.fastq

**` rm -r + nombre del archivo o directorio`** para eliminar

**` grep`** permite navegar entre archivos sin tener que abrirlos

**` wc`** cuenta la cantidad de palabras, líneas y carácteres de un archivo`**

**`nano`** es un editor de texto, con este comando podemos crear un archivo y escribir en él

     nano README.txt

Después de estar satisfechos con lo que escribimos podemos presionar **Ctrl + O + enter**  para guardar 

Para salir de nano presiona **Ctrl + X + enter** 

Para descomprimir:
*     gunzip + "nombre archivo"
para leer:
*            cat
para volver a comprimir: 
*       gzip

## Aplicación💾
Aplicaremos los conceptos vistos previamente en una secuencia de pasos que reúne algunos de los comandos que nos van a ayudar en el trabajo que realizaremos en el shell. Los pasos a seguir están ordenados en forma de lista.

###   Ejercicios
- [ ] Crea un nuevo directorio con el nombre de "Taller1" dentro del directorio *taxonomy* 
- [ ] Ir al directorio recién creado.
- [ ] Crea un archivo de texto con el nombre *"README.md"*
- [ ] Entra a **README.md** y escribe el nombre del taller.
- [ ] Dirígete al directorio *data* y a la carpeta ***untrimmed_fastq***
- [ ] Descomprime los archivos de la carpeta con el comando  ***gunzip***
- [ ] Copiar el archivo **"JC1A_R1.fastq"** y cambiar el nombre a **"prueba"**
- [ ] Eliminar el archivo **"prueba"** de la carpeta ***untrimmed_fastq***
               
Para ver la solución del ejercicio, entra [aquí](https://github.com/landalab0/IntroduccionBioinformaticaLinux/blob/main/solucion.md)












