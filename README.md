# RA5.2-Terraform-Ansible

## Objetivo Principal
El objetivo principal de esta tarea es automatizar la configuración de un servidor web Apache en una máquina virtual Ubuntu 24.04, incluyendo la creación y despliegue de un archivo ``index.html``personalizado, y verificar su accesibilidad mediante ``curl``.

## Introducción
En esta sección, profundizaremos en la automatización de la configuración de una máquina virtual Ubuntu 24.04 en VirtualBox utilizando Ansible. Partiendo de una VM ya aprovisionada, el objetivo es demostrar cómo Ansible puede ser empleado para gestionar la instalación y configuración de servicios, específicamente el servidor web Apache, así como para desplegar y actualizar su contenido web.

## Conclusión
La tarea de configuración de una máquina virtual Ubuntu 24.04 en Virtualbox mediante Ansible ha sido exitosamente completada. Hemos demostrado cómo Ansible, una herramienta de Infraestructura como Código (IaC), permite automatizar de manera eficiente no solo la instalación de un servidor web Apache, sino también el despliegue de contenido HTML personalizado y estilizado. La capacidad de Ansible para gestionar el ciclo de vida de los servicios, como el reinicio de Apache tras la actualización del index.html, asegura que los cambios se apliquen de forma inmediata y consistente. La validación mediante curl confirma que la automatización ha sido efectiva, resultando en una página web accesible con el contenido deseado. Este proceso subraya el valor de Ansible para crear entornos reproducibles y simplificar la gestión de la infraestructura.