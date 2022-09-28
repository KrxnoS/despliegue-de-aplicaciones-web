1. Crea un repositorio para subir todas las actividades de esta asignatura con el
nombre despliegue-de-aplicaciones-web.



2. Crea una carpeta en tu repositorio llamada “Actividad 1” y dentro crea un archivo
README.md con la solución a los siguientes ejercicios.



3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.

logintoken: gLD29QHKKHwiOYbzxgohdt0VmbPvdaDw


4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP?

Al puerto numero 80

 ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? 

Capa 4 o de aplicación

¿Y los protocolos TCP,UDP, e IP?

En la capa de transporte

5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php

indica que el recurso solicitado ha sido movido temporalmente a la URL dada por las cabeceras Location

6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

ip google : 216.58.215.141	TCP	54	56364 → 443 [FIN, ACK] Seq=2 Ack=74 Win=512 Len=0
