# PearOS Installer Spanish
Codigo original: https://github.com/pearOS-archlinux/pearOS-installer

# PearOS Nice C0re Instalador
Este trabajo esta en progreso

# ¿Como ejecutarlo?
abre la terminal y escribe lo siguiente:
```sh
cd system-install
make
```

# ¿Que hace?
Instala el sistema en el disco seleccionado.
Extremadamente importante: utilizará el disco <b>COMPLETO</b>.
Todos los datos en el disco seleccionado serán <b>BORRADOS</b> en el momento que se presione `Continuar`
Se parece mucho al instalador de macOS.
Se agregó el progreso de la instalación :)

# Estado actual
Se realizan varias pruebas a esta aplicación.
En cuanto la version original tenga cambios importantes, yo actualizare este tambien.

# Licencia y derechos de autor:
Este proyecto se publica bajo la licencia PPL v2 y posterior, que se puede encontrar en https://github.com/Pear-Project
Electron Framework se publica bajo la licencia MIT
El script de instalación de arco original se publica bajo la licencia GPL v3.

## Nota:
El script de instalación de arch era un instalador de interfaz de usuario de terminal. El número de líneas de ese código era `1207` líneas. Luego se edito el script para convertirlo en una interfaz de línea de comandos (usa $1 como argumentos), se elimino el cuadro de diálogo gráfico y dividio el código en 2 partes. Ahora tiene ~220 líneas de código :)) <sub><sub><sub><sub><sub><sub>¿es esto lo que quieres que haga, amy?</sub></sub></ sub></sub></sub></sub>

# Colaboradores:
- Alexandru Balan (desarrollando y modificando la mayor parte del código)
- ~~equal (limpieza del código, algunos ajustes de la interfaz de usuario)~~ No comprometí su trabajo, cerré la solicitud de extracción
- zhovner (base de la interfaz de usuario, hecha en electron. Está muy modificada, ni siquiera el 10% del código de zhovner aún está presente, pero *alguien* quiere que lo mencione xd)
- @jorgeluiscarrillo (el script de instalación. Está EXTREMADAMENTE modificado, solo usé la estructura de codificación de esto, pero aún así, *alguien* puede reportar esto como *código robado* :))
- Frank-Dev18 (Correccion de error en el script de instalacion y traduccion al español)
- GitHub (desarrollando el Electron Framework)
- Microsoft (mantenimiento y desarrollo de GitHub)
