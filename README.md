# Practica-02---CSS

 	PRÁCTICA DE LABORATORIO 

CARRERA:Computación 	ASIGNATURA:Programación Hipermedial
NRO. PRÁCTICA:	3	TÍTULO PRÁCTICA:Practica02-Mi sitio Web(CSS)
•	OBJETIVO ALCANZADO:
 Entender y organizar de una mejor manera los sitios de web en Internet Diseñar adecuadamente elementos gráficos en sitios web en Internet y por ultimo crear sitios web aplicando estándares actuales. 
ACTIVIDADES DESARROLLADAS
 1.Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)”
 
2. Realice un compromiso y presione por cada requerimiento de los puntos antes específicos.
A continuación se presentan todos los commits realizados a lo largo de la práctica:
 
Como se puede observar en la imagen los archivos ArquitecturaIndex del 1 al 6 hacen referrencia solo a CSS , mientras que los index html hacen referencia a los archivos web.
3. Creación de archivos html
-	Encabezados utilzados para las páginas desde Index hasta Index5
 
 
- En este pequeño fragmento podemos observar como procedemos a crear el documento html mediante el comando <!DOCYPE html>.
- Procedemos a crear la estructura básica de un documento html y mediante la etiqueta <html lang=”es” damos a entender que nuestra pagina sera escrita es español. 
- Creamos las etiquetas meta que forman parte de nuestro encabezado de la pagina web, en donde indicamos la primera sentencia meta, la cual hace referencia a cualquier visitante de una pagina web,ya que mediante las keywords podrá encontrar nuestra web en un navegador.Mientras que la segunda sentencia meta hace referencia al formato de texto que va a tomar la web, en este caso utf-8.Después creamos nuestra etiqueta<title> (titulo el cual es asignado).Finalmente para cerrar la etiqueta head procedemos a referenciar nuestro archivo css en este caso “ArquitecturaIndex.css”.	
- Procedemos al cuerpo o contenido de nuestra pagina mediante la etiqueta <body>.Primeramente le damos un encabezado por medio de la etiqueta <header>.Esta etiqueta esta dividida en 3 clases las cuales son:logo, redes y buscar.
En la clase logo se usó la etiqueta div para poder ubicar el elemento, en este caso la imagen que necesito usar en ese momento para direccionar el logo de la universidad a su pagina oficial.Se suele usar <nav> comúnmente que ya lo veremos mas adelante, pero en este caso use el blockquote, ya que nos vamos a referir a un solo sitio web en especifico en este caso es el url de la universidad:https://www.ups.edu.ec/sede-cuenca por lo cual lo necesito citar mediante cite. 
Usamos el mismo procedimiento recién mencionado para la clase redes, pero a diferencia de la clase logo aquí si usamos la etiqueta <nav> debido a que se va a mencionar varios sitios y ya no uno como fue el caso del logo.
Nuestra ultima clase del encabezado es buscar la cual hace referencia a la barra de búsqueda para ello usamos la etiqueta input para que el usuario pueda escribir lo que desea buscar, el atributo placeholder me permite colocar un valor de muestra en este caso “serch Text” la cual se verá reflejada dentro de la barra de búsqueda, mediante el atributo type especifico que se va a tratar de una búsqueda.Y por ultimo mediante el style le doy atributos css en mi caso un margin para centrarlo debido a que es un objeto y un tamaño con width.
Para la parte de nuestro menú en si creamos una lista desordenada <ul> con sus respectivos ítems <li> en mi caso: Inicio, Tipos, Marcas, Precios, Contacto y Consejos en donde referenciamos a las paginas que nos debe llevar en caso de pulsar algún ítem del menú. Hacemos saltos de lineas mediante el comando <br>.Finalizamos header y nuestro menú el cual va a ser replicado en nuestros posteriores archivos html.
•	Index.html (Inicio)
a.Contenido 
 
