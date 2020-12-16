# Documentación DNS

## ¿Qué es y para qué sirve el DNS?

#### El sistema de nombres de dominio (Domain Name System), es un sistema de nomenclatura que traduce nombres entendibles para las personas en identificadores binarios asociados a los equipos conectados en red. Utiliza una base de datos, que almacena información asociada a nombres de dominio, puesto que es encargado de traducir direcciones IP a nombres de dominio, y viceversa. Ejemplo: www.google.es a 233.12.123.121 y al revés.

## Tipos de registros DNS más utilizados:

* _A_ =Dirección (address). Este registro se usa para traducir nombres de servidores de alojamiento a direcciones IPv4.
* _AAAA_=Dirección (address). Este registro se usa en IPv6 para traducir nombres de hosts a direcciones IPv6.
* _CNAME_ = Nombre canónico (canonical Name). Se usa para crear nombres de servidores de alojamiento adicionales, o alias, para los servidores de alojamiento de un dominio. Es usado cuando se están corriendo múltiples servicios (como FTP y servidor web) en un servidor con una sola dirección IP. Cada servicio tiene su propia entrada de DNS (como ftp.ejemplo.com. y www.ejemplo.com.). Esto también es usado cuando corres múltiples servidores HTTP, con diferentes nombres, sobre el mismo host. Se escribe primero el alias y luego el nombre real. Ej. Ejemplo1 IN CNAME ejemplo2.
* _NS_ = Servidor de nombres (name server). Define la asociación que existe entre un nombre de dominio y los servidores de nombres que almacenan la información de dicho dominio. Cada dominio se puede asociar a una cantidad cualquiera de servidores de nombres.
* _MX_ = Intercambio de correo (mail exchange). Asocia un nombre de dominio a una lista de servidores de intercambio de correo para ese dominio. Tiene un balanceo de carga y prioridad para el uso de uno o más servicios de correo.
* _PTR_ = Indicador (pointer). También conocido como 'registro inverso', funciona a la inversa del registro A, traduciendo IPs en nombres de dominio. Se usa en el archivo de configuración de la zona DNS inversa.
* _SOA_ = Autoridad de la zona (start of authority). Proporciona información sobre el servidor DNS primario de la zona.
* _SRV_ = Service record (SRV record).
* _ANY_ = Toda la información de todos los tipos que exista. (No es un tipo de registro, sino un tipo de consulta).

## En Guebs

![DNS](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/DNS.png)

* _A_= Traduce la dirección grupo2.zerbitzaria.net a 54.76.1.76
* _MX_= Nombre de dominio para una lista de servidores de correo. En este caso, no tenemos configurado ningún correo.
* _TXT_= Usado para proporcionar la habilidad de asociar un texto arbitrario con un dominio u otro nombre, como información legible por humanos sobre un servidor, una red, un centro de datos u otro tipo de datos sobre cuentas