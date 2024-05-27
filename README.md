# No sabes nada, John Snow! 

### Recreando el mapa fantasma con Python
¿Sabías que John Snow tiene que ver más con la ciencia de datos que con la madre de dragones? Acompañame en este proyecto a descubrir de dónde viene la famosa frase.

## Dr. Snow

<img src="/img/john_snow.jpg" align="left" width="150" style="margin-right: 20px;" />

El Dr. John Snow (quien nada tiene que ver con la famosísima serie de HBO), fue un médico británico ampliamente reconocido como una figura legendaria en la historia de la salud pública y un pionero destacado en el desarrollo de la anestesia. Él mismo administró cloroformo a la reina Victoria durante el nacimiento de su octavo y su noveno hijo en 1853 y 1857, lo que permitió una gran aceptación pública del uso de anestésicos durante el parto.
En la actualidad también se lo reconoce como el padre de la epidemiología moderna y, aún más, algunos lo consideran el fundador de la ciencia y visualización de datos, del análisis espacial y muchos otros campos relacionados, por su enfoque científico e innovador al identificar un brote de cólera en el barrio de Soho, Londres, en el año 1854.

Pero lamentablemente ésto no fue siempre así. Durante mucho tiempo ha sido ignorado y, a menudo, incluso mitificado por la comunidad científica.

En este proyecto, propuesto por **Radovan Kavicky** en la plataforma *Datacamp*, volví a analizar los datos que el doctor Snow recopiló en 1854 y recree su famoso mapa fantasma, mediante el uso de las librerías Pandas, Folium y Bokeh.

## ¡El cólera ataca!

<img src="/img/johnsnow_cholera1.jpg" align="right" width="150" style="margin-left: 20px;" />

El cólera era un visitante frecuente de las concurridas y antihigiénicas calles de Londres antes de que John Snow hiciera su descubrimiento. Entre 1839 y 1856, se publicaron más de 700 estudios y ensayos sólo en Londres, lo que lo convirtió en uno de los temas más estudiados en la época del tercer brote. 
Casi todos los autores sostuvieron la teoría de que los brotes eran causados por miasma o "mal aire". El innovador trabajo de John Snow con la antestesia y los gases es lo que inicialmente lo llevó a cuestionar el modelo de la enfermedad. Antes del brote de 1849, en un ensayo titulado "On the mode of communication of cholera", desarrolló y publicó por primera vez su propia teoría, de que el cólera se transmite por el agua o los alimentos. En The Lancet y London Medical Gazette, el ensayo recibió críticas desfavorables. Ahora sabemos que tenía razón, pero el Dr. Snow luchó con la forma de demostrarlo.   

## No sabes nada, John Snow

<img src="/img/johnsnow_cholera_king2.png" align="left" width="300" height="auto" style="margin-right: 20px;" />

El trabajo del Dr. Snow fue ignorado en gran medida porque resultaba impensable que una sola persona pudiera probar que TODOS los demás estaban equivocados. Sus colegas médicos simplemente dijeron: "¡No sabes nada, John Snow!". Su primer intento para desacreditar la teoría del miasma fracasó, pero para aclarar qué tipo de evidencia sería convincente, un revisor le dio el siguiente consejo: encontrar personas que vivieran juntas, con estilos de vida similares en todos los aspectos, **excepto en la fuente de agua que consumían**.
Snow tuvo la oportunidad de probar y refinar su teoría, además de salvar vidas, durante la epidemia de cólera en Soho, Londres, en 1854. Pero, ¿cuál fue la evidencia concluyente de que estaba en lo correcto?.

## El mapa fantasma

Lamentablemente, su mapa original no se encontró. Sin embargo, el famoso mapa que se muestra debajo, fue creado por el mismo Dr. Snow aproximadamente un año después, en 1855. Esta imagen se conoce como "The ghost map" porque representa y describe las muertes por cólera.

<img src="/img/mapa_original.jpg" style="text-align: center;" width="250"/>

## ¡Es la bomba!