Una vez pasado el menú de nuestra página procedemos al contenido escencial de nuestra pagina de inicio la cual cuenta con las siguientes cajas :
-	<Aside id=”img1”> 
Dentro de esta caja vamos a colocar nuestra imagen al lado derecho como lo muestra el inicio base del documento de la practica.El atributo id hace referencia a que vamos a llamar a nuestro selector id ubicado en el archivo “ArquitecturaIndex.css”.Dentro de la caja aside procedemos a colocar el link de nuestra imagen a utilizar en el atributo src , es decir <img src = “url_imagen”> y finalizamos nuestra primera caja.
-	<Aside id=”información”>
En esta caja vamos a colocar información sobre el tema de nuestra página web.Como va a ser un párrafo descriptivo decidí colocar una etiqueta <article> y dentro de ella otra etiqueta <p> para hacer referencia a una descripción textual o escrita.En el párrafo competo se puede observar 2 tipos de etiquetas:
-	h: ocupada para hacer énfasis a subtítulos dentro del articulo.
-	strong: ocupada para resaltar alguna palabra o letra clave dentro del pequeño articulo.
En mi caso fue una capital letter con el fin de hacerlo parecer un articulo.para ello usamos css mediante style en el cual definimos “font-size:2rem”, decidí no hacer un selector debido a que solo use este atributo para este caso puntual.Finalmente lo llamamos al selector id dentro de la etiqueta aside para que me aplique todas las propiedades css.
-	<section class=”sectionA”>
En mi caso use esta sección para colocar contenido multimedia para lo cual se decidio usar 3 tipos de etiquetas:
- h: ocupada para el titulo de la sección.
-  iframe: ocupada para poder introducir videos de youtube en nuestra web.
- video: mediante la cual damos las dimensiones que va a tener nuestro video y tambien con el atributo controls le permitimos al usuario reproducir el video cuando desee , mientras que en la etiqueta type definimos el formato de nuestro video. Finalmente llamamos a la clase dentro de la etiqueta section para que me aplique todas las propiedades css.
-	<section class=”sectionB”>
 


Utilizamos otra sección para colocar percusiones acerca de mi tema de estudio en donde simplemente usamos una etiqueta p debido a que no es la introducción de la pagina de inicio donde se ocupó la etiqueta article.Dado el caso de que no se cumplieron los requisitos mencionados, decidí dejarle solo como una sección textual que no tenía mucha relevancia, realmente lo único distinto fue la utilización de listas ordenadas<ol>.Finalmente llamamos a clase sectionB para que aplique las propiedades css.
-	<section class=”SectionC”>
Se usó para colocar una dirección, como en casos anteriores debido a que solo es ocupada en este caso puntual, se decidió en hacer css únicamente al tamaño del font mediante el atributo style.Lo novedoso de esta sección fue el haber logrado insertar un mapa de google mediante la etiqueta iframe que ya fue mencionada antes para la inserción de videos de youtube. 
-	<section id=”piepagina”>
 




En esta sección insertamos el primer formulario. Para la elaboración del formulario vamos a neceseitar de las siguientes etiquetas:
-	Form para especificar que es un formulario
-	Fieldset para el contorno del formulario
-	Legend para el título del formulario
-	Cite para cursear el enunciado del formulario
-	Input para ingresar valores en las cajas de texto.Dentro de este input usamos type=”radio” para hacer botones circulares, mientras que en name colocamos las opciones para que el usuario seleccione.El último input que falta por mencionar es el button el cual me permite crear botones en el formulario.
Ya para finalizar el archivo Index.html colocamos la etiqueta <footer> en la cual vamos a colocar un enlace para que me puedan realizar una llamada mediante <a href=”tel:+codigo, numero” > y en mi caso le coloque un icono de llamada de facetime, mientras que al lado se encuentra el icono de mail para el cual se hizo el mismo procedimiento solo que en vez de telf colocamos malito:mi_correo.
Debajo de estos iconos coloque mi imagen debido a que los enlaces mencionados son para que los demás se puedan comunicar conmigo.Por ultimo colocamos la etiqueta audio, esta tiene la misma funcionalidad que la etiqueta video solo que ocupa formatos de audio como mp3,wav.etc.Ya aquí solamente pongo agradecimientos mediante la etiqueta <p> y <cite> para citar el autor en este caso mi persona ,<em> para hacer énfasis en alguna palabra o frase , <time> para la fecha. 
•	Index1.html (Tipos)
B.Contenido
 
-	<Aside id=”información”>
-	En esta caja vamos a colocar información sobre el tema de nuestra página web.Como va a ser un párrafo descriptivo decidí colocar una etiqueta <article> debido a que es lo elemental de la página y dentro de ella otra etiqueta <h> para hacer referencia al tema central.dentro del articulo también se puede observar una lista descriptiva la cual use debido a los puntos a tocar en este tema.al igual que en la pagina inicial donde sus items están definidos con la etiqueta <dt> y sus contenidos con la etiqueta <dd><p> para el texto.las imágenes<img src”url”> y el video de youtube<iframe> están para clarificar el concepto en uno de los puntos de la lista.
-	<aside id=”información1”>
 
