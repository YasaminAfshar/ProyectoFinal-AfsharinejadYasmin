<h1 align="center">NEW HAIR RECOVERY!</h1>
<p align="center">
<img alt="Sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white" width="80px" height="40px"/> <img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" width="80px" height="40px"/> <img alt="npm" src="https://img.shields.io/badge/-NPM-CB3837?style=flat-square&logo=npm&logoColor=white" width="80px" height="40px"/> <img alt="html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"  width="80px" height="40px"/> <img alt="Nodejs" src="https://img.shields.io/badge/-Nodejs-43853d?style=flat-square&logo=Node.js&logoColor=white" width="80px" height="40px"/>
</p>

## Descripción del proyecto
Este proyecto fue creado como proyecto final para el curso  de **Desarrollo Web** que estuve realizando en la plataforma **CoderHouse**, primera parte de la carrera de **Desarrollo Full Stack**. Para conocer más sobre el curso puede ingresar en el siguiente link: [Carrera Desarrollo Full Stack](http://https://www.coderhouse.com/online/carrera-online-desarrollo-fullstack "Carrera Desarrollo Full Stack").

Los requisitos de este proyecto final fueron:
1. Se debe entregar la versión final de tu sitio cargada al servidor con acceso desde la web, aplicando cada una de las características vistas en el transcurso del curso: **HTML**, **CSS**, aplicación de **framework**, **SEO** y **SASS**.
2. Subida al servidor: Utilizar **WebHost000** o cualquier servicio de hosting para poner el sitio web online.

### Objetivos del proyecto

El objetivo del proyecto a nivel público es poder informar a los usuarios interesados en realizarse el tratamiento capilar sobre las diferentes opciones, de acuerdo a su grado de alopecia. 

El relación al backend, el objetivo es poder demostrar lo aprendido en la clase con respecto a entender y saber usar los dos lenguajes conocidos y todas las herramientas que ayudan a maquetar la página. 


## Herramientas utilizadas para el desarrollo web
- Visual Studio Code
- HTML 5
- CSS 3
- [Bootstrap v5.2](https://getbootstrap.com/ "Bootstrap v5.2") como framework
- [Animate css](https://animate.style/ "Animate css")
- SASS
- Node.Js
- Flexbox y Grid
- Icons/[Font Awesome](https://fontawesome.com/ "Font Awesome")
- [Google Font](https://fonts.google.com/ "Google Font")
- [Convertidor de colores a código de Hex, RGB y HSL ](https://htmlcolorcodes.com/es/ "Convertidor de colores a código de Hex, RGB y HSL ")
- [Generador de gradientes](https://cssgradient.io/ "Generador de gradientes")
- YouTube para los videos y google para las imágenes.
- [Canva](https://www.canva.com/ "Canva para la creación del logo y portada") para la creación del logo y portada

## Arquitectura del proyecto
Se crearon 6 páginas individuales, cada una con un contenido diferente, por lo tanto el proyecto consta de:

- **6 HTML**: La estructura básica está conformada por un HEAD y un BODY, dentro de esta última contiene nav, header, main y footer como etiquetas semánticas. Todas las páginas contienen el mismo navbar, footer y el boton de whatsapp adaptados a las diferentes resoluciones. 
	- *index.html* : es la página de inicio, el cual contiene una breve descripción sobre la empresa, que tratamientos se ofrecen, una galeria de fotos con ejemplos de casos exitosos y un formulario de contacto. 
	- *tratamiento-mesoterapia.html* : es la página que contiene toda la información relacionada con el tratamiento de mesoterapia capilar. Se incorporó animaciones, iframes como videos e imágenes. 
	- *tratamiento-prp.html* : es la página que contiene toda la información relacionada con el tratamiento de plasma rico en plaquetas (PRP). Se incorporó animaciones, iframes como videos e imágenes. 
	- *microimplante-capilar.html* : es la página que contiene toda la información relacionada con el Microimplante capilar. Se incorporó animaciones, iframes como videos e imágenes. 
	- *sedes.html* : se describe en detalle la dirección y los medios de contacto de las distintas sedes. Se incorporó animaciones e iframes como maps (obtenidos del google maps).
	- *error-404.html* : es una página creada como modelo de ejemplo para indicar que la página buscada no puede ser encontrada. Contiene imágenes, texto y animación para hacerlo más dinámico. 
- **CSS y SASS**: para realizar la maquetación y diseño de la página se utilizó el preprocesador de css conocido como SASS que nos permite escribir pseudocódigo CSS, generando diferentes archivos **.scss** (uno principal donde se importaron los partials creados) en los cuales se incluyeron mixins, maps, bucles y variables. A partir de estos archivos **.scss**  se creo un solo archivo **.css** de código más limpio, sencillo de mantener y editar. Utilizando el método de anidación se logro crear un archivo **main.css** prolijo. 

Todas las páginas fueron creadas para que sean Responsive, adaptables a todas las resoluciones ya sea mobile, tablet o desktop. Para lograrlo, se siguió la idea del **"Mobile first"** utilizando los medias queries; teniendo en cuenta los breakpoint conocidos: 280 a 480px para MOBILE, 600 a 1024px para TABLET y 1024px en adelante para DESKTOP. 

## Links del proyecto

==> [Deployment o Pages de Github](https://yasaminafshar.github.io/ProyectoFinal-AfsharinejadYasmin/ "Deployment o Pages de Github")

