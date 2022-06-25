# Analisis del sistema de administracion de un cine

## Que cosas ocurren en un cine?

Podemos ver esto desde varias perspectivas, tales como:

- Un Cliente.
- Un Empleado.
- Un Administrador.

### Cliente

Un cliente va al cine, ve las peliculas disponibles, y si alguna de las peliculas le parece interesante, entonces comprara un boleta para verla.

### Empleado

A un empleado se le asigna diversos roles, por ejemplo, vendedor de boletos, o limpieza del cine.

En el caso de un vendedor, el se encarga de venderle boletos a los clientes que llegen al cine. A la hora de vender boletos, el vendedor necesita saber que peliculas estan disponibles, los asientos que estan disponibles, los precios de entrada, etc.

### Administrador

Un administrador tiene mas responsabilidades, ya que el se encargara de que el cine este funcionando de forma eficiente y correcta, que los empleados esten realizando sus tareas, que las funciones de peliculas tengan los horarios correctos, etc.

Bueno, su nombre lo dice, _administrador_, verdad?

### Resumen de lo que pasa en un cine

Un cliente llega al cine, ve las peliculas disponibles (en la cartelera), y si alguna le parece interesante, el comprara un boleto para verla.

Ya con el boleto en mano, el cliente vera a cual sala del cine ir, y el asiento que se le fue asignado.

Un empleado tiene varios roles, 1) puede ser un vendedor, el cual atiende a los clientes que desean comprar boletos, 2) puede ser del personal de limpieza.

Un administrador, se encarga de que todas las tareas que deban hacerse se hagan de forma correcta y en el tiempo esperado, un administrador es vital para que un cine funcione.

## Que aspectos del cine se quieren controlar en el sistema?

Que funcionalidades llevara un sistema?, hasta que nivel de detalle queremos controlar las cosas?, quienes usaran el sistema?

Todas estas son preguntas que debemos hacernos a la hora de analisar un sistema, ya que es esencial definir los limites de lo que se desea hacer. Bueno, pero quien decide que hacer y no hacer?

Podriamos tomar un enfoque que este _orientado a las necesidades_ de un cine, que cosas queremos controlar? porque controlarlas? Como controlarlas?

## Necesidades de un cine

Como se dijo anteriormente, a la hora de analisar un sistema, debemos poner limites. Para este sistema de cine hemos decidido enfocarnos en las siguientes necesidades administrativas:

- Control de peliculas.
- Control de los empleados.
- Control de las funciones cinematograficas.
- Control de las salas y asientos.
- Control de la venta de boletos.

### Control de peliculas

Llevar el control de las peliculas significa tener la informacion de las peliculas que se encuentran en los almacenes del cine en una base de datos, ademas de proveer una forma de trabajar con esta informacion, por ejemplo, ser capaz de modificar la informacion de las peliculas o agregar nuevas peliculas.

### Control de los empleados

Los empleados del cine seran los que interactuen con el sistema, asi que necesitamos llevar control de los usuario que participaran en el sistema y sus roles dentro del mismo.

### Control de las funciones cinematograficas

Una funcion cinematografica representa a una pelicula que esta disponible para ser vista, y a la cual se le asigna un horario, sala y precio.

El sistema sera capaz de llevar el control de las funciones cinematograficas.

### Control de las salas y asientos

Llevar el control de las salas significa que el sistema llevara el control de todas las salas con las que cuenta el cine. Tambien se llevara el control de los asientos de cada sala.

Hacer esto es necesario porque a cada funcion cinematografica se le asigna una sala, y al vender un boleto, tambien se asignaran asientos.

### Control de la venta de boletos

Al tener funciones cinematograficas, luego necesitamos ser capacez de controlar la venta de boletos de dichas funciones, esto involucra saber las funciones disponibles, asientos disponibles y horarios.
