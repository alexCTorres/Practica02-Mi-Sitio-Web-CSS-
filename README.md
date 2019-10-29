# Practica02-Mi-Sitio-Web-CSS-

 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES

CARRERA: INGENIERIA EN SISTEMAS	ASIGNATURA: HYPERMEDIAL
NRO. PRÁCTICA:	2	TÍTULO PRÁCTICA: Resolución de problemas sobre CSS3
OBJETIVO ALCANZADO:
•	Entender y organizar de una mejor manera los sitios de web en Internet
•	Diseñar adecuadamente elementos gráficos en sitios web en Internet.
•	Crear sitios web aplicando estándares actuales.
ACTIVIDADES DESARROLLADAS

1.	Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)”

   
Agregamos un repositorio con la cuenta ya creada antes en la práctica anterior.

2.	Realizar un commit y push por cada requerimiento de los puntos antes descritos. 


Primero agregamos a nuestro proyecto o subimos al github para luego realiza los commit y push.

 

Commit y Push

 

GitHub

 

3.	Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. 

Index.html
 
Contacto.html

 

4.	Luego, se debe crear el archivo README del repositorio de GitHub. 
5.	ACTIVIDADES.

1-	Se pide realizar el tutorial02 del texto guía New Perspectives HTML5 and CSS3, 7th Edition. El desarrollo del tutorial se debe incluir en el informe de la práctica (detallado). 

Para el desarrollo de este tutorial se procedió a descargar el archivo del tutorial, que siguiendo los pasos del libro vamos formando nuestra pagina web con sus distintos diseños y estilos de CSS3.

Página principal sin cambios:

Después de abrir nuestros documentos y guardarlos como dice en el tutorial, procedemos a abrirlos en un navegador web la página principal home la cual nos muestra la siguiente figura como esta e este momento. 

 

Realizando los cambios:

Luego de abrir la pagina home vamos dando estilos a la página, primero lo vamos a dividir en 3 columnas para un diseño más llamativo, para ello llamamos al layout.css donde tiene estos tipos de diseño lo realizamos así:

 

 

Resultado: 
 

Ahora vamos a darle colores a los distintos campos y h1 del proyecto para ello vamos a styles.css donde están los estilos de cada uno y le agregamos:

  


Resultado: 
 

El siguiente paso es poner diferentes estilos de letras, tamaños, colores a las diferentes etiquetas, todo esto en el archivo style.css

  

Resultado: 
 

Luego entramos a las otras paginas del tutorial que son bike, swim, run, en donde realiamos lo mismo que en home, ponemos los links de los estilos y layouts para crear estilos.

 

Ahora modificamos colores de las etiquetas:

   
   

Resultado: 

 

Ponemos números a las listas de las paginas secundarias las cuales cuenta con algunas listas numeras en distintos tipos como numéricos, romanos, decimales, etc.

  

Resultado: 
 

Ponemos márgenes a los distintos componentes.
  

Resultado: 
 

Vamos a poner imágenes realizando pseudo código a las clases, la lista de running, bike y swim en cada una de las listas así:

  

Resultado: 


 

Ahora vamos a utilizar el pseudo-clases a hipertextos para que cuando aplastemos una opción del menú principal se resalte con otro color la opción requerida.

  

Resultado: 

 

El siguiente paso para que nuestra pagina quede mas vistosa, vamos a poner comillas en los bloques del aside para que cada bloque este separado por comillas entre si, esto lo realizamos con open-quote y close-quote: 

  

Resultado: 

 

PAGINA ABADA CON TODOS SUS CAMBIOS.


Index.html
 

Running.html, Bike.html y swim.html con el mismo formato:

 


 
2-	Se pide realiza un sitio web que tenga al menos una página principal (index.html) y cinco páginas que tengan navegabilidad entre todas las páginas html. Además, se pide utilizar estilos CSS con la finalidad de obtener un diseño como el que se muestra a continuación, para cada una de las páginas html. El tema elegido por cada estudiante deberá ser distinto al realizado en la práctica 01 – Creación de un sitio web usando HTML5. 
    



