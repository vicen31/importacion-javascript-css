# importacion-javascript-css
Utilidades para importar librerías de JavaScript y sus CSS asociados sin preocuparse de sus dependencias y evitando duplicados accidentales.

La información para importar los diversos archivos se dividen en módulos específicos catalogados por distintas tipologías, como por ejemplo, modulos de librerías de desarrollo generales, de tratamientos de texto, de gestión de tablas, etc...

El objetivo del proyecto es la de crear una recopilación de las principales liberías javascript, de información de sus dependencias necesarias, y la creacción de una API para generar todas las etiquetas <script> que necesitemos en nuestro código mediante una única y descriptiva línea de código, como por ejemplo :
  
  import().addJQuery().addBootStrap().addDataTable().addFullCallendar().addVoca().limpiar();

