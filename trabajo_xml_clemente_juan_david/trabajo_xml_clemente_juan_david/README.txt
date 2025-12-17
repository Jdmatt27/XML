El archivo README.txt debe contener: 
1. Contexto elegido 
2. Explicación breve de la estructura del XML 
3. Qué valida el DTD 
4. Qué valida el XSD 
5. Dificultades encontradas durante el desarrollo



1. CONTENIDO ELEGIDO

Hemos elegido la extructura de un colegio con la respectiva distribucion de este mismo:
-Un apartado para las clases
-Un apartado para los profesores (el cual contendra otras etiquetas para añadir datos mas concretos de cada apartado)
-Y un apartado para los alumnos (el cual contendra otras etiquetas para añadir datos mas concretos de cada apartado)


2. EXPLICACION BREVE DE LA ESTRUCTURA XML 

En el archivo XML hemos asignado como etiqueta raiz la etiqueta <instituto>, en la cual se especificara abajo como sera la organizacion de las diferentes etiquetas:

- <cursos> (la cual va a contener las 2 siguientes)

- <curso> (la cual se identificara con un id para diferenciar los diferentes cursos que tenga cada apartado. Va a contener los siguientes apartados)

- <nombre> (esta etiqueta se usara para agregar texto indicando diferentes cosas)

- <profesores> (esta etiqueta contendra las siguientes que se escribiran acontinuacion)

- <profesor> (esta etiqueta determinara el nombre de los profesores que estaran dentro del archivo XML, del cual dependera tambien de un ID para identificar cada profesor)

- <nombre> 

- <edad> (esta etiqueta solo contendra un numero)

- <alumnos> (esta etiqueta servira para poder diferenciar el apartado de los alumnos)

- <alumno> (contendra un ID para poder diferenciar los diferentes alumnos, ademas de que contendra otras dos etiquetas)

- <nombre>

- <edad>






5. DIFICULTADES ENCONTRADAS DURANTE EL DESARROLLO
 
A la hora de organizar todo el archivo XML nos hemos encontrado problemas como el que tendriamos que colocar dentro de cada etiqueta o que tendriamos que poner por debajo de la raiz para que la jerarquia este completamente bien