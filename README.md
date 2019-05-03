# AppMp

It is an app for managing files, where you can search and visualize your documents, images, etc. In addition, it allows to clasify
them by category (in which you can add any wanted number), by type of file or by name.
Fuerthermore, you have the option to customize the color of the windows to fullfil the customer wishes.

_________________

Se trata de una aplicacion para gestionar archivos, donde puedes buscar y visualizar documentos, imágenes, etc. También, 
permite clasificarlos por categoría (las cuales puedes añadir la cantidad que quieras), tipo de archivo o nombre.
Además tiene la opción de personalizar el color de las ventanas para satisfacer los gustos de los usuarios.

## Getting Started / Inicialización:

You need to have java installed in your computer (at least java 8). You can use the .jar file that we submitted on the Release tab or
compile it yourself with Netbeans or comands.

To compile with commands:

```
javac *.java 
```
With it you compile all java class generinc .class, witch we will package into the jar file with:

```
jar cf GestorArchivos.jar manifest.mf *.class  
```
The manifest.mf file has to contain the main class GestorArchivos.

Once you have the .jar file, all you need to do is to execute it as a usual aplication with:

```
java -jar .\GestorArchivos.jar
```
__________________

Es necesario tener instalado java en tu pc, recomendamos usar java 8, puedes usar el .jar que publicamos en la pestaña Release o compilarlo tú mismo con Netbeans o comandos.
Los comandos necesarios son:

```
javac *.java 
```
Con este comando compilamos las clases java generando .class, las cuales empaquetaremos en un jar mediante el comando:

```
jar cf GestorArchivos.jar manifest.mf *.class  
```

El manifest.mf tiene que referenciar a la clase principal GestorArchivos.

Una vez tengas el .jar lo puedes ejecutar como una aplicación normal con

```
java -jar .\GestorArchivos.jar
```

### Installing / Instalación:

Any further installation isn't necessary, it's a portable application.
_________________

No es necesaria ningún tipo de instalación, se trata de una aplicación portable.

## Built With / Construido con:

* [NetBeans](https://netbeans.org/) - The used enviroment.
________________
* [NetBeans](https://netbeans.org/) - El entorno de desarrollo utilizado.

## Authors

* **Marina Fernández Suárez** - *Initial idea* - [IhoFenixMFS](https://github.com/IhoFenixMFS)
* **Javier Barrio** - [JavierBarrio](https://github.com/JaviBarrio6)
* **Alejandro García Luna** - [AlejandroGarciaLuna](https://github.com/AlejandroGarciaLuna)
* **Álvaro Orbaneja** - [aorbaneja](https://github.com/aorbaneja)
* **Manuel Antonio Romero** - [ManuelARV](https://github.com/ManuelARV)

