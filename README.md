# GitHub Classroom Plantilla de entrega
**Template tarea para subir subir nuestros trabajos, práticas o exámenes a repositorios de GitHub Classroom**

![imagen](https://github.blog/wp-content/uploads/2019/08/github-classroom-1200-630.png)

## Cómo mandar mi Entrega
Esta es la plantilla de entrega de GitHub Classroom. Te comento los pasos que debes hacer para entregar.
Para elo recibirás el enlace al la entrega de GitHub Classroom

### 1 Una vez reciba mi enlace de entrega
Con mi enlace de entrega, que puede ser de esta forma parecida: https://classroom.github.com/a/DygYDUJS debes proceder así:
- Pincho y acepto la asignación del mismo
- Se te indicará que se está configurando tu repositorio y que puede llevar unos momentos. Se te indicará la fecha de entrega máxima para la cual estará abierto. Debes refrescar la página para ver si todo está listo.
- Una vez hayas refrescado y esté todo listo, te dará la dirección del repositorio donde debes trabajar, por ejemplo: https://github.com/IESLuisVives/prueba-joseluisgs (llevará tu nombre de usuario de GitHub). 
- Clonamos nuestro nuevo repositorio de entrega con git clone url. No lo hagas directamente con GitKraken porque no podrás clonarlo así.
- Una vez clonado en tu disco duro, ya podrás abrirlo con GitKraken si quieres.
- Ya podemos trabajar con él.

### 2 Datos de Alumno/a
Lo primero que debes hacer es completar el fichero alumno.md añadiendo tu nombre y apellidos, así como curso, email y nick de GitHub.

### 3 Trabajando
Puedes trabajar o crear tu proyecto aquí o copiarlo de otro lado. Para ello:
- Cambia y usa siempre la rama develop (git checkout develop), así si te equivocas no habrás ensuciado la main. También puedes crear otra rama siempre que quieras y lo necesites.
- Usa Git todo lo que puedas, ya sabes, add, commit, reset, restore para trabajar y sobre todo en las partes fundamentales por si neceitas regresar a algún commit ya sea por fallo, o copia de seguridad, o lo que necesites.

### 4 Entregando
- Cuando lo tengas todo listo, si tienes alguna rama merega a develop. Finalmente cambia a la rama principal: git checkout main
- Mergea la rama develop a main: git merge develop
- Haz commit en la rama main con el código final de entrega: git commit -m y pon tu nombre y apellido y curso como mensaje.
- Sube los cambios con git push origin main
- Crea una etiqueta v1.0.0 con tu nombre y apellido y curso. git tag -a v1.0 -m "Nombre Apellido 1DAM/2DAM"
- Subimos la etiqueta: git push origin <tag_name>, por ejemplo git push origin v.1.0
- OJO si por lo que sea vas a hacer varias entregas repite los pasos necesarios pero siempre incrementa la versión. Por ejemplo, 1.1, 1.2, 1.3, 1.4...
- Si tienes dudas, pregúnta a tu profesor sobre la entrega.

### 5 Finalizado
- Podrás ver tu entrega en la url asignada. Confirma que tienes todos lso commits y tags que quieras entregar.

¡¡ SUERTE !! 🦾




