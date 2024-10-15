# Repositorio Ejercicio 1

Este repositorio contiene los pasos básicos para trabajar con Git y GitHub.


## Paso 3: Clonar el repositorio en local

Clona el repositorio que acabas de crear a tu máquina local utilizando Git.

En la terminal, ejecuta el siguiente comando (reemplaza la URL por la de tu repositorio):

```code
bae2@jpexposito-VirtualBox:~/Documentos$ git clone https://github.com/GabrielHerreraGanzo/repositorio-ejercicio-1.git
Clonando en 'repositorio-ejercicio-1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo
```

##  Paso 4: Modificar el archivo README.md

 Usa los siguientes comandos:

 ```code
bae2@jpexposito-VirtualBox:~/Documentos/repositorio-ejercicio-1$ git add README.md
bae2@jpexposito-VirtualBox:~/Documentos/repositorio-ejercicio-1$ git commit -m "Añadir título y descripción al README"
[main d87fa6d] Añadir título y descripción al README
 1 file changed, 24 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
bae2@jpexposito-VirtualBox:~/Documentos/repositorio-ejercicio-1$ git push origin main
Username for 'https://github.com': GabrielHerreraGanzo
Password for 'https://GabrielHerreraGanzo@github.com': 
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 681 bytes | 681.00 KiB/s, listo.
Total 3 (delta 0), reusados 0 (delta 0), pack-reusados 0

To https://github.com/GabrielHerreraGanzo/repositorio-ejercicio-1.git
   1d1b5ac..d87fa6d  main -> main
```

## Paso 5: Editar el README.md desde GitHub