-	Dentro de la caja aside decidí utilizar article debido a que lo que se trata dentro de información1 es secuencial con lo que se había tratado previamente en información.Dentro de la etiqueta articulo estoy usando listas ordenadas <ol> para las secciones y <li> para los ítems, ademas de eso también uso etiquetas p para el texto, h para los títulos o secciones y <strong> para resaltar palabras o frases.Ya en el pie de pagina.
-	Ya en el footer cargo información del autor de la pagina donde &#8226 es para colocar una viñeta, ademas de usar la etiqueta<em> para hacer énfasis en la frase vuelva pronto, la etiqueta <cite> para citar al autor,la etiqueta <p> de texto para agradecimientos y ya para finalizar la etiqueta <time> la cual es útil para colocar la fecha.




•	Index2.html (Marcas)
C.Contenido
 
 

-	Para este archivo se uso la caja aside, mientras que tambien se uso la etiqueta<h> para darle el titulo a las secciones que estamos por observar,<p> para texto , <ul> para una lista desordenada debido a que los temas de la lista no son secuenciales ni tienen ningun orden jerarquico como ya se sabe cada item lleva la etiqueta <li>
-	Se procede a hablar de un cargador de samsung conocido por lo cual el titulo del mismo lleva la etiqueta<strong>.
-	Debido a las pocas etiquetas <p> que hay en este archivo , tome la decisión de que el css (text-align) de esta etiqueta en especifico se lo realice mediante el atributo style .
-	Las imágenes insertadas mediante <img src”url”> son de los cargadores mencionados.En esta parte en los casos de los cargadores Twelvesouth HiRise Wireless y Pitaka Air Trio se uso css para anidar 4 imágenes en una sola franja 
-	La etiqueta <div class=”slader”> se uso en concreto para alinear la franja de imágenes y aplicar la propiedad css.

•	Tabla
 

 
-	De la linea 129 hasta la 207 esta creada la tabla mediante el comando <table> ,<tr> es para row que seria columna y <td> el contenido de cada fila horizontal asi se haria durante todos los campos de la Tabla y<tbody>para el contenido de una tabla. 
-	Dentro de <tbody> se aplico la propiedad de alinear texto mediante style CSS
-	El comando <td rowspan=” ” colspan=“”>hace referencia al borde que es e grosor de la tabla, el rowspan al espaciado entre cada celda de la tabla por asi decirlo , y el calspan es el espaciado de los margenes. 
-	 Ya en el footer cargo información del autor de la pagina donde &#8226 es para colocar una viñeta, ademas de usar la etiqueta<em> para hacer énfasis en la frase vuelva pronto, la etiqueta <cite> para citar al autor,la etiqueta <p> de texto para agradecimientos y ya para finalizar la etiqueta <time> la cual es útil para colocar la fecha.
•	Index3.html (Precios)
D. Contenido
 
 
-	Ocupamos la etiqueta h para titulos o secciones.En este caso cada item a vender.
-	En este caso nuestra caja css es section dentro de la cual no tiene ningun id de selección debido a que en esta clase decidí aplicar a todas las etiquetas <section> .
-	En lo que si se decidio aplicar un selector id fue en la etiqueta <span> para el precio.
-	Como es una pagina de precios tambien se icupo la etiqueta <img src=”url”> para insertar imágenes.
-	Ya en el footer cargo información del autor de la pagina donde &#8226 es para colocar una viñeta, ademas de usar la etiqueta<em> para hacer énfasis en la frase vuelva pronto, la etiqueta <cite> para citar al autor,la etiqueta <p> de texto para agradecimientos y ya para finalizar la etiqueta <time> la cual es útil para colocar la fecha.
•	Index4.html (Contactos)
E.Contenido
 
-	Se ocupo la etiqueta <h> para secciones o titulos. 
En este aside insertamos el segundo formulario. Para la elaboración del formulario vamos a neceseitar de las siguientes etiquetas:
-	Form para especificar que es un formulario
-	Fieldset para el contorno del formulario
-	Legend para el título del formulario
-	P para el texto
-	Div para los labels
-	Input para ingresar valores en las cajas de texto.Dentro de este input usamos type=”text” para hacer las cajas de texto, mientras que en name colocamos los nombres de cada caja a los cuales se les da dimensiones mediante style=width,height.El último input que falta por mencionar es el button el cual me permite crear botones en el formulario.
-	Ya en el footer cargo información del autor de la pagina donde &#8226 es para colocar una viñeta, ademas de usar la etiqueta<em> para hacer énfasis en la frase vuelva pronto, la etiqueta <cite> para citar al autor,la etiqueta <p> de texto para agradecimientos y ya para finalizar la etiqueta <time> la cual es útil para colocar la fecha.
•	Index5.html (Consejos)
F.Contenido
 
