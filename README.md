# Inicial
Archivos iniciales para un proyecto web
### Autor
by @dered170
### Lista de mixins incluidos
  * absolute-center
  * absolute-center-bottom
  * absolute-center-top
  * activate-Selection-p
  * animation
  * background-clip
  * background-gradient
  * background-horizontal
  * background-radial
  * background-size
  * border-bottom-radius
  * border-left-radius
  * border-radius
  * border-radius-separate
  * border-right-radius
  * border-top-radius
  * box-shadow
  * box-shadow-inset
  * box-sizing
  * BoxShadowMaterial
  * clearfix / clearfix2
  * columns
  * empty
  * font-face
  * grayscale / quit-grayscale
  * keyframes
  * noSelection-g
  * noSelection-p
  * opacity
  * prefix
  * resize
  * rotate
  * scale
  * selection-g
  * selection-p
  * skew 
  * sombra-fancy
  * text-shadow
  * text-truncate
  * transition
  * translate
  * translate3d

### Configuración
  1. configura la sección de variables.scss
    * Tipografía
      * Families
      * Size
      * Weights
      * Color & Theming
      * Colores brand
      * Color/background botones
      * Colores mensajes de alerta
    * Customización de elementos
      * input
      * links
    * Logos de la marca
      * STANDARD
      * WHITE
      * BLACK
    * Colores sociales
      * Facebook
      * Flickr
      * Foursquare
      * Google+
      * Instagram
      * Linkedin
      * Pinterest
      * Skype
      * Soundcloud
      * Spotify
      * Tumblr
      * Twitter
      * Vimeo pallete
        * ...
      * WhatsApp
      * Youtube
  2. Generar css
    ##### Instalar sass
     
      [sass install](http://sass-lang.com/install)

	Adicionalmente puedes leer la documentación.
     
    #####  Abrir la terminal  y navegar hacia el directorio dónde se desea compilar el archivo sass
    
      *  Compilar archivos ".scss" a ".css"

      ```
        sass --watch sass:css --style expanded
      ```
      
      		Las líneas anteriores compilan los archivos ".scss" a ".css", que son los archivos que entiende el      navegador
      
  3. Incluir archivos css de normalizacion y animacion
  
  	  *	incluir normalize.css

		 ```
  		 <link rel="stylesheet" href="css/normalize.css">
  		 ```
  		  
  		 Ver [Normalize en github](https://github.com/necolas/normalize.css) para obtener la version más actualizada

  	  *	Incluir base.css
		   ```
  		   <link rel="stylesheet" href="css/base.css">
  		   ```
  		   
  		   Incluyendo estos archivos ya puedes hacer uso de los mixins y variables de la siguiente manera
  		   
  		   *	mixins
  		   
  		   	```sass
  		   	body{
  		   		background: blue;
  		   		@include nombreMixin (parametros);
  		   		...
  		   	}
	  		```
	  		
	  	   *	variables
	  	   
	  	   	```sass
  		   	body{
  		   		background : $bg-fondo;
  		   		...
  		   	}
	  		```
	
  	  *	Incluir animate.css
  		
  		   ```
  		   <link rel="stylesheet" href="css/animate.css">
  		   ```
		 Ver [animate en github](https://github.com/daneden/animate.css) para obtener la version más actualizada
