# curso-programacion Juan Fernando

## Clonado de un proyecto con git
** cd .. ir una carpeta atras**
C:\Users\juanf>cd ..
C:\Users>cd ..
**mkdir para crear un directorio**
C:\>mkdir proyectos-programacion
C:\>cd proyectos-programacion

**Clonacion del proyecto -> comando git clone**
C:\proyectos-programacion>git clone https://github.com/JFMM07/programacion-java.git
Cloning into 'programacion-java'...
warning: You appear to have cloned an empty repository.

**listar un directorio**
C:\proyectos-programacion>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 0C80-D7F3

 Directorio de C:\proyectos-programacion

14/01/2022  03:37 p. m.    <DIR>          .
14/01/2022  03:37 p. m.    <DIR>          ..
14/01/2022  03:37 p. m.    <DIR>          programacion-java
               0 archivos              0 bytes
               3 dirs  152,960,925,696 bytes libres

C:\proyectos-programacion>
 
 ## Comandos git
 
 **git add .**
 Comando que sirve para agregar los archivos al repositorio se puede usar git add nombre_archivo
 
 **git pull**
 Sirve para bajar los archivos del repositorio la version actual del repositorio
 
 **git commit**
 Sirve para poner un mensaje a la carga de archivos ejemplo git commit -m "Mensaje de carga"
 
 **git push**
 Subir archivos locales despues de git add y git commit  se usa git push -u origin main, siendo origin los archivos locales y main el repositorio de git
