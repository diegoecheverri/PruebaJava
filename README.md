# PruebaJava
Prueba Java Axity

La prueba consta de dos proyectos:

1. Un servicio web tipo rest, que hace uso de un pool de conexiones a apache derby que se encuentra configurado en el servidor de aplicaciones Payara(Glasfish), y los crud estan realizados con jpa(eclipse link), con una clase abstracta(facade) utilizada en la gestion de los mismos.

2. Una aplicacion web realizada en JSP con el framework primefaces que consume el servicio web(Incompleta)

Ambas aplicaciones, estan construidas sobre un proyecto Maven.

Para desplegar el proyecto, es necesario crear el esquema de la base de datos en la version de apache derby que viene incluida en netbeans, sin embargo adjunto la que yo use, y se puede agregar sin problemas a netbeans.

Una vez hecho esto, se debe compilar y ejecutar los servicios web, y posteriormente la aplicacion
