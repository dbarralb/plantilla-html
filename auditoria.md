# Auditoría de zonammorpg.com #

Vamos a auditar la web de http://www.zonammorpg.com/ 

## **Errores encontrados** ##
--------

### **Contraste** ###
En la lista del menú principal hay varios títulos con muy bajo contraste puesto que se muestran sobre un fondo de imagen, además cambiante, siendo completamente ignorados *(creo que en 2 años de visitas a esta página los he usado 3 veces)*.

Así mismo todos los iconos sobre imágenes del contenedor wpb_tabswpb_content_element del banner derecho, usan colores (rosas, rojos y violetas sobresaturados) que tienen demasiado **contraste sobre imágenes oscuras** en negro y pueden resultar bastante molestas a las **personas con deuteranopia**.

    Si se desatura la página con blancos y negros, estas imágenes son demasiado oscuras y en este caso pasa a verse solamente el texto de esas etiquetas.

Lo mismo sucede con los iconos de las redes sociales del header, y las etiquetas de los artículos en el cuerpo central principal de la página. que ya no solo pasan inadvertidos sino que además son links que no contienen texto, con lo que los Screen Readers lo ignoran.

### **Etiquetas Innecesarias** ###
Justo debajo de los artículos DESTACADOS (gp_blog_wrapper_1) hay unas etiquetas que clasifican esos artículos como destacados y que son de Zona mmorpg (la misma página que estamos visitando) Considero que se trata de **informacion irrelevante** ya que los articulos están destacados y además las etiquetas son **casi ilegibles** por no tener apenas **contraste**.

### **Links vacíos** ###
Tanto en los iconos de redes sociales asociadas en el header, como en las flechas de navegación de la galería de imágenes destacadas justo en la parte superior *(lo primero que vemos nada más entrar)* contienen **links sin texto**. Esto supone confusión en la navegación desde teclado o lector de pantalla.

    He realizado la prueba de navegación por la web y al tabular no puedo saber en ningún momento dónde me sitúo si no observo la etiqueta de url que aparece abajo en los laterales del navegador.


### **Formularios** ###
El primer formulario situado a la derecha de clase *searchform* contiene una barra de búsqueda para consultar texto en todo el contenido de la página, pero el botón no contiene ningún *value* asociado. Lo mismo sucede con cinco etiquetas label de formulario en toda la página. Los lectores de pantalla no interpretarían estos elementos correctamente.

### **Textos descriptivos en imágenes** ###
El uso contínuo de imagenes en el banner derecho implica que los apartados NUEVOS JUEGOS, PRÓXIMOS LANZAMIENTOS e incluso el código embebido del servidor de Discord no sean accesibles para un lector de pantallas. Las imágenes **no contienen texto** descriptivo ni junto a ellas ni tiene los **atributos ALT=""** rellenos.

### **Redundancia de Links** ###
Las imágenes del banner derecho vuelven a presentar sobreinformación incluyendo varios links al mismo sitio, contienen redundancia tambien en el etiquetado del título y el texto que nos proporciona el hover.