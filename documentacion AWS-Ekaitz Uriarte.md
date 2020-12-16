# Documentación de AWS server

## ¿Qué es y para qué sirve EC2?
#### EC2 es una parte central de la plataforma de cómputo en la nube de Amazon, denominada Amazon Web Services, sirve para que los usuarios puedan alquilar ordenadores virtuales en los cuales pueden ejecutar sus propias aplicaciones.

#### A continuación, se muestra una captura de pantalla de la instancia creada:

![Instancia](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-16%20115147.png)

#### La clave ssh se vincula siguiendo las siguientes instrucciones:

![Instancia](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-16%20115413.png)

#### Todo esto lo ejecutamos desde el git:

1. Hacer Git bash en la carpeta donde está la clave.
2. Garantizar los privilegios haciendo chmod 400 sobre la clave.
3. Conectarse a la instancia con el DNS público.

#### Instalación de los módulos apache2, mysql, php y ftp en la instancia. Capturas:

1. Apache

![Apache](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-16%20110542.png)

2. Mysql

![mysql](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-14%20111947.png)
3. FTP

![FTP](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-14%20111705.png)
4. PHP

![PHP](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-16%20121854.png)

## ¿Qué es y para qué sirve una IP Elástica?

#### Una dirección IP estática es una dirección asignada de forma permanente a un dispositivo. Esta dirección nunca se modifica, aunque sí es posible reasignar una nueva. Se suelen usar porque suelen ayudar a tener una mayor velocidad, con una conexión más estable y proporciona un mayor control sobre ella.

#### Asociación de IP elástica en AWS:

1. Entramos a Red y Seguridad.
2. Le damos a asignar la dirección IP elástica.
3. Dejamos los valores predeterminados.
4. Le damos a Acciones> Asociar la dirección IP elástica.
5. Cuando pinchamos en los campos ya nos sale nuestra instancia y la IP a asignar.

![IP_ELASTICA](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/ipelastica.png)

6. Pantallazo del proceso culminado:

![IP_ELASTICA2](https://raw.githubusercontent.com/EkaitzUriarte/imagenesMarkdown/master/Captura%20de%20pantalla%202020-12-16%20122824.png)


