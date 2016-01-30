# GitHub

¿Como trabajar con un repositorio de GitHub desde Linux?

- Creamos un nuevo repositorio en nuestra cuenta de GitHub.
- Desde el terminal, clonamos el repositorio en la carpeta deseada.

```sh
     $ git clone [url]
```
- Ingresamos a la carpeta nueva que tiene el mismo nombre del repositorio, despues de colocar los archivos y/o documentos que deseamos que aparesca en nuestra cuenta de GitHub procedemos a reiniciar el repositorio.

```sh
     $ git init
```
- Añadimos todos los archivos modificados (estos aun no se veran en nuestra cuenta de GitHub).
```sh
     $ git add .
```
- Todos los cambios que se hagan en el repositorio requeriran un mensaje
```sh
     $ git commit -m "Mensaje"
```
- Para poder ver los cambios en nuestra cuenta de GitHub, enviamos los archivos al servidor.
```sh
     $ git push origin master
```
PD: Tildes Omitidas.

