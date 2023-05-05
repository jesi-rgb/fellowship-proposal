<script>
	import Paragraph from '../../lib/Components/Paragraph.svelte';
	import Link from '../../lib/Components/Link.svelte';
	import Hero from '../../lib/Components/Hero.svelte';
	import Heading from '../../lib/Components/Heading.svelte';
</script>

<svelte:head>
	<title>Our Proposal — Processing Fellowship 2023</title>
</svelte:head>

<div class="mx-auto max-w-sm md:max-w-md xl:max-w-xl">
	<Hero text="Our Proposal" />
	<Paragraph>
		<div>
			<span class="font-mono font-bold"> MatheMagical.js</span> is a proposed p5.js library for
			making web-based mathematical figures, animations, and interactives in 2D and 3D.

			<br />
			<br />
			Designed for learners, educators, and creators, it will be easy enough for beginners and flexible
			enough for experts. If you’re interested in this project, please let us know by filling out our
			<Link text="community form" link="/form" />! We’ll keep you updated.
		</div>
	</Paragraph>

	<Heading>The problem</Heading>
	<Paragraph>
		It is known that basic mathematical visualizations often require an intimidating amount of
		programming, even with a beginner-friendly library like p5.js. In Python, <Link
			text="Manim"
			link="https://manim.community"
		/> has recently become a popular solution, and for good reason. Thanks to its stunning visualizations
		and great flexibility, it has been called the gold standard of mathematical animation.

		<br />
		<br />

		Unfortunately, Manim users must have access to a machine on which they can install software.
		They must be ready to implement a difficult installation process. One of us, who happens to be a
		professional animator with a degree in computer science, actually broke his computer three times
		while trying to install Manim! They must know how to use the command line and be familiar with
		object-oriented programming.

		<br />
		<br />

		All this is required to draw a circle. The getting-started guide for p5.js also teaches users
		how to how to draw a circle, and the difference in accessibility is dramatic! So, our solution
		is to extend p5.js with an add-on library for mathematical visualizations. It should be as
		capable as Manim, but beginner friendly, and built for the web.

		<br />
		<br />
		We have <span class="font-bold">three top design priorities</span>:

		<ol class="list-disc flex-col space-y-3 py-3">
			<li>
				<b>Accessibility</b>. It must be easy for total beginners to use in the browser, with no
				setup.
			</li>
			<li><b>Interactivity</b>. It must be easy to make visualizations interactive!</li>
			<li>
				<b>Expressiveness</b>. It must be easy to create custom aesthetics.
			</li>
		</ol>
		We’ve already proposed the idea on Twitter, and it went viral!
	</Paragraph>
</div>
