# nvam (nginx, varnish, apache, mysql)
Para crear un stack de apps basado en Nginx, Varnish, Apache y MySQL

## Introducción.

Este repositorio va a contener la definición de las imágenes que después se van a reutilizar para crear los:
- deploy / statefullset
- servicios 
- cronjobs, etc...

Para replicar el stack en entornos de K8s. 

## Mecanismos. 

Se habilitará primero:

- los dockerfiles para construir las imágenes que después serán reusadas en los objetos de kubernetes, así como los scripts de tests de las imágenes. 
- la definición de los objetos que se tienen que desplegar en el cluster de kubernetes
- la definición de los tests para comprobar los objetos desplegados. 
- información para el sistema de despliegue continuo. 
