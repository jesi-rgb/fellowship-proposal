<script>
	import Paragraph from '$lib/Components/Paragraph.svelte';
	import Link from '$lib/Components/Link.svelte';
	import Hero from '$lib/Components/Hero.svelte';
	import Heading from '$lib/Components/Heading.svelte';
</script>

<svelte:head>
	<title>Nuestra propuesta — Processing Fellowship 2023</title>
</svelte:head>

<div class=" max-w-sm md:max-w-md xl:max-w-xl">
	<Hero text="Nuestra propuesta" />
	<Paragraph>
		Pretendemos solucionar un problema al que se enfrentan tanto profesores como estudiantes.
		Solucionándolo, podremos permitirles construir, explorar y crear de maneras actualmente
		inaccesibles.
	</Paragraph>

	<Heading>El problema: La accesibilidad</Heading>
	<Paragraph>
		Queremos resolver un problema de accesibilidad: los estudiantes y profesores de matemáticas se
		beneficiarían enormemente de librerías para la visualización de las matemáticas, pero aún no
		existe una librería que sea accesible para ellos.

		<br /><br />
		Crear visualizaciones matemáticas básicas a menudo requiere de una intimidante cantidad de programación,
		incluso con herramientas más sencillas como p5.js.

		<br /><br />
		En Python, Manim se ha convertido en una de las librerías más populares, con razón. Se la estima
		como el estándar de la animación matemática gracias a sus preciosas animaciones.

		<br /><br />
		Aún así, los usuarios de Manim deben tener acceso a un ordenador en el que puedan instalar programas.
		Deben estar listos para acometer un difícil proceso de instalación. Deben conocer la terminal y estar
		familiarizados con programación orientada a objetos. Todo esto, simplemente para poder dibujar un
		círculo.
	</Paragraph>

	<Heading>La solución: Mathemagical.js</Heading>
	<Paragraph>
		Del mismo modo que la guía rápida de Manim, la de p5.js enseña a los usuarios a dibujar un
		círculo. ¡La diferencia es abismal!

		<br /><br />
		Nuestra solución es extender p5.js con una librería especializada en animación matemática. Será tan
		potente como Manim, pero mucho más fácil de utilizar y construida para la web.

		<br /><br />
		Nos sustentamos sobre tres principios para su diseño:
		<br /><br />

		<ul class="list-disc">
			<li>
				<b>Accesibilidad</b>: debe ser fácil hasta para el más novato.
			</li>

			<li><b>Interactividad</b>: debe ser fácil hacer las animaciones interactivas.</li>
			<li><b>Expresividad</b>: debe ser fácil crear una estética personalizada.</li>
		</ul>

		<br />
		Basándonos en la <Link
			text="abrumadora acogida que tuvo en Twitter"
			link="https://twitter.com/HigherMathNotes/status/1638652022022115328"
		/>, ¡parece que vamos en buen camino!
	</Paragraph>

	<Heading>Nuestra propuesta</Heading>
	<Paragraph>
		Proponemos Mathemagical.js, una librería basada en p5.js para construir figuras matemáticas,
		animaciones y sistemas interactivos en 2D y en 3D, todo en la web. Diseñado para estudiantes,
		profesores y creadores, será suficientemente fácil para los novatos y suficientemente flexible
		para los expertos.
	</Paragraph>

	<Heading>Preguntas frecuentes</Heading>
	<Paragraph>
		<ul class="list-decimal">
			<li>
				<p class="font-medium text-2xl text-pink-600 my-9">
					¿Qué podré hacer con Mathemagical.js que no puedo hacer con Desmos o Geogebra?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						Construiremos Mathemagical.js encima de p5.js, que está diseñada no sólo para
						estudiantes y profesores, sino también para artistas visuales. Por lo tanto, podrás
						personalizar tus animaciones tanto como quieras.

						<br />

						<i class="font-light">
							(Algunos creadores
							<Link
								text="pueden verse limitados"
								link="https://www.mathemaniac.co.uk/blog/how-i-use-geogebra-to-make-animations-in-videos-part-i"
							/></i
						> con herramientas como Geogebra)
					</li>
					<li>
						Además, pretendemos hacer que Mathemagical.js funcione mejor que Geogebra en la web (por
						ejemplo, compara <Link
							text="este atractor"
							link="https://www.geogebra.org/m/wtdx457q#material/JGGV5b5A"
						/> hecho en Geogebra y <Link
							text="este otro atractor"
							link="https://www.dynamicmath.xyz/strange-attractors/"
						/> hecho con p5.js, ambos por el mismo autor)
					</li>
					<li>
						Lo que uno puede crear con p5.js solo está limitado por la imaginación. Se puede
						utilizar para cualquier cosa imaginable, ya sea en 2D o en 3D. Hasta podemos incluir
						sonidos y otros tipos de multimedia.
					</li>
				</ul>
			</li>
			<li>
				<p class="font-medium text-2xl text-pink-600 my-9">
					¿Cómo se compara Mathemagical.js con Manim?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						Manim es potente y muy popular entre los creadores de contenido de carácter técnico.
						Está hecho en Python, y ofrece unos valores predeterminados muy apropiados sin
						comprometer la capacidad de personalización. Aún así, es bastante difícil de instalar,
						requiere de bastantes recursos para funcionar y no es apto para principiantes.
					</li>
					<li>
						Nuestra idea es traernos lo mejor de Manim a la web, donde no hay que instalar nada y
						con una curva de aprendizaje mucho más asequible. Lo haremos mediante p5.js, que está
						construida con herramientas nativas para la web con la que podemos integrar y compartir
						en internet además de añadir elementos interactivos, un elemento clave para el
						aprendizaje de las matemáticas.
					</li>
				</ul>
			</li>
		</ul>
	</Paragraph>
	<Heading>Demo</Heading>
	<iframe
		class="w-full border-2 border-pink-600 rounded-xl"
		height="315"
		src="https://www.youtube.com/embed/Br40z-lpC3o"
		title="YouTube video player"
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
		allowfullscreen
	/>
</div>
