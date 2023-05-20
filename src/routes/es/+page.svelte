<script>
	import { Handshake, MicrophoneStage, NotePencil } from 'phosphor-svelte';
	import Hero from '$lib/Components/Hero.svelte';
	import Link from '$lib/Components/Link.svelte';
	import Page from '$lib/Components/Page.svelte';
	import Paragraph from '$lib/Components/Paragraph.svelte';
	import Card from '$lib/Components/Card.svelte';
	import Heading from '$lib/Components/Heading.svelte';
</script>

<svelte:head>
	<title>Processing Fellowship 2023</title>
</svelte:head>

<Page>
	<Hero text="Mathemagical.js" />
	<Heading>Propuesta para la Processing Fellowship 2023</Heading>
	<Paragraph>
		<p>
			Hola! Somos <span class="font-bold">Greg</span> y <span class="font-bold">Jesús</span>, dos
			desarrolladores viviendo en Denver, Colorado y Jaén, España, dispuestos a participar en la <Link
				link="https://medium.com/@ProcessingOrg/open-call-processing-foundation-fellowship-program-462b057285"
				text="Processing Fellowship para este año 2023"
			/>.
		</p>
		<br />
		<p>
			Pretendemos construir una librería de visualización matemática como nunca antes vista. Aquí
			puedes consultar nuestra propuesta y nuestro trabajo.
		</p>
		<br />
	</Paragraph>
</Page>

<Page>
	<Hero text="Nuestra propuesta" />
	<div>
		<Paragraph>
			<p>
				Gracias a <Link text="Manim" link="https://www.manim.community/" /> y a sus increíbles visualizaciones,
				la animación se ha convertido en un medio importante para la divulgación de las matemáticas.
			</p>

			<br />

			<p>
				¿No sería genial si los estudiantes y profesores pudieran programar fácilmente estas
				animaciones matemáticas directamente en el navegador, compartirlas e interactuar con ellas?
			</p>

			<br />

			<p>
				Para hacer esto posible, proponemos Mathemagical.js: una herramienta basada en tecnologías
				web para crear figuras matemáticas, animaciones y elementos interactivos en 2D y 3D.
				Aprovechando el increíble trabajo de la comunidad de p5.js, podremos hacerla suficientemente
				fácil para los principiantes, pero igualmente flexible para los expertos.
			</p>

			<br />
		</Paragraph>
		<br />
	</div>
</Page>

<Page>
	<Hero text="Sobre nosotros" />

	<div class="mt-10 font-bold text-pink-600 text-3xl">Greg</div>
	<Paragraph>
		Soy <b>profesor de matemáticas profesional</b>, youtuber y programador. Hace tiempo construí una
		primera versión de Mathemagical.js llamada visualODE. También he montado una página web para mi
		servicio de Higher Math Help, en el que tengo 15 años de experiencia tratando con alumnos de tú
		a tú.

		<br />
		<br />
		Como becario de la Fundación Wikimedia, he creado una <b>wiki</b> y una <b>comunidad</b> de profesores
		de matemáticas para Eventmath (en colaboración con el Dr. Brendan Sullivan). Mi meta a largo plazo
		es compartir mi material educativo online con estudiantes de todo el mundo, de forma gratuita.
	</Paragraph>
	<div class="mt-10 font-bold text-pink-600 text-3xl">Jesús</div>
	<Paragraph>
		Soy un creador de contenido profesional, especializado en ciencias de la computación, diseño
		gráfico y animación procedural. Mis animaciones hechas en Manim han aparecido en varios de los
		vídeos más populares de Youtube, alcanzando hasta 60 millones de visualizaciones.

		<br />
		<br />
		También trabajé en la implementación de exportar GIFs de forma nativa en p5.js, así que sé alguna
		cosa que otra acerca de animaciones en la web. También soy un desarrollador web, así que procuraré
		que Mathemagical.js tenga un buen sitio en la web, con demostraciones y documentación para todos
		los públicos.
	</Paragraph>
</Page>

<Page>
	<Hero text="Más detalles" />

	<div class="flex flex-col items-stretch xl:flex-row justify-evenly gap-10 mt-20">
		<Card title="Propuesta" link="/es/proposal">
			<NotePencil slot="icon" size={200} />
			<p slot="content">
				Aquí puedes consultar más detalles y preguntas frecuentes que actualizaremos en función de
				las preguntas que surjan de la comunidad.
			</p>
		</Card>

		<Card title="Portafolio" link="/es/portfolio">
			<Handshake slot="icon" size={200} />
			<p slot="content">
				Puedes echar un ojo a nuestro portafolio para ver algunos de los proyectos en los que hemos
				trabajado.
			</p>
		</Card>

		<Card
			title="Formulario de la comunidad"
			link="https://docs.google.com/forms/d/e/1FAIpQLSeaUbq5oLIuehUUCnKRd-mwHx1B8E5Ml6s6DAXXNZ0XMhHLiw/viewform?hl=es"
		>
			<MicrophoneStage slot="icon" size={200} />
			<p slot="content">
				Si te interesa este proyecto, por favor: ¡cuéntanos qué te parece rellenando el formulario!
				¡Te iremos contando!
			</p>
		</Card>
	</div>
</Page>
