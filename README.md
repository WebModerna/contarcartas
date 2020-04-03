<h1>Programa de contar cartas</h1>

<p>
	Programa para contar cartas y brindarte la probabilidad de que la siguiente carta, sea menor o igual a la que sacaste recién.
</p>

<p>
	Está diseñado específicamente para las calculadoras <stron>CASIO fx6600</stron>, de ahí para arriba.
	<br />
	También las para las calculadoras fincancieras <stron>CASIO FC-200</stron>, para arriba; que admita lenguaje de programación.
</p>

<h2>Explicación en el desarrollo</h2>
<p>
	Consiste en intruducir sentencias en espacios de la memoria (<em>Limitada por cierto</em>);
	empezando por banderas o flags. Entiéndase como marcadores de destino.
	Las sentencias <strong>GOTO xx</strong> son las que llevan a mensionados marcadores de destinos.
</p>
<p>
	También hay contadores, ya que el lenguage es limitado y no admite el famoso i++. En cada casilla de memoria sólo puede ir una sola cosa: ya sea una letra, destino, una instrucción simple, un número, un comparador, etc... Por eso vale racalcar lo limitado que es la construcción de un programa, debe ser muy optimizado.
</p>

<h3>Lo que hace:</h3>
<p>
	Primero que nada construye una matriz de un mazo virtual de tantas cartas, siempre número par y múltiplo de 4.
</p>
<p>
	En la vida real, uno debe contar con dicho mazo de cartas y extraer una cierta cantidad de cartas y ponerlas boca abajo; y guarda el resto a un lado.
</p>
<p>
	Eso mismo preguntará el programa: ¿Cuántas cartas sacaste?
</p>
<p>
	Luego uno sacará, de esa extracción, la carta de más arriba. El programa preguntará cuál fue.
</p>
<p>
	Uno le constestará al programa. Entonces la magia sucede: el programa responderá que tienes una probabilidad del tanto por cierto que la próxima carta sea menor o igual a la que sacaste.
</p>
<p>
	El conteo es exacto y la probabilidad exacta. El programa irá reduciendo paulatinamente el mazo virtual en cada movimiento.
</p>
<p>
	Ayuda a que ganes el juego contra otra persona entre un 75 y 80% de las veces.
</p>
<p>
	Claro, es una probabilidad, puede que pierdas. Pero si juegas 100 veces, siempre ganarás entre un 75 u 80% de las veces.
</p>
