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

 