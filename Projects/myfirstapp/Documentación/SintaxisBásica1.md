# Sintaxis Básica en C# p.1

## ¿Que son los comentario y como construirlos?

Podemos decir que un comentario es una apreciación que podemos realizar tanto de forma escrita como de forma oral de un objeto que hemos analizado previamente, emitiendo un juicio valorativo, en programación los comentarios tienen un papel muy fundamnetal ya que nos permiten describir a detalle la función que cumple ciertas lineas de código, adémas de eso los comentarios nos ayudan a recordar la funcionalidad de esta linea eso se es muy util cuando se está trabajando en un proyecto con varias personas.

Los comentarios que usamos a la hora de programar tienden a ocupar mas de una linea en la mayoría de los casos, para los IDE los comentarios son lineas de código que no pueden ser ejecutadas o visualizadas en un navegador web es decir son líneas de código que solo puden leer los programadores.

## Tipos de comentarios en Programación 

En programación hay dos tipos de comentarios, los comentarios de una sola linea y los comentarios de multilinea.

- Los comentarios de una sola linea: como su nombre lo indica este tipo de comentarios se usan en una sola linea con el objetivo de ser breves y consiso ya que se usan para especificar la función de una linea, para construir o iniciar un comentario de una sola linea usaremos la barra diagonal izquierda y la ubicación del comentario ha de ser al final de la linea que queremos comentariar.

#### Ejemplo:
~~~
Using SYstem;

namespace PrimeraAplicación
{
    class Program
    {
        Static void Main(string[]args)
        {
            console.WriteLine("Hello World!");//Console.WriteLine(""); se usa para imprimir en la consola.
        }
    }
}
~~~

- Los comentarios multilineas: como su nombre lo indica este tipo de comentarios se usan en varias linas con el objetivo de tener una descricción mucho mas detallada sobre el código y su funcionalidad en un sistema de información, este tipo de comentarios suelen ser muy usados y extensos ya que nos permite conocer a fondo y a adetalle un código y su función, para construir un código  multilinea usaremos la barra diagonal izquierda acompañada de un asterisco y para cerrarlo usaremos el asterisco primero seguido de la barra diagonal izquieda, la ubicación puede ser la que nos convenga.

#### Ejemplo:
~~~
Using System; 

namespace PrimerAplicación
{
    class Program 
    {
        Static void Main(string[]args)
        {
            console.WriteLine("Hello World!");
            /*
            Esto es un Hello World básico elaborado en C#
            en donde el primer comando nos ubica en al interior
            del sistema, el sugundo nos indica el nombre del proyecto,
            el tercero es una clase, el cuarto es el tipo de caracter que se 
            usara y el ultimo es la instrucción del programa.
            */ 
        }
    }
}
~~~

## Funciones Extras en los comentarios

Una de las funciones adicionales que se les llegar a dar a los comentarios es la de poder inhabilitar lineas de código, eso nos ayuda mucho a la hora de comprodar cual es la funcionalidad en concreto de esa linea que estamos inhabilitando,

#### Ejemplo:

si inhabilitamos la linea de console.WriteLine("Hello World!"); ya no podremos ver lo que se encuentra alojado en ese espacio, ya que la linea esta siendo ignorada por el IDE.
~~~
Using SYstem;

namespace PrimeraAplicación
{
    class Program
    {
        Static void Main(string[]args)
        {
            //console.WriteLine("Hello World!");
        }
    }
}
~~~

## Los errores de sintaxis en C#

En C# los errores de sintaxis en programas muy extensos llegan a ser mas comunes de lo que se cree. para poder identificar los errores de sintaxis el programa nos mostrar al costado izquierdo de la linea en la cual se esta presentando el error una bombilla o en otros casos un destornillador junto una linea de color rojo que se encontrara en la parte de abajo de la instrucción.

si por alguna razon llagamos a depurar el programa, en la consola se nos mostrará un error de complición que nos va a describir cual es el error que se ha identificado en el programa, el error de compilación no desaparecera de la  consola hasta que solucionemos los errores de sintaxis que se presentan en el programa.

## Las palabras reservadas o identificadores

Los identificadores son aquellas palabras unicas y predifinidas que se encuentran en el código, este tipo de palabras no se pueden usar en variables o constantes ya que al ser palbras predifinidas su función ya esta establecida en el programa. esta se usan para poder identificar los elementos que se encuentren en el programa como lo pueden ser:

- Namespace
- Clases o class
- Métodos 
- Variables 
- Constantes 

1. Para poder usar un edentificador es necesario saber que solo esta permitido usar letras pueden ser mayúsculas o minúsculas, guines bajos , números.

#### Ejemplo:

~~~
namespace PrimeraAplicación

/* Este es un buen identificador ya que cuenta con los requerimientos basicos para un identificador funcional*/

namespace Pimera-Aplicación 

/* Esto es un mal identificador ya que posee caracteres los cuales no estan pirmitidos en C#, si se llega a usar de esta forma nos saltara un error de sintaxis*/
~~~

2. Los identificadores en C# deben empezar por guiones bajos o nombres pero no puden inicar con números ademas los identiifcadores no deben de poseer un espacio en su interior  
 
#### Ejemplo:

~~~
namespace PrimeraAplicación2

/* Este es un buen identificador ya que cuenta con los requerimientos basicos para un identificador funcional*/

namespace -Pimera Aplicación 

/* Esto es un mal identificador ya que posee caracteres los cuales no estan pirmitidos en C#, si se llega a usar de esta forma nos saltara un error de sintaxis*/
~~~

3. Para poder establecer un identificador nuevo no se pueden usar la palabras claves o palabras reservadas, ya que este tipo de palabras son las que se llegan a usar por el lenguaje de programación para sus propios propositos, las palabra reservadas son faciles de identificar ya que poseen un color azul.

#### Ejemplo:

~~~

class nameespace

// Esta clase esta mal estructurada ya que cuenta con una palabra reservada. 

~~~

## Convenciones en C#

Las convenciones son aquellas acciones que no solo nos permiten tener un código funcional, si que tambien lejible ya que nos dicen de que forma correcta se estructura un programa.

- Espacios: los espacios en C# son fundamentales e infinitos pero lo recomendable es no llegar a sobrepasarse de ciertos limitantes 

- Sangrias: la sangria es la separación que realizamos del código fuente ante la margen que podemos ver el los IDE, tener una buen sangria nos permitira tener un programa mas legible.