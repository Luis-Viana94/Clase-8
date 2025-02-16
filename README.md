![GitHub](https://img.shields.io/github/license/taller-R/clase_8) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/taller-R/clase_8/issues) ![](https://img.shields.io/github/followers/taller-R?style=social)

<img src="https://avatars0.githubusercontent.com/u/69440432?s=400&u=96b3e58c713578b563d5c3d3c259f34965ac8e33&v=4" align="right" width=120 height=120 alt="" />

# INSTRUCCIONES


## 1. Descargar la clase

Para descargar las clases debes seguir los siguientes pasos:

```{r}
# 1. Establecer el directorio de trabajo en el que quieres descargar la carpeta
setwd("~/Downloads")

# 2. Descargar el repositorio
download.file(url = "https://github.com/taller-R/clase_8/archive/master.zip", 
              destfile = "clase_8.zip")

# 3. Descomprimir las carpeta
unzip(zipfile = "clase_8.zip")

# 4. Cambiar nuevamente el directorio de trabajo
setwd("~/Downloads/clase_8-master")

# 5. Inspeccionar archivos en el directorio 
list.files()
```
O puede seguir [estas](https://eduard-martinez.github.io/blog/github/clonar_github.html) instrucciones para crear una versión de control de Git en Rstudio que contenga este repositorio. En este [otro](https://www.dropbox.com/sh/bc76kg2h0xcid70/AAA86g9eP4l8ayr6KYEpvxI2a?dl=0) vídeo usted encuentra una explicación de como trabajar en un repositorio de GitHub. 



## 2. Leer las instrucciones iniciales

Después de descargar o clonar el repositorio de la clase, usted debe abrir el archivo **Intro-clase-8.html** que se encuentra dentro de la carpeta del repositorio. Siga atentamente las instrucciones.



## 3. Script de la clase

Ahora puedes ir a la carpeta **codes** y abrir el script **Clase 8.R** para replicar la clase.

![](help/graphs/run_class.gif)

## 4. Notas
* Los vídeos de la clase se encuentran [aquí](https://www.dropbox.com/sh/3c8wdqch9so26un/AAD_1m4SONV3yPoEojYD1Cjaa?dl=0). Nota: Dropbox no deja reproducir los vídeos más de 1 hora en linea, debe descargarlos para que pueda verlos completos.

* Por favor hacer todas las correcciones ortográficas a este y los demás archivos **.Rmd** del repositorio.
