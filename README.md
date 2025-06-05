# DesarrolloGIT
# GIT y Versionado de Codigo

## Introduccion

Es una herramienta basica para el desarrollo de software

- **Linea base** es el estado de un proyecto que es aprobado por todo el equipo, es el codigo que no debemos de tocar libremente.

El control de versiones es un controlador que no permite ver y utilizar las diferentes versiones del codigo fuente.

<u>Tipos de Versionadores</u>:

- Local = Manual
  
- Centralizado = SVN
  
- Distribuido = Git (Creada por linus torbal)
  

## Ventajas

- Historial Completo: permite ver todos los cambios con sus mensajes, fechas y autores.
  
- Revertir cambios: si algo sale mal, se puede volver a una version anterior facilmente.
  
- Trabajo colaborativo: varias personas pueden trabajar al mismo tiempo sin interferir.
  
- Ramas de desarrollo: se pueden probar nuevas idesa sin romper lo que ya funciona, es un espacio de trabajo con un nombre definido para poder probar dichas ideas.
  
- Auditoria y trazabilidad: util para equipos grandes y en entornos donde se exige trazabilidad.
  

## Tipos de Archivos

Git permite ingresar archivos de tipo Texto plano(codigo fuente y puedo identificar donde se realizo el cambio) y Binario(pdf,imagen,etc, y no puedo identificar donde se realizaron cambios).

## Comandos basicos de GIT

- git init = nos crea un subdirectorio(.git) dentro del Repositorio, a su vez nos crea una rama(main o master)
  
- git status = va a ir tomando instantaneas para poder comparar el estado actual con algun estado anterior, para saber el estado en el que estan los archivos.
  
  ![](file:///C:/Users/bonzo/AppData/Roaming/marktext/images/2025-05-26-14-54-54-image.png?msec=1749158715063)
  
- git add = paso previo al commit
  
- git commit = se encarga de tomar usuario, fecha y hora y un mensaje para subir nuestro archivo al main.
  
- git log = podemos ver las diferentes modificaciones que se crearon por el usuario, el horario y dia en que lo hizo y el mensaje que dejo.
  
- Repositorio remoto = repositorio en la nube que permite crear un proyecto remoto que nos permite subir nuestro repositorio, con sus ramas y commits.
  
  > Podemos interactuar con un repositorio de git remoto con https o con ssh.
  
- git remote add = nos permite publicar nuestra copia actual de nuestro commit actual a un repositorio remoto
  
- git push = nos permite subir la rama de mi pc a la rama de la nube (las ramas de la nube tiene el identificador "Origin").
  
- git clone = vamos a bajarnos el repositorio mediante la url del repositorio, es una copia del repositorio subido.
  
- git pull = nos sirve para descargar el estado actual del proyecto del repositorio remoto a mi maquina.
  
- git checkout = lo utlizamos para cambiar de una rama a otra.
  
- git branch = lo utilizamos para crear una nueva rama con su respectivo nombre.
  
- git fetch = baja toda la info que tiene el reositorio remoto a nuestra maquina, toda la info que no tenemos descargada.
  
- El git ignore = nos permite seleccionar los archivos que no van a poder ser trackeados, ya sea por seguridad o otros motivos. Permaneces "Untracked".
  

> Podemos encontrar detalladamente la descripcion de cada comando de git en el libro "git Pro", tiene el nombre el codigo detallado, con las respuestas que da el sistemas a las mismas.
