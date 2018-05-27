## Footprinting

La definición de footprinting es la etapa de un test de intrusión en la que el atacante recolecta todo tipo de información 
sobre su objetivo. Su fuente de recolección pueden ser variadas, tomándose como referencia aquellas que se encuentran en 
fuentes abiertas como Internet.
Toda la información recogida en esta fase del pentest es necesario filtrarla, puesto que este tipo de investgación nos puede
descubrir acgivos de nuestro objetivo y organziación que más adelante pueden convertirse en vectores de ataque.
Dentro del Footprinting el primer paso que debemos realizar es el objetivo donde vamos a obtener la información y descubrir
los activos.
Así deberíamos realizar las siguientes acciones:
* Realizar visitas a los sitios web de la organización, servicios y aplicaciones con el fin de encontrar errores y saber 
la superficie de información que tiene el objetivo
- Encontrar a través de los motores de búsqueda ficheros que puedan darnos información como es el caso de robots.txt
- Descargarse las páginas web enontradas para descrubir cuestiones que se nos hayan pasado en el primer análisis.
- Una buena fuente de información son los DORKS para consultar a los motoroes de búsqueda. Se trata de vulnerabilidades que 
se pueden encontrar indexadas en Google o en otros buscadores y que pueden ser debilidades del objetivo a analizar.
Herramienta: GHDB Google Hacking DataBase
- El dominio es una parte muy importante a estidiar o los dominios de la organización.
- También es recomendable realizar una visita a archive.org para conocer el histórico de los activos que estamos analizando.
- Una forma interesante de conocer la embergadura de una organización es conocer los dominios y subdominios que posee. Una 
forma podría ser listando las IPs que posee para conocer el número de máquinas que tiene.
- Una parte también muy interesante son los metadatos que podemos encontrar en documentos en Internet de una organización. En 
estos metadatos podemos encontrar todo tipo de información desde nombres de personas, emails, usuarios, dispostivos, ...
- Gracias a losm DNS podemos encontrar mucha información de una organización.
- Analizar los servicios web que está usando una organización, arrojándonos información de tood tipo como puede ser IP, 
subdominios, ... Toda esta información la podemos conseguir con servicios del tipo: netcraft, cuwhois, 123people, iptools, etc.
- Tipo de alojamiento en el que están alojadas las webs o recursos externos de la empresa.
- Conseguir los emails es muy importante, los cuales pueden ser usados para labores de ingenería social, phishing u otro tipo
de técnicas más avanzadas.
- 
