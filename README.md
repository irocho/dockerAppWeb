<img style="float:left" height="64px"   src="https://irocho.files.wordpress.com/2012/10/rocho-950x264-e1350378609633.png" alt="" />

# Docker para AppWeb
Traballamos no módulo de Aplicacións Web 2º curso de SMR con Docker

### Reiniciar docker:
<code>sudo systemctl restart docker</code>
### Comprobar se vai docker:
<code>sudo systemctl status docker</code>
### Usar un contedor de proba:
<code>sudo docker run hello-world</code>
### Cotilleos
* Mirar os contedores que teño:
<code> sudo docker ps -a</code>
* Mirar os contedores que están activos:
<code>sudo docker ps</code>
### Traballar cun contedor:
* Arrancar un deses contedores:
<code>sudo docker start <i>numeritoID</i> </code>
* Parar un contedor:
<code>sudo docker stop <i>numeritoID</i> </code>
* Borrar un contedor:
<code>sudo docker rm -f <i>numeritoID</i> </code>
* Información en tempo real dun contedor:
<code>sudo docker logs -f <i>numeritoID</i> </code>
* Averiguar IP
<code>sudo docker container inspect moodle | grep IPAddress</code>

[Consulta aquí o que imos traballando de docker en i-rochiño](https://irocho.wordpress.com/tag/docker/)

## Un chisco avanzado:

<code>sudo apt-get install docker-compose</code>

<code>sudo docker-compose up -d</code>
