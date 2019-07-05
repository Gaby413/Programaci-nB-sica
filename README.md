# Programación Básica

----

## Curso Básico Python

### ¿Qué es Python?

Es un lenguaje de programación creado por \*Guido Van Rossum\* a los principios de los años 90&#39;s cuyo nombre esta inspirado en el grupo de cómicos ingleses \*\*&quot;Manty Python&quot;\*\*. Es un lenguaje similar a \*\*&quot;C&quot;\*\* pero con una sintaxis muy limpia y que favorece un código legible.

----

### Lenguaje interpretado o de script

Lenguaje interpretado o de script es aquel que se ejecuta utilizando un programa intermediario , que se llama interprete en lugar de copilar el código al lenguaje maquina de lenguajes compilados.

La ventaja de los lenguajes compilados es que su se ejecución es mas rápida sin embargo los lenguajes interpretados son mas flexibles y portados.

----

### Introducción a los ejercicios de programación

Podremos diseñar los siguientes tema:

\* Generar una salida con la sentencia \*\*print\*\*

\* Leer la entrada del usuario con el teclado usando \*\*raw-input\*\*

\*Realizar cálculos sencillos con suma (\*\*+\*\*), resta (\*\*-\*\*), multiplicación (\*), división (\*\*/ o //\*\*), modulo (\*\*%\*\*) y potencia (\*\*).

\*Realizar cálculos mas complejos con el modulo \*\*math\*\*

Existen dos formas de ejecutar código en python, la cual puede ser mediante una sesión interactiva \*\*linea o lineal\*\* con el interprete o bien de la forma habitual, escribiendo el código en un archivo de código fuente y ejecutando.

\&gt;Ejemplo:

     nombre= &#39;Gaby Flores&#39;

     calle= &#39;Cardenal 6&#39;

     colonia= &#39;Minas el Tecolote&#39;

     municipio= &#39;Naucalpan de Juarez&#39;

     estado= &#39;Estado de Mexico&#39;

     codigoPostal= 53697

     print(nombre , &#39;\n&#39; , calle , &#39;\n&#39; , colonia , &#39;\n&#39;, municipio , &#39;\n&#39; , estado , &#39;\n&#39; , codigoPostal)

----

###Tipos de datos básicos

En python los tipos de datos básicos se dividen en, números, como pueden ser 3 (\*entero ó integer\*) 1.75, (\*punto flotante ó float\*) 7+5j (\*complejos ó complex\*).

Para poder conocer el tipo de dato de una variable usaremos la instrucción \*\*type()\*\*.

Los números flotantes son los que tienen decimales. En python se expresan mediante el tipo \*\*float\*\*

Los números complejos son aquellos que tienen una parte imaginaria. Para definir una variable compleja se utiliza el termino \*\*complex\*\*.

\&gt;Ejemplo:

     import math

     a = float(input(&#39;Ingresa un numero&#39;))

     b = float(input(&#39;Ingresa un numero&#39;))

     s = a+b

     r = b-a

     p = a\*a

     d = a/b

     m = a%b

     e = a\*\*b

     l = (math.log10(a))

     print(&#39;El resultado de la suma es:&#39;,s)

     print(&#39;El resultado de la resta es:&#39;,r)

     print(&#39;El resultado de la multiplicacion es:&#39;,p)

     print(&#39;El resultado de la division es:&#39;,d)

     print(&#39;El residuo de la division es:&#39;,m)

     print(&#39;El resultado de la potencia es:&#39;,e)

     print(&#39;El resultado de la logaritmo es:&#39;,l)

----

###Tipos de variables

\*\*Salto de pagina\*\*

&#39;\n&#39;

\&gt;Ejemplo:

     print(nombre + &#39;\n&#39; + calle&quot;

\*\*Variable flotante\*\*

 Es una variable que puede guardar datos numéricos con punto decimal, para forzar a una variable a que sea flotante usaremos el comando \*\*float()\*\*

\*\*float = numero decimal\*\*

\*\*int = numero entero\*\*

\&gt;Ejemplo:

     a= int(input(&#39;Introduzca las millas por galón que da su carro&#39;))

     b= 1.609344

     print (&#39;los kilómetros por galón que da su automovil es:&#39;, a\*b)

###Sentencias condicionales

Las sentencias condicionales nos permiten comprobar y hacer que nuestro programa se comparte de una forma u otra, que ejecute un fragmento de un código u otro, dependiendo esa condición.

\*\*Condicional &quot;if; else&quot;\*\*

La forma mas simple de una sentencia condicional es el \*\*if\*\* (del ingles &quot;si&quot;) seguida de la condicion a evaluar, (:) y en la siguiente linea \*\*in dentado\*\* el código a ejecutar en caso de que se cumpla dicha condición.

\&gt;Ejemplo:

     password\_user1 = input(&#39;Inserte su nuevo password: &#39;)

     password\_user2 = input(&#39;Confirme password: &#39;)

     if password\_user1 == &quot;password\_user2&quot;:

          print(&#39;Su password ha sido establecido&#39;)

     else:

          print(&#39;Lo siento, ha introducido mal sus datos&#39;)

     print(&#39;Gracias!&#39;)

\*\*Bucles\*\*

Los bucles permiten ejecutar un mismo fragmento de código un cierto numero de veces mientras se cumpla una determinada acción condición

\*While\*

El bucle \*\*while\*\* ejecuta un fragmento de código mientras se cumpla la condición.

\*Ciclo For\*

En pyhton \*\*for\*\* se utiliza como una forma genérica de interés sobre una secuencia, es decir, recorrer una secuencia.

\&gt;Ejemplo:

    for celcius in arange(0,101,10):

        farenheit = 1.8 \* celcius + 32

        print(celsius, &#39;gc&#39;, &#39;|&#39;,farenheit, &#39;gf&#39;)

----

###Funciones

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. A demás de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones también permiten reutilizar código.

Las Funciones ayudan al programador a dividir un problema en pequeñas piezas que pueden ser re usadas. También ayudan al programador a concentrarse en una pequeña parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware.

En nuestro caso debemos aprender a:

\*Definir una función para usarla después.

\*Pasar uno o más valores a una función.

\*Desarrollar un cálculo complejo en una función.

\*Regresar uno o más resultados a una función.

\*Llamar a una función que previamente hayamos definido.

\&gt;Ejemplo:

     #definición de una función

      def tarifa(kilómetros):

          tarifa=7.00\*kilómetros+7.25

          if tarifa\&lt;40:

              return 40

          return tarifa

     km=float(input(&#39;Inserta los kilómetros

     recorridos:&#39;))

     precio =tarifa(km)

     print(&#39;Precio final:&#39;, precio)



----

###Programación Orientada a Objetos

Al principio del curso comentamos que Python es un lenguaje multiparadigma en el que se podía trabajar con programación estructurada, como veníamos haciendo ahora o con programación orientada a objetos el cual es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestro problema se modelan a través de clases y objetos, y en el que nuestro programa consiste en una serie de interacciones entre objetos.

\*\*Objetos\*\*

Un objetos es una entidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define a través de variables llamadas atributos, mientras que la funcionalidad de modela a través de funciones a las que se les conoce con el nombre de métodos del objeto.

\*\*Clases\*\*

Una clase no es más que una plantilla genérica de la cual instancia los objetos; es la plantilla que define que atributos y métodos tendrán los objetos de esa clase.

\&gt;Ejemplo:

     class Coche(object):

        def \_\_init\_\_(self,gasolina):

             self.gasolina = gasolina

        def arrancar(self):

             if self.gasolina \&gt; 0:

            print(&#39;Arranca&#39;)

             else:

                 print(&#39;No Arranca&#39;)

         def conducir(self):

             if self.gasolina \&gt; 0:

                 self.gasolina = self.gasolina - 1

                 print(&#39;Quedan &#39;, self.gasolina,&#39; litros&#39;)

             else:

                 print(&#39;No se mueve&#39;)

     vocho = Coche(5)

     tsuru = Coche(3)

     vocho.arrancar()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

----

###Modulo Turlte

Hay muchos módulos en python que proveen características poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

\&gt;Ejemplo:

     import turtle

     def dibujar\_cuadro\_caracol(tur, d):

         for i in  [&#39;red&#39;,&#39;red&#39;,&#39;red&#39;,&#39;red&#39;]:

             tur.color(i)

             tur.forward(d)

             tur.left(90)

     ventana=turtle.Screen()

     ventana.bgcolor(&#39;yellow&#39;)

     ventana.title(&#39;funciones&#39;)

     alex=turtle.Turtle()

     alex.pensize(2)

     alex.speed(100)

     d=100# Programación Básica

----

## Curso Básico Python

### ¿Qué es Python?

Es un lenguaje de programación creado por \*Guido Van Rossum\* a los principios de los años 90&#39;s cuyo nombre esta inspirado en el grupo de cómicos ingleses \*\*&quot;Manty Python&quot;\*\*. Es un lenguaje similar a \*\*&quot;C&quot;\*\* pero con una sintaxis muy limpia y que favorece un código legible.

----

### Lenguaje interpretado o de script

Lenguaje interpretado o de script es aquel que se ejecuta utilizando un programa intermediario , que se llama interprete en lugar de copilar el código al lenguaje maquina de lenguajes compilados.

La ventaja de los lenguajes compilados es que su se ejecución es mas rápida sin embargo los lenguajes interpretados son mas flexibles y portados.

----

### Introducción a los ejercicios de programación

Podremos diseñar los siguientes tema:

\* Generar una salida con la sentencia \*\*print\*\*

\* Leer la entrada del usuario con el teclado usando \*\*raw-input\*\*

\*Realizar cálculos sencillos con suma (\*\*+\*\*), resta (\*\*-\*\*), multiplicación (\*), división (\*\*/ o //\*\*), modulo (\*\*%\*\*) y potencia (\*\*).

\*Realizar cálculos mas complejos con el modulo \*\*math\*\*

Existen dos formas de ejecutar código en python, la cual puede ser mediante una sesión interactiva \*\*linea o lineal\*\* con el interprete o bien de la forma habitual, escribiendo el código en un archivo de código fuente y ejecutando.

\&gt;Ejemplo:

     nombre= &#39;Gaby Flores&#39;

     calle= &#39;Cardenal 6&#39;

     colonia= &#39;Minas el Tecolote&#39;

     municipio= &#39;Naucalpan de Juarez&#39;

     estado= &#39;Estado de Mexico&#39;

     codigoPostal= 53697

     print(nombre , &#39;\n&#39; , calle , &#39;\n&#39; , colonia , &#39;\n&#39;, municipio , &#39;\n&#39; , estado , &#39;\n&#39; , codigoPostal)

----

###Tipos de datos básicos

En python los tipos de datos básicos se dividen en, números, como pueden ser 3 (\*entero ó integer\*) 1.75, (\*punto flotante ó float\*) 7+5j (\*complejos ó complex\*).

Para poder conocer el tipo de dato de una variable usaremos la instrucción \*\*type()\*\*.

Los números flotantes son los que tienen decimales. En python se expresan mediante el tipo \*\*float\*\*

Los números complejos son aquellos que tienen una parte imaginaria. Para definir una variable compleja se utiliza el termino \*\*complex\*\*.

\&gt;Ejemplo:

     import math

     a = float(input(&#39;Ingresa un numero&#39;))

     b = float(input(&#39;Ingresa un numero&#39;))

     s = a+b

     r = b-a

     p = a\*a

     d = a/b

     m = a%b

     e = a\*\*b

     l = (math.log10(a))

     print(&#39;El resultado de la suma es:&#39;,s)

     print(&#39;El resultado de la resta es:&#39;,r)

     print(&#39;El resultado de la multiplicacion es:&#39;,p)

     print(&#39;El resultado de la division es:&#39;,d)

     print(&#39;El residuo de la division es:&#39;,m)

     print(&#39;El resultado de la potencia es:&#39;,e)

     print(&#39;El resultado de la logaritmo es:&#39;,l)

----

###Tipos de variables

\*\*Salto de pagina\*\*

&#39;\n&#39;

\&gt;Ejemplo:

     print(nombre + &#39;\n&#39; + calle&quot;

\*\*Variable flotante\*\*

 Es una variable que puede guardar datos numéricos con punto decimal, para forzar a una variable a que sea flotante usaremos el comando \*\*float()\*\*

\*\*float = numero decimal\*\*

\*\*int = numero entero\*\*

\&gt;Ejemplo:

     a= int(input(&#39;Introduzca las millas por galón que da su carro&#39;))

     b= 1.609344

     print (&#39;los kilómetros por galón que da su automovil es:&#39;, a\*b)

###Sentencias condicionales

Las sentencias condicionales nos permiten comprobar y hacer que nuestro programa se comparte de una forma u otra, que ejecute un fragmento de un código u otro, dependiendo esa condición.

\*\*Condicional &quot;if; else&quot;\*\*

La forma mas simple de una sentencia condicional es el \*\*if\*\* (del ingles &quot;si&quot;) seguida de la condicion a evaluar, (:) y en la siguiente linea \*\*in dentado\*\* el código a ejecutar en caso de que se cumpla dicha condición.

\&gt;Ejemplo:

     password\_user1 = input(&#39;Inserte su nuevo password: &#39;)

     password\_user2 = input(&#39;Confirme password: &#39;)

     if password\_user1 == &quot;password\_user2&quot;:

          print(&#39;Su password ha sido establecido&#39;)

     else:

          print(&#39;Lo siento, ha introducido mal sus datos&#39;)

     print(&#39;Gracias!&#39;)

\*\*Bucles\*\*

Los bucles permiten ejecutar un mismo fragmento de código un cierto numero de veces mientras se cumpla una determinada acción condición

\*While\*

El bucle \*\*while\*\* ejecuta un fragmento de código mientras se cumpla la condición.

\*Ciclo For\*

En pyhton \*\*for\*\* se utiliza como una forma genérica de interés sobre una secuencia, es decir, recorrer una secuencia.

\&gt;Ejemplo:

    for celcius in arange(0,101,10):

        farenheit = 1.8 \* celcius + 32

        print(celsius, &#39;gc&#39;, &#39;|&#39;,farenheit, &#39;gf&#39;)

----

###Funciones

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. A demás de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones también permiten reutilizar código.

Las Funciones ayudan al programador a dividir un problema en pequeñas piezas que pueden ser re usadas. También ayudan al programador a concentrarse en una pequeña parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware.

En nuestro caso debemos aprender a:

\*Definir una función para usarla después.

\*Pasar uno o más valores a una función.

\*Desarrollar un cálculo complejo en una función.

\*Regresar uno o más resultados a una función.

\*Llamar a una función que previamente hayamos definido.

\&gt;Ejemplo:

     #definición de una función

      def tarifa(kilómetros):

          tarifa=7.00\*kilómetros+7.25

          if tarifa\&lt;40:

              return 40

          return tarifa

     km=float(input(&#39;Inserta los kilómetros

     recorridos:&#39;))

     precio =tarifa(km)

     print(&#39;Precio final:&#39;, precio)



----

###Programación Orientada a Objetos

Al principio del curso comentamos que Python es un lenguaje multiparadigma en el que se podía trabajar con programación estructurada, como veníamos haciendo ahora o con programación orientada a objetos el cual es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestro problema se modelan a través de clases y objetos, y en el que nuestro programa consiste en una serie de interacciones entre objetos.

\*\*Objetos\*\*

Un objetos es una entidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define a través de variables llamadas atributos, mientras que la funcionalidad de modela a través de funciones a las que se les conoce con el nombre de métodos del objeto.

\*\*Clases\*\*

Una clase no es más que una plantilla genérica de la cual instancia los objetos; es la plantilla que define que atributos y métodos tendrán los objetos de esa clase.

\&gt;Ejemplo:

     class Coche(object):

        def \_\_init\_\_(self,gasolina):

             self.gasolina = gasolina

        def arrancar(self):

             if self.gasolina \&gt; 0:

            print(&#39;Arranca&#39;)

             else:

                 print(&#39;No Arranca&#39;)

         def conducir(self):

             if self.gasolina \&gt; 0:

                 self.gasolina = self.gasolina - 1

                 print(&#39;Quedan &#39;, self.gasolina,&#39; litros&#39;)

             else:

                 print(&#39;No se mueve&#39;)

     vocho = Coche(5)

     tsuru = Coche(3)

     vocho.arrancar()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

     vocho.conducir()

----

###Modulo Turlte

Hay muchos módulos en python que proveen características poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

\&gt;Ejemplo:

     import turtle

     def dibujar\_cuadro\_caracol(tur, d):

         for i in  [&#39;red&#39;,&#39;red&#39;,&#39;red&#39;,&#39;red&#39;]:

             tur.color(i)

             tur.forward(d)

             tur.left(90)

     ventana=turtle.Screen()

     ventana.bgcolor(&#39;yellow&#39;)

     ventana.title(&#39;funciones&#39;)

     alex=turtle.Turtle()

     alex.pensize(2)

     alex.speed(100)

     d=100
