# CCOO-Galeo Website

Made with Hugo using [Whisper theme](https://themes.gohugo.io/themes/hugo-whisper-theme/)

## Cómo aportar contenido

Primero instala **hugo**:

```sh
sudo apt install hugo
```

Luego inicia el server de desarrollo local:

```sh
hugo server
```

### Crear páginas

Crea una carpeta dentro de `content/info/` con el nombre que quieras, y dentro de ella crea un archivo `index.md` con el contenido que desees.

El archivo deberá empezar con la siguiente información (edita lo que necesites):
```
---
title: 'Título de la página'
date: 2019-02-11T19:27:37+10:00
weight: 2
summary: Información que aparecerá en buscadores etc.
---
```

El orden de la página se determina por el valor de `weight`. Cuanto más alto, más abajo sandrá la página.

Puedes echar un vistazo a las otras páginas para ver cómo se han hecho.

### Publicar cambios

Cuando tengas listos tus cambios, haz un push a la rama `main`, y la página se desplegará automáticamente.