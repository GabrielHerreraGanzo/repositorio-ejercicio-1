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

Esta línea fue añadida directamente desde la interfaz web de GitHub.

## Paso 6: Actualizar el repositorio local con los cambios remotos

Actualizar el repositorio con los cambios que acabas de realizar en GitHub.

```code
bae2@jpexposito-VirtualBox:~/Documentos/repositorio-ejercicio-1$ git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Desempaquetando objetos: 100% (3/3), 1005 bytes | 1005.00 KiB/s, listo.
Desde https://github.com/GabrielHerreraGanzo/repositorio-ejercicio-1
 * branch            main       -> FETCH_HEAD
   b54f690..f60b381  main       -> origin/main
Actualizando b54f690..f60b381
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

## Paso 7: Añadir un nuevo cambio en local y subirlo a GitHub

Realiza un último cambio en local añadiendo otra línea al archivo README.md.

Esta línea fue añadida desde la consola local como parte del último paso.

```code
bae2@jpexposito-VirtualBox:~/Documentos/repositorio-ejercicio-1$ git add README.md
git commit -m "Añadir última línea al README desde local"
git push origin main
[main acbdcfc] Añadir última línea al README desde local
 1 file changed, 6 insertions(+)
Username for 'https://github.com': GabrielHerreraGanzo
Password for 'https://GabrielHerreraGanzo@github.com': 
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 475 bytes | 475.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GabrielHerreraGanzo/repositorio-ejercicio-1.git
   a010d4e..acbdcfc  main -> main
```