-	Dentro de esta caja aside vamos a colocar nuestra imagen al lado izquierdo como lo muestra el inicio base del documento de la practica.En este caso debido a que es la unica imagen decidi llamar a la propiedad css ubicado en el archivo “ArquitecturaIndex5.css”.Dentro de la caja aside procedemos a colocar el link de nuestra imagen a utilizar en el atributo src , es decir <img src = “url_imagen”> y finalizamos nuestra primera caja.
-	En la otra caja aside vamos a colocar información sobre el tema de nuestra página web.Como va a ser un párrafo descriptivo decidí colocar una etiqueta <article> y dentro de ella otra etiqueta <p> para hacer referencia a una descripción textual o escrita.En el párrafo competo se puede que tiene una lista desordenada <ul> con items <li>.Cabe reclacar que ninguna aside tiene un id selector o una calse debido a que en el archivo css se esta aplicando a todas las etiquetas aside.
-	Ya en el footer cargo información del autor de la pagina donde &#8226 es para colocar una viñeta, ademas de usar la etiqueta<em> para hacer énfasis en la frase vuelva pronto, la etiqueta <cite> para citar al autor,la etiqueta <p> de texto para agradecimientos y ya para finalizar la etiqueta <time> la cual es útil para colocar la fecha.
4.Creación archivos CSS
-	Encabezados utilzados para las páginas desde Index hasta Index5
 
-	El punto hace referencia a una clase 
-	Dentro de la clase logo estoy diciendo que lo que pertenezca a logo va a ser movido al lado izquierdo.
-	Dentro de la clase buscar le estoy dando un tamaño a buscar de un 60% /100.El display inline-block me permite permite establecer un ancho y alto en el elemento.
-	Dentro de la clase redes estoy diciendole a la clase que todo su contenido va a ser movido al lado derecho y ademas le estoy dando un margin top dde 34px para que se separe un poco y me quede alineado con el resto de elementos
-	Mientras que el input,label lo ocupo para la barra <input> de buscar en donde le digo que va a estar estatica.
-	el header va a tomar como color de fondo un tono medio verde oscuro el cual fue sacado de la web recomendado en el enunciado de la practica, mientras que el body va a tomar un color como tipo beage.
-	Con el selector button estoy diciendo que todas las etiquetas que lleven ese selector se le va aplicar un padding(espaciado) de 0;
-	Por ultimo el #button li a va a ser todas las propiedades que va a tomar nuestro menu en si en este caso que va a tener una fuente arial en letra con un tamaño de 11px , no va a tener decoracion , va a estar ubicado en la parte izquierda.Su espaciado sera de 4px y su color de fondo sera un tono azulado y por ultimo su texto será justificado.
•	ArquitecturaIndex.css(Inicio)
a.Contenido
  
-	En el selector img1 le estoy diciendo que todos los que lleven ese id sera colocado en la parte derecha, en este caso una imagen.
-	En esta parte estoy diciendo que el primer aside va a colocarse en la parte derecha en este caso el de la imagen.
-	En el aside article digo que se va a ubicar en la parte izquierda y su texto va a ser justificado
-	Al selector informacion le estoy reduciendo su tamaño a un 55% 
-	Al selector audio le digo que va a estar ubicado en el lado izquierdo.
-	Al iframe le estoy dando un borde de 0px
-	A las etiquetas h2 les estoy justificando su texto.
-	En la clase sectionA  le estoy dando un margen en la parte superior de 550px con el fin de alinearlo,un borde tipo solid con un grosor de 2px y selecciono el color que se ve en la imagen.
Un espaciado de 10px y un background tipo beage.
-	En la clase sectionB,ol que hace referencia a una lista ordenada.Dentro de la clase vamos a tener las siguientes propiedades: un margen en la parte superior de 0px,un borde color medio morado, un espaciado de 10px,un background y el texto justificado.
-	Mientras que por ultimo en la clase sectionC igual voy a tener un marger en la parte superior de 0px,un alineamiento de texto a la izquierda un borde tipo color verde oscuro,un padding de 180 debido a que contiene el footer y el formulario.Por ultimo un backgroud verde.
-	Un margen superior de 80px para la etiqueta address.
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde.
•	ArquitecturaIndex1.css(Tipos)
B.contenido
 
-	Al selector imagen le doy un margen hacia la izquierda de 184px con el de alinearlo.
-	Al selector informacion1 justifico el texto, le doy un margen de 66px y un ancho de 721px , cabe recalcar que al width tambien se le puede dar valores de porcentaje.
-	A mi primera etiqueta aside la voy a ubicar a la derecha con un tamaño de caja del 40%
-	Mientras que mi a seccion de aside y article los voy a ubicar en el lado izquierdo, el texto justificado y un background café claro .
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde y por ultimo un borde superior solid de 2px color negro.
•	ArquitecturaIndex2.css(Marcas)
C.Contenido
  
