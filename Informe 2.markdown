#Trabajo practico laboratorio de bioinformática

#####Nombre: César Medina Nuñez

#####NCR: BIT120

##Parte 1: Colectar genes homólogos

####1- ¿Qué función cumple el gen SRY?
  Codifica para la proteina TDF, la cual desencadena la diferenciacion de las gonadas masculinas en el embrion.
####2-¿Cuántos genes ortólogos están anotados en esa base de datos?

Se encontraron 18 genes ortologos para SRY.

##Parte 2: Alineamiento múltiple

####1- ¿Qué es el EMBL-EBI?
Es el instituto europeo de bioinformatica, facilitan su base de datos y herramientos en sus paginas para ayudar a todo tipo de investigadores.
####2- ¿Cuántos tipos de alienamiento múltiple se pueden realizar en EMBL-EBI?
Ofrecen 7 tipos de alineamiento multiple.
####3- ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?
 El recomendado por ellos es el programa MUSCLE
####4- ¿Qué otros tipo de herramientas ofrece EMBL-EBI?

Ofrecen distintos programas para secuencias cortas, medianas y largas. Para alineamiento local o global.

####5- ¿Cuál es el costo de abrir un gap?
    
Para la abertura del gap el costo es de 1.53
####6- ¿Cuál es el costo de extender un gap?

Para la extencion del gap es de 0.123

####7- ¿Cuál es la longitud total del alineamiento?

La extencion del alineamiento de de 1184 bases.

###Arbol filogenetico del gen SRY
![Filogenia SRY](http://i64.tinypic.com/nfljs7.png "")

####8- ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?
La especie cuyo gen SRY está más relacionado con el gen SRY de *Homo sapien* es el de *Pan troglodytes*, tambien conocido como chimpance común.

####9- ¿Cuál es el más lejano?
En este caso seria *Pteropus alecto*
####10- ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?
El burro o *Equus asinus* es más cercano a *Equus przewalskii*, tambien conocido como caballo mongol,actualmente en peligro de extinción.
####11- ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?
Al aumentar el costo de abrir un gap el programa evitara abrirlos de forma intercalada, i.e, nucleotido-gap-nucleotido-gap, dandonos un resultado más realista. Por otro lado al disminuir el costo de de abrir un gap el programa puede llegar a intercalar gaps y nucleotidos en relacion 1 es a 1, creando un alineamiento poco probable.
####12- ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?

Al aumentar el costo de extencion del gap estos seran de tamaño reducido, mientras que entre menos el costo de abertura mayor presencia de gaps largo se podran encontrar en el alineamiento.

####13- Prueba aumentando el costo de abrir gaps cambiando el valor de 1.53 a 2.0 ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?
   Se redujo la presencia de gap solitarios en el alineamiento.
####14- Prueba lo mismo pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento

Los gaps presentes en el alineamiento fueron de mayor longitud.


##Parte 3: Diseño de partidores

###Partidores para los genes SRY de *Chlorocebus sabaeus*, *Homo sapiens*, *Pan troglodytes* y *Macaca mullata*

![primers](http://i67.tinypic.com/289bx44.png "")