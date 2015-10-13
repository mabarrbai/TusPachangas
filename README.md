# TusPachangas
Proyecto de la asignatura Infraestructura Virtual en conjunto con la de Desarrollo de Aplicaciones para Internet

##Introducción
La aplicación web que voy a realizar será la de una aplicación que se encargue de gestionar peñas de fútbol de amigos(aunque podría ser ampliada a otros deportes). Entre las funcionalidades que tendrá serán principalmente:
* Registrar peñas.
* Añadir los componentes de la peña.
* Clasificaciones de los componentes, según partidos ganados, goles, etc.
* Formación aleatoria de equipos.
* Avisos particulares a componentes.
* Gestión de campeonatos y disputa de partidos entre peñas.
	
##Infraestructura
Como infraestructura necesaria para la aplicación será necesario:
* **Servidores web** configurados correctamente, entre los que habrá varios de producción, uno de desarrollo, y otro que actuará como balanceador de carga e implementará funcionalidades de seguridad como puede ser un firewall. También sería posibley puede que conveniente, la separación firewall/balanceador. De esta forma, se tendría el firewall como rimera puerta de entrada, y si es admitida la petición,entraría el balanceador de carga a actuar.

* **Servidores de bases de datos** para almacenar todo el contenido de la aplicación web. Tener en cuenta que las bases de datos estarán replicadas continuamente.
	
* **Servidor de correo**, para el envío de notificaciones a peñas y componentes.	
	
##Herramientas
La aplicación será desarrollada con un framework web como **Django**.
Para ir siguiendo el desarrollo de la aplicación web y testeándola, se usará **Travis CI**, con el que se podrá, por ejemplo, probar la aplicación contra distintas configuraciones.
	
##Inscripción en el [certamen de proyectos de la UGR](http://osl.ugr.es/bases-de-los-premios-a-proyectos-libres-de-la-ugr/)
Proyecto inscrito al certamen

	
