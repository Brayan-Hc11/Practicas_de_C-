# Pruebas_C# <img alt="" style="width: 50px; height: 50px;" class="" src="https://tse3.mm.bing.net/th?id=OIP.dDiDKax3YyAEQsjMXkrPoAHaHa&amp;pid=Api&amp;P=0" id="yui_3_5_1_1_1682280372914_520">

## ¿Qué es C#?

C# es un lenguaje de programación moderno, innovador, de código abierto, multiplataforma orientado a objetos y uno de los 5 principales lenguajes de programación de GitHub. ¿Tiene experiencia con JavaScript, Java o C++? C# le resultará familiar al instante y disfrutará de sus características en constante evolución, como seguridad de tipos, genéricos, coincidencia de patrones, asincrónico, registros, y mucho más.


## Caracteristicas de C#

1). C# se trata del lenguaje lider de la plataforma Windows.<br>
2). C# es la parte fundamental de todas las herramientas de desarrollo de MicroSoft en especial (Visual Studio y .NET).<br>
3). C# nos permite crear aplicaciones de todo tipo: Web, móviles, Videojuegos...etc.<br>
4). C# tiene una sintaxis muy similar a la de Java, C, C++.<br>


## Temario de aprendizaje

1. Sintaxis de C#
   1. Variables 
   2. Operaciones 
   3. Expreciones 
   4. Bucles 
   5. Codicionales 

2. POO
   1. Clases 
   2. Objetos 
   3. Estructuras 
   4. Tipos enumerados 
   5. Arrays 
   6. Herencia 
   7. Interfaces 
   8. Excepciones 

3. Caracteristícas Avanzadas 
    1. Propuedades  
    2. Indexaciones 
    3. Tipos genéricos 
    4. Colecciones 
    5. Sabrecarga  
    6. Trabajo con archivos 
    7. serialización 

4. Construcción de aplicaciones para Windows 10
    1. Interfaces de usuario <br>
    2. Acceso a BBDD <br>
    3. Integración con Windows Store <br>

## Software de uso 
El IDE o entorno de desarrollo que se va ha estar usar en el desarrollo de C# será [Visual Studio Code](https://code.visualstudio.com/ "Viaula Studio Code"). La Versión estable que se estará usando durante el desarrollo será: 10.0 del 21 de marzo del 2022

### Nivel de conocimiento 
 Al finalizar la formación podrá adquirir un nivel de conocimiento "Básico-medio" en el lenguaje de programación C#.

## Tipos de aplicaciones en C#

### Aplicaciones de consolas

  - Son aquellas aplicaciones que se ejecutan desde una ventana de comandos. Este tipo de aplicaciones sulen ser sencillas pero esto no quiere decir que lleguen a ser
  poco utiles, si no que suelen ser sencillas de aprender que las aplicaciones de escritorio o que las aplicaciones web.
 
### Aplicaciones de escritorio
  
  - Son aquellas aplicaciones  que se ejecutan y se visualizan a traves de una IGU (Interfas Gráfica de usuario)/ una ventana interactiva en la que se pueden incluir botones, barras, checbox ...etc
  
### Aplicaciones Web

  - Son aquellas aplicaciones que se ejecutan y se vidualizan a traves de un Navegador web.

## Instalación y configuración del IDE

 Para el desarrollo de nuestra formación estaremos creando nuestra primera aplicación de consola usando nuestro IDE [Visual Studio Code](https://code.visualstudio.com/ "Viaula Studio Code").

1). Para el desarrollo de nuestra primera aplicación de consola, ejecutaremos el IDE [Visual Studio Code](https://code.visualstudio.com/ "Viaula Studio Code") que  ya hemos instalado previmente, el proceso de instalación puede llegar a tardar un poco.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/302fc708-517c-4372-897f-3c403456ca58)

2). Iniciaremos el programa oprimiendo el icono que se encuentra en el escritorio.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/985f6c0e-8ad9-4c45-bcd3-d6cf149cdebf)

3). Por si soló  [Visual Studio Code](https://code.visualstudio.com/ "Viaula Studio Code") no es capaz de ejecutar  y compliar el código de C#, asi que para poder solucionar este percanse usaremos un [SDK](https://dotnet.microsoft.com/en-us/download "SDK") que es un conjunto de programas que nos permitira crear y ejecutar el código de C#

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/dfd5f32a-57da-4128-b694-4116cd5546bf)

4). El Dot.Net que estaremos usando será el .Net 7.0 que nos permitira crear nuestras aplicaciones de consolas, la descarga del archivo puede tardar varios minutos.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/e008cc72-7002-4787-b717-9c008fb671c5)

5). Procedemos a ejecutar el instalador para poder descargar el archivo, este proceso no debe de tardar demaciado.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/0c51bbbe-3143-41f6-82f5-93e1cb599482)

6). para verificar que este instalado de forma correcta y verificar que sea la versión adecuado usaremos la consola de comandos local, para iniciarla usaremos el comando (Win + R) y en el buscador ingresamos las letras "CMD"

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/5281c5bb-7820-48e5-8bf9-e3b69456b5e4)

7). Ahora dentro de la consola de comandos usaremos el comando (Dotnet --Vesion) y debera saltarnos la información que buscamos.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/d5d1c36f-d06d-4855-84ab-c1b4862c0cb4)

8). crearemos una carpeta desde la consola de comandos o terminal con ayuda de los comandos "mkdir projects" de forma instantania se nos aparecera una carpeta en el escritorio bajo en nombre de projects.

![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/7c4928f3-6df0-4416-8d6a-f5f52ac73d55)

9). dentro de esta carpeta crearemos un directorio  en donde alojaremos nuestra primer aplicación de consola con el una serie de comandos especificos, despues de ejecutar los comandos nos tiene que crear nuestra primera aplicación de consola que se encuentra en una carpeta con el nombre de myfirstapp.
~~~
c:\Users\Usuario\OneDrive\Escritorio\Projects>dotnet new console -o myfirstapp
~~~
![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/8713e101-34a1-463d-a07b-5152efb3a7e7)

10). para ejecutar nuestra pirema app tendremos que usar otro comando 
~~~
c:\Users\Usuario\OneDrive\Escritorio\projects\myfirstapp>code . 
~~~
![image](https://github.com/Brayan-Hc11/Practicas_de_C-/assets/118775234/7df6ddf2-50ab-464e-80e0-d4f2c0af9c46)






## Bibliografia
### Fuentes de información 
- <a href="https://dotnet.microsoft.com/es-es/languages/csharp"> C# MicroSoft Lenguajes </a>
- <a href="https://www.youtube.com/playlist?list=PLU8oAlHdN5BmpIQGDSHo5e1r4ZYWQ8m4B"> Pilboras Informaticas </a>
