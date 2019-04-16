![](imagenes/logo.png)

# Configuración de un servidor SMTP con Squirrelmail

### Introducción
Los sistemas que gestionan el e-mail utilizan tres protocolos principales:

* ***SMTP*** para la tarea específica de enviar el correo (correo saliente)
* ***POP3 o IMAP*** para recibir el correo entrante.



### SMTP

El protocolo para transferencia simple de correo (en inglés Simple Mail Transfer Protocol o SMTP) es un protocolo de red
utilizado para el intercambio de mensajes de correo electrónico entre computadoras u otros dispositivos 
(PDA, teléfonos móviles, impresoras, etc). 

El funcionamiento de este protocolo se da en línea, de manera que opera en los servicios de correo electrónico. 
Sin embargo, este protocolo posee algunas limitaciones en cuanto a la recepción de mensajes en el servidor de destino 
(cola de mensajes recibidos). Como alternativa a esta limitación se asocia normalmente a este protocolo con otros, como 
el POP o IMAP, otorgando a SMTP la tarea específica de enviar correo, y recibirlos empleando los otros protocolos antes 
mencionados (POP O IMAP). 

[Más información sobre SMTP.](https://es.wikipedia.org/wiki/Protocolo_para_transferencia_simple_de_correo)
 
### IMAP

El protocolo IMAP (Internet Message Access Protocol, o Protocolo de acceso a mensajes de internet) no descarga los 
mensajes a tu ordenador: tanto los mensajes como las carpetas que hayamos creado se mantienen en el servidor.
    
    Esto es ventajoso cuando nos conectamos para leer nuestro correo desde diferentes dispositivos, por ejemplo, nuestro
    portátil o el smartphone: sabemos que siempre podremos acceder a todos nuestros mensajes, y que el buzón estará actualizado.
    También es interesante para preservar nuestra privacidad cuando leemos nuestro correo desde un ordenador de uso público 
    o compartido, ya que no almacena información en la máquina local.

El protocolo IMAP es el más aconsejable cuando accedemos a nuestros correos desde varios dispositivos, o en movilidad.
Como precaución, hemos de borrar periódicamente el contenido de nuestra cuenta para que no exceda del límite de espacio 
concedido. El inconveniente de este protocolo es que siempre hemos de disponer de conexión a internet, incluso para 
acceder y trabajar con los mensajes antiguos.

### POP3

El protocolo POP3 (Postal Office Protocol, o protocolo de oficina postal versión 3) descarga los mensajes de correo en 
nuestro ordenador (u otro dispositivo), donde quedan almacenados y organizados en las carpetas que hayamos creado. 
Una vez que se han bajado del servidor, los correos sólo serán accesibles desde la máquina a la que lo hayamos bajado, 
ya que por defecto, al descargarse los mensajes, éstos quedan eliminados del servidor.

Es ideal para conectarse siempre desde un mismo ordenador, y además ofrece la ventaja de poder acceder a nuestros mensajes 
antiguos (ya descargados) sin necesidad de tener conexión a internet.

    La elección entre IMAP o POP3, una vez conocidas las ventajas e inconvenientes de cada protocolo, se deja a elección del 
    usuario. Una solución usual es utilizar el POP3 en nuestro ordenador principal del trabajo, o en nuestro ordenador 
    personal de casa y descargar en ellos los correos para gestionar mejor su almacenamiento. En movilidad, o para consultar 
    el correo desde otros ordenadores, podemos usar el IMAP.

### Instalación y configuración


