# CONFIGURACION INICIAL **GIT**.

Despues de la instalacion de git tendras que realizar algunas configuraciones para personalizar tu entorno de desarrollo, una vez configuradas estas se quedaran guardadas en tu comutadora. Tambien podras actualizarlas si lo requieres.

## PRIMERA CONFIGURACION DE GIT
### 1. Configuraremos en usuario y email

Para la primera vez usaremos el comando `--global` pero solo la primera vez.
```text
    $ git config --global user.name "jhon uzumaki"
    $ git config --global user.email "uzumaki@example.com"
```
Si desamos actualizar o cambiar esta informacion solo bastara con escribir lo mismo pero sin el comando `--global`.
```text
    $ git config user.name "jhon uzumaki"
    $ git config user.email "uzumaki@example.com"
```
Si deseamos verificarlo podemos ejecutar el siguiente comando:
```text
    $ git config --list
    user.name=jhon uzumaki
    user.email=uzumaki@example.com
    color.status=auto
    color.branch=auto
    color.interactive=auto
    color.diff=auto
    ...
```