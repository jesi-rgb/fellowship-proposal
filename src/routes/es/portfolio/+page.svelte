<script>
	import Heading from '$lib/Components/Heading.svelte';
	import Hero from '$lib/Components/Hero.svelte';
	import WorkItem from '$lib/Components/WorkItem.svelte';
	import WorkTitle from '$lib/Components/WorkTitle.svelte';
</script>

<svelte:head>
	<title>Portfolio - ES — Processing Fellowship 2023</title>
</svelte:head>

<Hero text="Portafolio" />
<div class="text-2xl font-light">
	Aquí puedes ver el trabajo que hemos elaborado a lo largo de los años. <br /> ¡Esperamos que te
	guste! <br />
	<i class="text-lg text-gray-600 italic"
		>(Pssst… ¡Clica y arrastra todo lo que veas! La mayoría de estas demos son interactivas.)</i
	>
</div>
<div class="my-10 flex-col space-y-24">
	<div>
		<Heading>Selección de proyectos: Greg</Heading>

		<Heading>p5.js</Heading>
		<div class="grid grid-cols-1 xl:grid-cols-2 justify-evenly items-center gap-14 mb-10">
			<div>
				<WorkTitle
					title="Calculadora gráfica"
					link="https://editor.p5js.org/highermathnotes/full/Up0ONQ9dE"
				/>
				<iframe
					class="rounded-xl border-2 border-pink-600"
					loading="lazy"
					width="410"
					height="500"
					title="graphing calc"
					src="https://editor.p5js.org/highermathnotes/full/Up0ONQ9dE"
				/>
			</div>

			<div>
				<WorkTitle
					title="Simulador de un muelle"
					link="https://editor.p5js.org/highermathnotes/sketches/Q5vcziXmJ"
				/>
				<iframe
					loading="lazy"
					class="rounded-xl border-2 border-pink-600"
					height="500"
					width="410"
					title="mass spring"
					src="https://editor.p5js.org/highermathnotes/full/pq3qzh3hr"
				/>
			</div>

			<div class="">
				<a href="https://editor.p5js.org/highermathnotes/sketches/pq3qzh3hr">
					<WorkTitle
						title="Simulador de bacterias en un espacio discreto"
						link="https://editor.p5js.org/highermathnotes/sketches/0FQg_1mP5"
					/>
					<img
						src="/assets/bacteria.png"
						width="410px"
						class="rounded-xl border-2 border-pink-600"
						alt="bacteria simulation screenshot"
					/>
				</a>
			</div>
		</div>

		<Heading>visualODE</Heading>
		<div
			class="max-w-md mx-auto flex-col xl:grid xl:grid-cols-2 space-y-9 xl:space-y-0 xl:gap-14 xl:justify-around xl:max-w-5xl"
		>
			<WorkItem
				title="Distribución normal"
				link="https://www.khanacademy.org/computer-programming/interactive-normal-distribution/6221313412710400"
			/>

			<WorkItem
				title="Demostración de visualODE"
				link="https://www.khanacademy.org/computer-programming/visualode-demo/6127327220629504"
			/>

			<WorkItem
				title="Hipérbola degenerada"
				link="https://www.khanacademy.org/computer-programming/degenerate-hyperbola-interactive/5729571474915328"
			/>

			<WorkItem
				title="Diferenciación numérica"
				link="https://www.khanacademy.org/computer-programming/numerical-differentiation-applet/4587401748643840"
			/>
			<WorkItem
				title="Animación de una curva implícita"
				link="https://www.khanacademy.org/computer-programming/implicit-curve-animator-with-tangents/4886044829777920"
			/>
		</div>
	</div>

	<!---->
	<!---->
	<!-- Jesús -->
	<!---->
	<!---->

	<div>
		<Heading>Selección de proyectos: Jesús</Heading>

		<div class="flex-col xl:grid xl:grid-cols-2 space-y-6 xl:space-y-0 xl:gap-5">
			<WorkItem title="Así se inventaron los números imaginarios">
				<iframe
					src="https://www.youtube.com/embed/cUzklzVXJwo"
					class="rounded-xl w-full h-[250px]"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>

			<WorkItem title="El puzle que parece imposible incluso conociendo...">
				<iframe
					class="rounded-xl w-full h-[250px]"
					src="https://www.youtube.com/embed/iSNsgj1OCLA"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>
			<WorkItem title="El problema más simple que nadie puede resolver">
				<iframe
					class="rounded-xl w-full h-[250px]"
					src="https://www.youtube.com/embed/094y1Z2wpJg?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>

			<WorkItem title="La increíble efectividad de JPEG">
				<iframe
					class="rounded-xl w-full h-[250px]"
					width="560"
					height="315"
					src="https://www.youtube.com/embed/0me3guauqOU?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>

			<WorkItem title="Así funciona PNG">
				<iframe
					class="rounded-xl w-full h-[250px]"
					width="560"
					height="315"
					src="https://www.youtube.com/embed/EFUYNoFRHQI?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="La transformada discreta de Fourier">
				<iframe
					class="rounded-xl w-full h-[250px]"
					width="560"
					height="315"
					src="https://www.youtube.com/embed/yYEMxqreA10?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="El problema del viajante de comercio">
				<iframe
					class="rounded-xl w-full h-[250px]"
					width="560"
					height="315"
					src="https://www.youtube.com/embed/GiDsjIBOVoA?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="¿qué son los modos de fusión?">
				<iframe
					class="rounded-xl w-full h-[250px]"
					width="560"
					height="315"
					src="https://www.youtube.com/embed/D7Yg4H8e7uw?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
		</div>
	</div>
</div>
