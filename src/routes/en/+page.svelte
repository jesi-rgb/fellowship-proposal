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
	<Heading>Proposal for the Processing Fellowship 2023</Heading>
	<Paragraph>
		<p>
			Hi! We are <span class="font-bold">Greg</span> and <span class="font-bold">Jesús</span>, two
			developers based in Denver, CO and Jaén, Spain, eager to participate in <Link
				link="https://medium.com/@ProcessingOrg/open-call-processing-foundation-fellowship-program-462b057285"
				text="2023's Processing Fellowship"
			/>.
		</p>
		<br />
		<p>
			We aim to build a mathematical visualization library unlike any other! Here, you can learn
			about our proposal and our work.
		</p>
		<br />
	</Paragraph>
</Page>

<Page>
	<Hero text="Our proposal" />
	<div>
		<Paragraph>
			<p>
				Thanks to <Link text="Manim" link="https://www.manim.community/" /> and its stunning visualizations,
				animation has become an important medium of communication in math education.
			</p>

			<br />

			<p>
				Wouldn't it be great if learners and educators could easily program mathematical animations
				directly in the browser, share them, and interact with them?
			</p>

			<br />

			<p>
				To make this possible, we propose Mathemagical.js: a web-based tool for making mathematical
				figures, animations, and interactives in 2D and 3D. By leveraging the amazing work of the
				p5.js community, we can make it easy enough for beginners and flexible enough for experts.
			</p>

			<br />
			Here’s a demo of prototypes that illustrate some visualizations users might make:
			<br /><br />
			<iframe
				class="w-full border-2 border-pink-600 rounded-xl"
				height="315"
				src="https://www.youtube.com/embed/Br40z-lpC3o"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			/>
		</Paragraph>
	</div>
</Page>

<Page>
	<Hero text="About us" />

	<div class="mt-10 font-bold text-pink-600 text-3xl">Greg</div>
	<Paragraph>
		I’m a professional <b>math tutor</b>, a YouTuber, and a programmer. I built an early version of
		Mathemagical.js called <b>visualODE</b>. I also created the website for my Higher Math Help
		service, where I have <b>fifteen years of experience</b> working with learners one on one.

		<br />
		<br />
		As a Wikimedia Foundation grantee, I created a <b>wiki</b> and a <b>community</b> of math educators
		for Eventmath (in collaboration with Dr. Brendan Sullivan). My long-term ambition is to share my
		education online with learners around the world, for free.
	</Paragraph>
	<div class="mt-10 font-bold text-pink-600 text-3xl">Jesús</div>
	<Paragraph>
		I’m a professional <b>content creator</b>, specializing in computer science, graphic design and
		procedural animation. My Manim animations have appeared in some of the most popular math videos
		on all of YouTube; they’ve been viewed over <b>60 million times</b>!

		<br />
		<br />
		I also engineered <b>native GIF exports for p5.js</b>, so I know a thing or two about sharing
		animations on the web. I am also a web developer, so I’ll make sure Mathemagical.js has a good
		home on the web, with beginner friendly <b>demos and docs</b>.
	</Paragraph>
</Page>

<Page>
	<Hero text="Learn more" />

	<div class="flex flex-col items-stretch xl:flex-row justify-evenly gap-10 mt-20">
		<Card title="Proposal" link="/en/proposal">
			<NotePencil slot="icon" size={200} />
			<p slot="content">
				You can check this out for more details and an FAQ that we’ll update based on questions from
				the community.
			</p>
		</Card>

		<Card title="Portfolio" link="/en/portfolio">
			<Handshake slot="icon" size={200} />
			<p slot="content">
				You can take a gander at our joint portfolio, to see some of the cool stuff we’ve made.
			</p>
		</Card>

		<Card
			title="Community form"
			link="https://docs.google.com/forms/d/e/1FAIpQLScmVUW9doOZlzCN7k-P5XqKIGUIx_tWplqUySZSneT7IelDKA/viewform?usp=share_link"
		>
			<MicrophoneStage slot="icon" size={200} />
			<p slot="content">
				If you’re interested in this project, please let us know by filling out our community form!
				We’ll keep you updated.
			</p>
		</Card>
	</div>
</Page>
