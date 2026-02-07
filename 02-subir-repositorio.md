# COMO INICIALIZAR Y SUBIR MI REPOSITORIO A **GITHUB**.
En esta segunda parte vermos como inicializar un proyecto con git y veremos como se sube este a un repositorio remoto como github. Para esto conoceremos algunos comandos, uno de ellos es git init, git push y git pull

## IMPLEMENTACION.
### 1. Inicializacion de un proyecto.

- Primero crearemos un proyecto cualquiera, el de su preferencia.
- Luego pasaremos a abrir la consola, git bash, navegamos hasta la ubicacion de nuestro proyecto.
- Una vez que nos encontramos en la ubicacion de la carpeta de nuestro proyecto, ejecutamos el siguente comando `git init`, esto automaticamente creara un archivo oculto [.git]. Esto nos indica que nuestro proyecto ya fue inicializado corectamente.
- Una vez inicializado el proyecto podremos guardar todos nuestros cambios y codear con total tranquilidad, ya que git llevara un control de versiones de tu codigo constantemente.
### 2. Mi primer **commit**
- Para continuar y poder subir nuestros cambios a nuestro repositorio remoto, tendremos que guardar nuestros cambios con un `commit -m "Mi primer commit"`
- Pero para llegaer a esto tendremos que hacer algunos pasos previos.
- Primer paso, despues de terminar de hacer la ultima modificacion a nuestron codigo, lo que haremos es dirigirnos a la consola, nos ubicamos en la carpeta de nuestro proyecto, hacemos un git status para verificar cuales son los cambios que no agregamos.
- Luego de esa verificacion, procederemos a hacer un git add . para que todos los cambios que hicimos se agregen a nuestro repositorio local.
- Seguido de este paso ahi recien procederemos a realizar nuestro primer commit con el comando `git commit -m "Mi primer commit"`.

### 3. **Push** a nuestro proyecto
- Una vez hecho el commit ya podemos hacer el respectivo push a nuestro repositorio pero debemos seguir los siguientes paso:
    - Paso 1: Viculamos el repositorio local con el remoto.
     ```text
    git remote add origin <URL_DEL_REPOSITORIO>
    ```
    - Paso 2: Hacemos el push a nuestra rama raiz o mejor conocida como master o main.
     ```text
    git push origin <nombre_de_tu_rama>
    ```