-	En el primer article justifico el texto,le doy un tamaño del 45% a la caja y lo ubico en la parte izquierda
-	En el segundo article tambien lo justifico,le doy un tamaño del 50% a la caja , lo ubico a la derecha con un background tono verdoso.
-	Centro las etiquetas h3,h1
-	Aquí aplico la propiedad de juntar imágenes en una sola franja mediante el display flex lo divido en secciones , le doy un tamaño dedl 25% y una dimension de 30vh que seria el 30% del viewport.Con el object-fit cover lo que hago es que las imágenes se ajusten al tamaño del contenedor.
-	Procedemos a realizar las propiedades para la etiqueta table la cual tiene un tamaño normal , un borded solido negro de grosor 1px y background tono azul palido.
-	Th , td esto hace referencia a las celdas de la tabla, las cuales vana tener un tamaño de un 25% , su texto va a estar alineado al centro , va a estar alienada de manera vertical , va a tener un bordde de 2px solido color negro , el row-gap que establece el espaciado de las filas , el colum-span que hac que sus columnas se extiendan para que puedan abarcar todas, el border-spacing que establece el espacio entre los bordes y por ultimo el padding-block-end que define el relleno de un elemento.
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde y por ultimo un borde superior solid de 2px color negro.
-	La etiqueta footer la cual tiene asignado un background especifico.
-	La etiqueta aside que tiene asignado un background especifico.
•	ArquitecturaIndex3.css(Precio)
D.Contenido
  
-	En la etiqueta section vamos a dadrle un borde superior solido de 3px color tono gris con un tamaño de caja del 50% y un texto justificado.
-	En el selector imgpr1 hago referencia al selector del precio el cual sera usado en todos los articulos .Este va a estar ubicado en la parte derecha con un margen en sus cuatros lados con los valores indicados , un tamaño de caja del 20% , un margen a la derecha de -272px y un -60 a la parte superior  con el fin de alinearlo, por ultimo una altura de 111px.
-	En el precio va a ser exactamente los mismos campos pero con otros valores y adicionalmente eb este selector de precio aplicamos un font sans-serif.
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde y por ultimo un borde superior solid de 2px color negro.
-	La etiqueta footer la cual tiene asignado un background especifico.
-	La etiqueta html que tiene asignado un background especifico.
•	ArquitecturaIndex4.css(Contacto)
E. Contenido
 
-	Creamos una clase img1 la cual unicamente va a tener la propiedad de width(tamaño)
-	Una etiqueta input para las cajas de texto del formulario , las cuales van a tener un tamaño de 662px
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde y por ultimo un borde superior solid de 2px color negro.
-	La etiqueta footer la cual tiene asignado un background especifico.
•	ArquitecturaIndex5.css(Consejos)
F.Contenidos

 
-	El primer aside es para la imagen la cual va a estar ubicada en el lado izquierdo
-	El segundo aside viene acompañado de un article en el cual su texto va a estar justificado y su caja o contenido va a tener un tamaño del 50%
-	Tenemos un selector para nuestra imagen la cual va a tener la propiedad de ubicación, tamaño y ancho 
-	Establecemos un estandar para la etiqueta p del 196%
-	A las listas le damos un tamaño de 120%
-	El selector pie de pagina no va tener margen la parte superior debido a que es de 0px, usamos el clear:both para el footer un borde de un tono morado, un espaciado de 0 , un borde-botton para la parte inferior , un background para el selector de un tono verde y por ultimo un borde superior solid de 2px color negro.
-	La etiqueta footer la cual tiene asignado un background especifico
Link Github: https://github.com/KevinGodoy98/Practica-02-CSS.git

RESULTADO(S) OBTENIDO(S):
•	MENU
 
•	PAGINA INICIO(INDEX)
 
•	PAGINA TIPOS(INDEX1)
 
•	PAGINA MARCA(INDEX2)
 
 
•	PAGINA PRECIO(INDEX3)
 
•	PAGINA CONTACTO(INDEX4)
 
•	PAGINA CONSEJOS(INDEX5)
 

•	Validaciones 

-	Index(Inicio)
 
-	Index1(Tipos)
 
-	Index2(Marcas)
 
-	Index3(Precios)
 
-	Index4(Contacto)
 
-	Index5(Consejos) 
CONCLUSIONES:Gracias a esta practica se logró entender de mejor manera como funciona la parte de css 
RECOMENDACIONES: Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari.

Nombre de estudiante:                 Kevin Godoy


Firma de estudiante:                           