3-	Se recomienda utilizar, en al menos una página HTML, un diseño a dos columnas con cabecera y pie de página, como el que se muestra en la Figura 2. Así, como también se recomienda utilizar, en al menos una página HTML, un diseño a tres columnas con cabecera y pie de página como se muestra en la Figura 3. 

   

Diseño a dos columnas:

Este diseño lo realizamos en la página de contactos.html

 






Diseño a tres columnas:

Este diseño lo realizamos en todas las otras paginas secundarias de index, entre ellas están reptiles.html, felinos.html, acuario.html, aves.html, alimentación.html, ahora veremos la página de acuaticos.html para comprobar este paso.

 

4-	De igual manera, se pide que se creé al menos tres archivos CSS, estos archivos estarán almacenados en una carpeta llamada css. Un archivo será para el diseño a dos columnas, otro archivo para el diseño a tres columnas, y los demás archivos será para las reglas CSS relacionas a textos, colores, tablas, secciones, artículos, etc. 


Dentro de la carpeta practica02, creamos la carpeta css, en donde vamos a tener tres archivos css, uno para un diseño de dos columnas, otro para el diseño a tres columnas y el ultimo un estilos.css para diseños de colores, tablas, fuentes, tamaños, etc.


 

 

dosColumnas.css

 


tresColumnas.css 


 


estilos.css 

En esta pagina de estilos.css diseñamos todas las páginas creadas asignándoles estilos a las letras, tamaños, estilo de letra, colores, etc. 

 










 
 
 
 
 




 
 
 
 
 
 

5-	También, se pide que se utilice selectores por etiquetas, selectores descendentes, selectores por clase y selectores por id. 

Selectores por etiquetas:

 

Selectores descendentes:

 

Selectores por clase:

 

Selectores por id:

 


6-	Luego, se pide que se personalicen al menos tres etiquetas para títulos (h1 – h6), tanto en color, tamaño, fuente, decoraciones, etc. 







Título h1

 

Título h2

 

Título h3

 


7-	Asimismo, se pide que se personalice todos los hipervínculos usando pseudo-clases. 

 





8-	También, se pide que se cree un menú vertical (navegación) para todas las páginas. El menú debe tener bordes ovalados, con color de fondo y una separación entre cada menú de al menos 5px. 

 


9-	De igual manera, se pide crear una nueva página HTML, en donde, se muestre un formulario de contacto que tenga los siguientes campos (nombre, correo electrónico, mensaje y botón para enviar). 

 
Para ello hacemos uso de un form,  el cual nos permitirá ir poniendo los campos solicitados el cual tendrá:

Label: Poner nombre de la etiqueta


Input: el cual nos genera cada campo como un id de nombre, name para el nombre, placeholder para poner el nombre o campo que requiera, un type para un email.

Button: este comando nos permite realizar un botón. 

 

10-	Asimismo, se pide que se utilice una gama de máximo cinco colores (ver más, https://htmlcolorcodes.com/es/recursos/mejor-paleta-de-colores-generadores/). 

Gamas: 

     Gama color blanco

   Gama color celeste

  Gama color Amarillo oscuro

  Gama color Gris

  Gama color Violeta.



RESULTADO(S) OBTENIDO(S):
•	Pudimos conocer y realizar archivos CSS para la generación de páginas web
•	Utilizar diferentes estilos de CSS
CONCLUSIONES:
•	Al concluir esta práctica aprendimos más acerca de CSS, sus funciones, utilidad y como hacerlos en HTML.
RECOMENDACIONES:
•	Poner bien las reglas CSS ya que después con la comprobación de W3 Validator nos sale errores.

Nombre de estudiante: Alex Cristopher Cuji Torres


Firma de estudiante:  e

