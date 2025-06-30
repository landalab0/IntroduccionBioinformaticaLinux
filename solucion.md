###   Solución paso a paso **Ejercicio** 🧩
- Crea un nuevo directorio con el nombre de "Taller1" dentro del directorio *taxonomy*

``` bash 
   mkdir -p taxonomy/Taller1
``` 
-  Ir al directorio recién creado.
 ``` bash 
  cd taxonomy/Taller1
```  
-  Crea un archivo de texto con el nombre *"README.md"*
 ``` bash
nano README.md
 ``` 
-  Entra a **README.md** y escribe el nombre del taller.
 ``` bash
 echo "# Taller 1: Introducción Bioinformática con Bash" > README.md
 ``` 
-  Dirígete al directorio *data* y a la carpeta ***untrimmed_fastq***
 ``` bash
cd data/untrimmed_fastq

 ``` 
-  Descomprime los archivos de la carpeta con el comando  ***gunzip***

 ``` bash
gunzip *.gz

 ``` 
-  Copiar el archivo **"JC1A_R1.fastq"** y cambiar el nombre a **"prueba"**

 ``` bash

cp JC1A_R1.fastq ../../taxonomy/Taller1/prueba.fastq

 ``` 
-  Eliminar el archivo **"prueba"** de la carpeta ***untrimmed_fastq***

 ``` bash

rm JC1A_R1.fastq

 ``` 
