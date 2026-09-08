Crear un proyecto desde cero:

```bash
cd ruta/de/la/carpeta
git init
```

Clonar un repositorio:

```bash
git clone https://github.com/usuario/repositorio.git
```

Revisar cambios:

```bash
git status
```


Agregar archivos al área de preparación (staging):

```bash
git add .
```
(O reemplaza el punto por el nombre de un archivo especifico.)

Enlazar con repositorio remoto:

```bash
git remote add origin https://github.com/usuario/repositorio.git
```
^Este paso se hace tambien al crear el repositorio en GitHub.

Subir cambios:
```bash
git push -u origin main
```
-u bandera abreviada de --set-upstream vincula la rama local con la rama remota, solo se usa la primera vez que se usa una rama nueva.
Despues basta con usar:
```bash
git push
```
Descargar cambios recientes:
```bash
git pull
```


