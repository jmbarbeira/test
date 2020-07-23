# Utilizacion de Git

Se desccriben los pasos para usar git en un nuevo proyecto

## Comenzando 🚀

_Listado de comandos que utilizaremos con GIT/GitHub_

 **Git status** Inicializamos un proyecto nuevo y se crean la carpeta .Git. Crea un nuevo repositorio.
```
git init
```

 **Git status** Estado del repositorio.
```
git status
```

 **Git add** actualiza o agrega al indice al contenido. "Paso a stage" con todo
```
git add -A
```
 **Git add** actualiza o agrega al indice al contenido. "Paso a stage" parcial
```
git add <archivo>
```

 **Git commit** Asienta los cambios agrupados. "Commit". 
```
git commit -m 'mensaje'
```

 **Git log** Info de los commits realizados. 
```
git log --oneline
```
 **Git reset** quitar cambios en stage. en vez de HEAD podemos poner el identificador del commit y pasa el commit a stage. si hacemos hard reset pasa al inicio 
```
git reset HEAD
```

```
git reset <idcomit>
```

```
git reset --hard <idcomit>
```

 **Git remote** agregar la carpeta de github
```
git remote add origin <url>
```

 **Git push** subur los commits
```
git push -u origin master
```
### Pre-requisitos 📋

_Instalacion de GIT_

```
https://git-scm.com/downloads
```

## Autores ✒️


* **Josu Barbeira** - *Trabajo Inicial* - [josu barbeira](https://github.com/jmbarbeira)


## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

