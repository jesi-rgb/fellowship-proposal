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
		We want to solve an accessibility problem: math learners and educators are the most likely to
		benefit from software libraries for mathematical visualization, but no existing library is
		accessible to them.

		<br /><br />
		Basic mathematical visualizations often require an intimidating amount of programming, even with
		a beginner-friendly library like p5.js.

		<br /><br />
		In Python, Manim has recently become a popular solution, and for good reason. Owing to its gorgeous
		visualizations, it has been called the gold standard of mathematical animation.

		<br /><br />
		Unfortunately, Manim users must have access to a machine on which they can install software. They
		must be ready to implement a difficult installation process. They must know how to use the command
		line and be familiar with object-oriented programming. All this is required to draw a circle.
	</Paragraph>

	<Heading>The solution</Heading>
	<Paragraph>
		Like the Quickstart tutorial for Manim, the Get Started guide for p5.js also teaches users how
		to draw a circle. The difference in accessibility is night and day!

		<br /><br />
		So, our solution is to extend p5.js with an add-on library for mathematical visualizations. It should
		be as capable as Manim, but beginner friendly, and built for the web.

		<br /><br />
		We have <b>three</b> design priorities:
		<br /><br />

		<ul class="list-disc">
			<li>
				<b>Accessibility</b>: It must be easy for total beginners to use in the browser, with no
				setup.
			</li>

			<li><b>Interactivity</b>: It must be easy to make visualizations interactive!</li>
			<li><b>Expressiveness</b>: It must be easy to create custom aesthetics.</li>
		</ul>

		<br />
		Based on the overwhelming <Link
			text="response on Twitter"
			link="https://twitter.com/HigherMathNotes/status/1638652022022115328"
		/>, we know we’re on the right track!
	</Paragraph>

	<Heading>FAQ</Heading>
	<Paragraph>
		<ul class="list-decimal">
			<li>
				<p class="font-medium text-2xl text-pink-600 my-9">
					What will Mathemagical.js do that <b>Geogebra</b> or <b>Desmos</b> can't?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						We’ll build Mathemagical.js on a technology called p5.js, which is designed not only for
						learners and educators, but also visual artists. By extension, Mathemagical.js will
						support a high degree of aesthetic customization out of the box.

						<br />
						<i class="font-light"
							>(Creators using tools like Geogebra can
							<Link
								text="run into limitations"
								link="https://www.mathemaniac.co.uk/blog/how-i-use-geogebra-to-make-animations-in-videos-part-i"
							/></i
						>)
					</li>
					<li>
						We also aim to make Mathemagical.js more performant than Geogebra is on the web (e.g.
						compare
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
					How will Mathemagical.js compare to <b>Manim</b>?
				</p>
				<ul class="list-disc list-inside space-y-4">
					<li>
						Manim is powerful, and it’s popular among technical content creators. Built in Python,
						it offers nice, sensible defaults without compromising extensibility. Nevertheless, it’s
						<b>quite difficult to install</b>, it’s a heavy program to run, and it’s not easy for
						beginners to use.
					</li>
					<li>
						Our idea is to <b>bring the best of Manim to the web</b>, with zero installation and a
						much softer learning curve. We’ll do this by building on p5.js, which is built for the
						web and enables immediate web integration, sharing, and exciting opportunities for
						interactivity, a core element for math learning.
					</li>
				</ul>
			</li>
		</ul>
	</Paragraph>
</div>
