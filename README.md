# **Laboratorio de Git**

## **Objetivos**
***

> Aquí describo la realización de los objetivos


### **1. Crear un repositorio en local**
---

- Abre tu terminal y navega hasta el directorio donde deseas crear el repositorio **+** Crea una carpeta con el nombre del repositorio:

    Aquí se reflejan ambos pasos:

![Creación repositorio](./content/1-1-creacion-repo.png)


- Ingresa a la carpeta que acabas de crear:

![Ingreso con Visual Studio Code](./content/1-2-ingreso_vsc.png)


- Inicializa el repositorio de Git:

![Inicializo repositorio Git](./content/1-3-git-init.png)


- **Extra solución problema con .DS_Store:**



Surgió el problema del fichero *.DS_Store* que no queremos y lo solucionamos con *.gitignore*:


![Problema .DS_Store](./content/1-5-problema-dsstore.png)

![Solución .gitignore](./content/1-6-solucion-gitignore.png)

Comprobamos:

![Git status](./content/1-7-git-status.png)

- Stage y commit del README.md:

Hacemos stage y commit del README.md:

![Stage y commit](./content/1-8-stage-commit.png)

### **2. Subir el repositorio a GitHub**
---

*Previamente hice modificaciones en el formato del README.md*

- Crea un nuevo repositorio en GitHub:

![Creo repositorio GitHub](./content/2-1-creacion-repo-github.png)

- Copia el URL del repositorio que acabas de crear en GitHub:

![Copio URL de GitHub](./content/2-2-copia-url-github.png)

- Conecta tu repositorio local con el repositorio en GitHub:

![Conecto local con Github](./content/2-3-conexion-local-github.png)

- Verifica que la conexión se haya establecido correctamente:

![Verifico conexión correcta](./content/2-4-verificacion.png)

### **3. Hacer un commit y un push**
---

- Crear un archivo en la carpeta del repositorio:

![Creación archivo carpeta repo](./content/3-1-creacion-archivo.png)

- Añade el archivo al staging:

![Staging](./content/3-3-commit.png)

- Crea un commit con un mensaje descriptivo:

![Creo commit](./content/3-3-commit.png)

- Sube los cambios al repositorio en GitHub:

![Subo cambios GitHub](./content/3-4-subo-github-1.png)


![Cambio subido](./content/3-4-subo-github-2.png)

*Hago más modificaciones de formato en README.md*

### **4. Crear una rama**
***

- Crea una rama nueva llamada "development":

![Creo rama development](./content/4-1-creando-rama.png)

- Cambia a la nueva rama:

![Cambio a rama nuevat](./content/4-2-cambio-rama-development.png)

- Realiza algunos cambios en el archivo que creaste:

![Archivo original](./content/4-3-realizo-cambios-archivo-1.png)

![Archivo cambiado](./content/4-4-realizo-cambios-archivo-2.png)

- Añade y haz un commit con los cambios en la rama "development":

![Staging y commit cambios rama](./content/4-5-add-commit-cambios-rama.png)

- Sube los cambios a GitHub:

![Subiendo cambios](./content/4-6-subo-cambios.png)
![Subiendo cambios 2](./content/4-7-subo-cambios2.png)


## **5. Hacer un merge**
***

*La rama principal de nuestro repositorio puede ser "main" o "master" según la hayamos nombrado*

- Vuelve a la rama "main":

En nuestro caso, "master"

![Vuelve rama master](./content/5-1-volviendo-rama-master.png)

- Haz un merge de la rama "development" a la rama "main":

En nuestro caso, "master"

![Merge](./content/5-2-merge.png)

Según hemos investigado, en este caso, introdujimos innecesariamente un mensaje commit cuando el merge era fast-forward, lo que llevó al mensaje que nos mandó Git.

- Si no hay conflictos, los cambios realizados en la rama "development" se incorporarán a la rama "main" **+** - Haz un push de los cambios al repositorio en GitHub

Los cambios se incorporan sin conflictos

![Cambios incorporados 1](./content/5-3-incorporo-cambios.png)

![Cambios incorporados 2](./content/5-4-incorporo-cambios-2.png)

![Cambios incorporados 3](./content/5-5-incorporo-cambios-3.png)

*Realizamos los últimos retoques en el formato del README.md*

> Fin del laboratorio