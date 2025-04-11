# event-driven-lab

## Descripción
El taller consiste en desarrollador dos microservicios para tener una arquitecura pub/sub, este está desarrollado con Java, Spring y RabbitMQ, contenerizando cada microservicio y desplegando usando la herramienta docker playground

## Pre-requisitos
* [Maven](https://maven.apache.org/) - Administrador de dependencias
* [Git](https://git-scm.com/) - Sistema de control de versiones
* [Java 21](https://www.java.com/) - Tecnología para el desarrollo de aplicaciones
* [Docker](https://www.docker.com/) - Herramienta de contenedores
* [RabbitMQ](https://www.rabbitmq.com/) - Sistema de broker de mensajes


## Evidencias funcionamiento

1. Luego de desarrollar la aplicación del publicador se realiza el build de esta

![alt text](<img/image (10).png>)

2. Se realiza el push a docker hub

![alt text](<img/image (11).png>)

3. Luego de desarrollar la aplicación del consumidor se realiza el build de esta

![alt text](<img/image (12).png>)

4. Se realiza el push a docker hub

![alt text](<img/image (13).png>)

5. Una vez clonado el repo en la sesion de docker playground se ejecuta el comando `docker-compose up -d`

![alt text](<img/image (14).png>)

6. Se envia un mensaje a traves del productor

![alt text](<img/image (15).png>)

7. Se visualizan los logs del consumidor

![alt text](<img/image (16).png>)

8. Se observa la interfaz de RabbitMQ

![alt text](<img/image (17).png>)

## Autores
Juan Camilo Angel Hernandez