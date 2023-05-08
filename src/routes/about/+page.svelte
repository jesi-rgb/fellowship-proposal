<script>
	import Heading from '../../lib/Components/Heading.svelte';
	import Hero from '../../lib/Components/Hero.svelte';
	import WorkItem from '../../lib/Components/WorkItem.svelte';
</script>

<svelte:head>
	<title>Joint Portfolio — Processing Fellowship 2023</title>
</svelte:head>

<Hero text="Joint Portfolio" />
<div class="text-2xl tracking-tight font-medium">
	Here, you can check out some of the work we've done over the years. We hope you like it!
</div>
<div class="my-10 flex-col space-y-24">
	<div>
		<Heading>Selected Work: Greg</Heading>
		<iframe
			class="rounded-xl border-2 border-pink-600 mx-auto"
			loading="lazy"
			width="405"
			height="500"
			title="graphing calc"
			src="https://editor.p5js.org/highermathnotes/full/Up0ONQ9dE"
		/>
		<div
			class="max-w-md mx-auto flex-col xl:grid xl:grid-cols-2 xl:gap-x-52 xl:justify-around xl:max-w-5xl"
		>
			<WorkItem
				title="Normal Distribution"
				link="https://www.khanacademy.org/computer-programming/interactive-normal-distribution/6221313412710400"
			/>

			<WorkItem
				title="VisualODE Demo"
				link="https://www.khanacademy.org/computer-programming/visualode-demo/6127327220629504"
			/>

			<WorkItem
				title="Degenerate Hyperbola"
				link="https://www.khanacademy.org/computer-programming/degenerate-hyperbola-interactive/5729571474915328"
			/>

			<WorkItem
				title="Numerical Differentiation"
				link="https://www.khanacademy.org/computer-programming/numerical-differentiation-applet/4587401748643840"
			/>
			<WorkItem
				title="Log spiral arc length reparameterization"
				link="https://www.khanacademy.org/computer-programming/log-spiral-arc-length-reparametrization-spin-off/5908979894534144"
			/>
			<WorkItem
				title="Implicit curve animator"
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
		<Heading>Selected Work: Jesús</Heading>

		<div class="flex-col xl:grid xl:grid-cols-2 xl:gap-5">
			<WorkItem title="The Simplest Math Problem No One Can Solve">
				<iframe
					class="rounded-xl w-full h-[250px]"
					src="https://www.youtube.com/embed/094y1Z2wpJg?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>

			<WorkItem title="The Unreasonable Effectiveness of JPEG">
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

			<WorkItem title="How PNG works">
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
			<WorkItem title="The Discrete Fourier Transform">
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
			<WorkItem title="The Traveling Salesman Problem">
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
			<WorkItem title="but what are Blend Modes?">
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
