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
			enough for experts.

			<p class="text-sm mt-10 opacity-70">
				If you’re interested in this project, please let us know by filling out our
				<Link text="community form" link="/form" />! We’ll keep you updated.
			</p>
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

	<Heading>FAQ</Heading>
	<Paragraph>
		<ul class="list-decimal">
			<li>
				<p class="font-medium text-2xl text-pink-600 my-9">
					What will Mathemagical.js do that Geogebra or Desmos doesn’t?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						The framework we’re building on, p5.js, is designed not only for learners and educators,
						but also visual artists. As an extension of this, Mathemagical.js will support a high
						degree of aesthetic customization out of the box.

						<br />
						<i class="font-light"
							>(Creators using tools like Geogebra can run into limitations in this regard. See
							these blog articles, for example.)</i
						>
					</li>
					<li>
						We aim to make Mathemagical.js more performant than Geogebra is on the web (e.g. compare
						<Link
							text="this strange attractor"
							link="https://www.geogebra.org/m/wtdx457q#material/JGGV5b5A"
						/> built with Geogebra and
						<Link
							text="this strange attractor"
							link="https://www.dynamicmath.xyz/strange-attractors/"
						/> built with p5.js, both from the same author).
					</li>
					<li>
						Creations built on p5.js are limited only by the imagination. We can use it to make
						anything we can imagine, in 2D or 3D. We can include sound and other multimedia files.
					</li>
				</ul>
			</li>
			<li>
				<p class="font-medium text-2xl text-pink-600 my-9">
					How will Mathemagical.js compare to Manim?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						Manim is incredibly powerful and very popular among the technical content creators.
						Built in python, it offers very nice and sensible defaults without compromising on
						extensibility. It is, nevertheless, a heavy program to run, quite difficult to install
						and not that easy to setup and use. The idea is to take <b
							>all that's good in Manim and bring it to the p5.js world</b
						>, with 0 installation and a much softer learning curve.
					</li>
					<li>
						Also, while it has already been considered and tried, Manim is <b
							>not quite as suited for the web as p5.js is.</b
						> p5 being a native web citizen allows for immediate web integration and sharing, as well
						as enabling interactivity, a core element for math learning.
					</li>
				</ul>
			</li>
		</ul>
	</Paragraph>
</div>
