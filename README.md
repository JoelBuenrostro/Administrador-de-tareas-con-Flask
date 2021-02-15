# Administrador de tareas

Ejemplo practico de una simple aplicacion de tareas usando el framework Flask y Python.

La aplicacion pueda agregar tareas a una base de datos Sqlite3, marcarlas como completadas y eliminarlas.

Flask es un framework minimalista escrito en Python que permite crear aplicaciones web rápidamente y con un mínimo 
número de líneas de código. 
Está basado en la especificación WSGI de Werkzeug y el motor de templates Jinja2 y tiene una licencia BSD.

SQLite es un sistema de gestión de bases de datos relacional compatible con ACID, contenida en una relativamente 
pequeña biblioteca escrita en C.

Bootstrap es una biblioteca multiplataforma o conjunto de herramientas de código abierto para diseño de sitios y 
aplicaciones web. 
Contiene plantillas de diseño con tipografía, formularios, botones, cuadros, menús de navegación y otros elementos de 
diseño basado en HTML y CSS, así como extensiones de JavaScript adicionales. 
A diferencia de muchos frameworks web, solo se ocupa del desarrollo front-end.

## Capturas de pantalla

Las tareas marcadas como completadas se mostraran con un tono gris, en este estado se puede volver a colocar en color 
normal al presionar el boton de completado por segunda vez.

![Captura 1](/screenshot/Admin-2.png)

Las tareas se pueden borrar en cualquier estado

![Captura 2](/screenshot/Admin-3.png)

Al crear nuevas tareas, se acomodarn en la parte inferior de la lista

![Captura 3](/screenshot/Admin-4.png)

## Modo de operacion

El codigo solo cuenta con tres vistas, una para cada operacion de las tareas, crear completar y borrar

![Flask](/screenshot/flask-python.png)