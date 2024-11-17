# Hola, BIENVENIDOS a mi página web! 👋
Este es el proyecto final de [zoenavasolis@gmail.com](https://github.com/Zoenavsz/Proyecto1-web-L-becalos) del grupo _1-web-L-becalos_ quién orgullosamente es una de las 600 personas de la 1era generación del Course Frontend de Bécalos Tech Challenge 2024

##### Este HTML es una página web sencilla diseñada para una empresa de SUP surf o paddle surf
la cual es una de mis actividades favoritas como lo había compartido en ejercicios de HTML anteriores en este mismo curso.
![Paddle surf](https://png.pngtree.com/png-vector/20220814/ourmid/pngtree-penguin-floating-on-a-sup-board-sup-board-surf-board-vector-png-image_33207220.png)
###### Para este ejercicio imaginemos que la empresa se llama SUP Adventures, cuyo logo se encuentra al inicio de nuestro HTML ¿Por qué serviría esta página web a esta empresa?
1.  Un formulario estructurado y profesional demuestra organización y seriedad optimizando para la empresa el manejo del tiempo y recursos (tablas, instructores, etc.).
2. Mejorar la experiencia del cliente:
Al incluir campos como la fecha de la reserva y el horario, se ofrece flexibilidad para que los usuarios elijan cuándo desean disfrutar de esta actividad.

#### 🚀 Para esto el proyecto se ha desarrollado de la siguiente manera:
#### Fondo y estilo visual
##### Se eligió un fondo en tono azul claro con colores de letras contrastantes 
en una paleta de azules-púrpura acorde a la imagen de marca y el servicio que se ofrece.
#### Formulario de reserva
El formulario es el núcleo de esta página, y cada campo tiene una función específica:

1. **Nombre, Apellidos y Email**: para identificar al cliente y poder enviarle una confirmación.
2. **Fecha de reserva**: usa un calendario para que el usuario elija fácilmente el día que prefiera.
3. **Número de personas**: se asegura que sea al menos 1 para evitar errores.
4. **Horario**: se presenta como opciones únicas usando botones de radio para que el cliente no pueda seleccionar más de un horario.

#### Link en la página
Un link en el que sólo los curiosos podrán encontrar una promoción para hacer su experiencia aún más increíble.

#### Condiciones de servicio
* Se agrega una lista que deja en claro bajo qué condiciones el servicio no se puede prestar. Esto no solo informa, sino que refuerza el compromiso con la seguridad de los clientes. 
* También se incluye un *checkbox* para que los usuarios confirmen que aceptan los términos antes de enviar el formulario.

#### Botón de envío
El botón de "**Reservar** conecta la acción del formulario con `FormSubmit`, un método súper práctico para enviar los datos directamente al correo sin complicaciones de servidores o programación extra que nos enseñó nuestro sensei.
![Paddle surf](https://img.freepik.com/vector-premium/pareja-joven-remando-tablas-sup-ilustracion-vectorial-plana-stand-up-paddle-boarding-sup-surfing-concepto-actividad-playa-verano_103044-1217.jpg)
Para esto se llevó un control de versiones a través de git
* **git init**: Con esto se inicializa git en el proyecto a través de su terminal.
* **Ctrl + S**: Se guardan los cambios en el código HTML antes de hacer un commit.
* **git add .**: "Enfocamos" aquello que queramos capturar para guardar nuestro código en diversas etapas del proyecto.
* **git commit -m".."**:Hacemos la "captura" del progreso en nuestro proyecto en diferentes etapas hasta tener nuestra versión final.

Una vez asegurándose de tener nuestra versión final...
1. **creamos un repositorio en Github para subir nuestro proyecto**
con **git remote add origin ___** agregamos la liga al repositorio, en este caso se ha configurado https://github.com/Zoenavsz/Proyecto1-web-L-becalos.git como **origin**
2. con **git remote -v** verificamos si nos aparece (fetch) y (push)
3. con **git push origin main** subimos a la nube nuestro proyecto, _este se almacenará en **nuestro repositorio** de Github_

Ahora bien, para desplegar nuestro HTML en Github Pages **debemos ir a _Configuración_** 
![Deployment](https://miro.medium.com/v2/resize:fit:828/format:webp/1*NXw6MsuP05WBbxRkl_EsPw.png)
**una vez desde _Pages_** que encontramos en el menú a la izquierda en **_Source_** seleccionamos **_Deploy from a branch_** y en ¨**_Branch_** seleccionamos la **_rama main o master_**. Una vez haciendo **_clic_** en "**Save**" GitHub activará el servicio de GitHub Pages para nuestro repositorio. Esto puede demorar unos segundos, una vez recargando, tendremos la liga **https://zoenavsz.github.io/Proyecto1-web-L-becalos/**