Cuando John Snow marcó las muertes en el mapa, notó que no había un patrón aleatorio. La mayoría de las muertes ocurrieron principalmente en la intersección de Broad Street (actualmente Broadwick Street) y Cambridge Street (ahora Lexington Street). El epicentro del brote fueron varias muertes alrededor de la intersección de estas calles, pero ¿qué había allí? Sí, una bomba de agua.
Las ubicaciones de las bombas cercanas también fueron marcadas en el mapa por el Dr. Snow, quien en ese momento ya tenía una teoría bien desarrollada sobre cómo se propaga el cólera a través del agua. Entonces, ¡bingo!.
El Dr. Snow pudo demostrar que la mayoría de las muertes relacionadas con el cólera se centraron en una sola bomba de agua pública en Broad Street, al combinar las ubicaciones de las bombas con las ubicaciones de las muertes a causa de la enfermedad. ¡Por fin tenía las pruebas necesarias!.

<img src="/img/mapa_bombas_de_agua.png" style="text-align: center;" width="300"/>

## You know nothing, John Snow! (de nuevo)

<img src="/img/johnsnow_caricature1.jpg" align="left" width="300" style="margin-right: 20px;" />

Pero no se detuvo ahí y siguió investigando más a fondo. Estaba buscando anomalías en los datos (ahora diríamos "outliers") y, de hecho, encontró dos puntos en el mapa donde no hubo ninguna muerte: una cervecería de Broad Street y un asilo cerca de Poland Street. En ambos casos, comprobó que las personas no consumían agua de la bomba, la fuente del brote.
Ahora estaba seguro, y aunque las autoridades públicas no confiaban en él ni en su teoría, el 8 de septiembre de 1854 quitaron la manija de la bomba. Posteriormente, el Dr. Snow recopiló y publicó todos los datos sobre las muertes en su renombrado libro, en orden cronológico, antes y después del pico del brote.

## Una imagen vale más que mil palabras

<img src="/img/johnsnow_pump1.jpg" align="left" width="150" style="margin-right: 20px;" />

Quitar el mango de la bomba evitó que se siguiera consumiendo agua infectada. Más tarde se descubrió que el manantial debajo de la bomba estaba contaminado con aguas residuales. Este acto fue reconocido posteriormente como un pionero de la epidemiología, de la medicina de salud pública y la aplicación de la ciencia en una crisis de la vida real.

Una réplica de la bomba, junto con una placa explicativa y conmemorativa (sin manija) fue puesta en 1992 cerca de la ubicación de la original, a unos metros de la pared trasera de lo que actualmente es el pub John Snow. El sitio está marcado sutilmente con una placa de pared.

Podemos aprender mucho de los datos de John Snow. Pero, ¡atentos! observar solamente los números podría llevarnos a una conclusión errónea. Gracias al doctor Snow tenemos los datos en orden cronológico (es decir, como datos de series de tiempo), por lo que la mejor manera de ver el panorama completo es visualizarlo y mirarlo como él lo vio mientras escribía *On the Mode of Communication of Cholera (1855)*.

<img src="/img/grafico_de_linea.png" style="text-align: center;" width="600"/>


## El mito de John Snow

<img src="/img/johnsnow_water1.jpg" align="left" width="150" style="margin-right: 20px;" />

La visualización anterior muestra que el brote de cólera ya estaba decreciendo antes de que se eliminara la manija de la bomba el 8 de septiembre de 1854.

Esta perspectiva nos lleva a cuestionar una interpretación simplista: basados sólo en cifras, podríamos pensar erróneamente que la intervención del Dr. Snow en la bomba de Broad Street puso fin al brote. Pero, aunque su acción sin lugar a dudas ayudó, no fue la única solución. Snow era plenamente consciente de ello; actuó conforme a su deber, sin aspiraciones heroicas.

Pero a la gente le encantan las historias sobre héroes y otros mitos (definitivamente más que la ciencia o la ciencia de datos). Según el mito de John Snow, fue el superhéroe que en dos días desafió a sus iguales al plantear la hipótesis de que el cólera era una enfermedad transmitida por el agua. A pesar de que nadie lo escuchaba, valientemente continuó dibujando su mapa, convenció a las autoridades locales de quitar la manija de la bomba de agua infectada y detuvo el brote. John Snow salvó la vida de muchos londinenses.

Si miramos mejor detrás de esta historia, podemos encontrar también al verdadero John Snow, que luchaba contra la enfermedad con herramientas limitadas y quería obtener pruebas de que tenía razón y "sabía algo" sobre el cólera. Simplemente hizo lo que pudo, con un tiempo limitado, y siempre pero SIEMPRE hirvió el agua antes de tomarla.