
RocketGatitOS-Sexyness
============

Aqui yacen los paquetes de logos y wallpapers!


¿Cómo clono este repo?
----------------------
1. `git git@github.com:piratas-ar/RocketGatitos-sexyness.git`
1. `cd RocketGatitos-sexyness`


Descripción de ficheros y directorios:
-----------------

Nombre | Descripción
-------|-----------


¿Como agrego un nuevo paquete para trabajar?
--------------------------------------------

Vamos a tener en cuenta que lo estas haciendo desde RocketGatitos o desde Fedora, voy a ejemplificar con _generic-logos_

1. dnf download generic-logos
1. mkdir generic-logos
1. mv generic-logos-17.0.0-8.fc24.noarch.rpm generic-logos
1. cd generic-logos
1. rpm2cpio generic-logos-17.0.0-8.fc24.noarch.rpm | cpio -idmv
1. rm generic-logos-17.0.0-8.fc24.noarch.rpm

Con esto descargamos el paquete a trabajar y lo desempaquetamos, ahora vamos
con lo entretenido :D



