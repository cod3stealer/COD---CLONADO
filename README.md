# Ejercicio de clase

## modificación de clase

Primero ejecuto el comando git clone -o NuevoNombre link.git

Luego, dentro de la carpeta del nuevo repositorio hago el git remote add origin link.git del 
repositorio creado de manera remota para el repositorio clonado.

Modifico este mismo README.md y por último hago un push de los cambios

## Anotaciones

Al hacer el `git remote add origin link.git` escribí mal el link y para cambiarlo
luego tuve que usar el comando `git remote set-url origin https://github.com/usuario/tu-nuevo-repositorio.git`.

Para comprobar la nueva URL empleé el comando `git remote -v`
