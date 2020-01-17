# LOS ARCHIVOS HOST Y NSSWITCH.CONF

- Para esta tarea he utilizado una máquina de Kali Linux (Debian)
- Antes de todo vamos a definir qué son y para que se utilizan estos comandos.


# HOSTS
- El archivo "hosts" es un archivo de un sistema operativo que almacena una lista con los nombres e IPs de los equipos de una máquina local, y este utiliza el sitema de nombres planos.

Aqui podemos un ejemplo de archivo host de Kali Linux, ejecutado con el terminal y pudiendonver una configuración normal con solo 2 usuarios y la máquina.

[CapturaHosts.PNG](./CapturaHosts.PNG)

Y aquí podeis ver que ejecutando el comando ping y el nombre del usuario, nos devuelve en las respuestas la IP de este usuario, ya que esta almacenado en el archivo "hosts", si modificaramos el archivo hosts y cambiaramos la IP de ese usuario, nos devolvería esa IP que hemos cambiado.

[Capturaping.PNG]8./Capturaping.PNG)
