<script>
	import { Hourglass, Intersect, MicrophoneStage, NotePencil } from 'phosphor-svelte';
	import Hero from '../lib/Components/Hero.svelte';
	import Link from '../lib/Components/Link.svelte';
	import Page from '../lib/Components/Page.svelte';
	import Paragraph from '../lib/Components/Paragraph.svelte';
</script>

<svelte:head>
	<title>Processing Fellowship 2023</title>
</svelte:head>

<Page id="Intro" navigateTo="Proposal" navigationArrow={true}>
	<Hero text="Processing Fellowship 2023" />
	<Paragraph>
		<p>
			Hi! We are <span class="font-bold">Greg</span> and <span class="font-bold">Jesús</span>, two
			developers based in Denver, CO and Jaén, Spain, eager to participate in <Link
				link="https://processingfoundation.org/fellowships"
				text="2023's Processing Fellowship"
			/>.
		</p>
		<br />
		<p>
			We present here our work as well as our proposal, consisting of a mathematical engine built on
			top of <Link text="p5.js" link="https://p5js.org/" />
		</p>
		<br />
	</Paragraph>
</Page>

<Page id="Proposal">
	<Hero text="Our Proposal" />
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
		</Paragraph>
		<br />
	</div>
</Page>

<Page>
	<Hero text="About us" />

	<div class="font-bold text-pink-600 text-3xl">Greg</div>
	<Paragraph>
		I’m a professional math tutor, a YouTuber, and a programmer. I built an early version of
		Mathemagical.js called visualODE. As a Wikimedia Foundation grantee, I created a wiki and a
		community of math educators for Eventmath (in collaboration with Dr. Brendan Sullivan). I also
		created the website for my Higher Math Help service, where I have tutored for fifteen years. My
		long-term ambition is to share my education online with learners around the world, for free.
	</Paragraph>
	<div class="font-bold text-pink-600 text-3xl">Jesús</div>
	<Paragraph>
		I’m a professional content creator, specializing in computer science, graphic design and
		procedural animation. My Manim animations have appeared in some of the most popular math videos
		on all of YouTube; they’ve been viewed over 60 million times! I also engineered native GIF
		exports for p5.js, so I know a thing or two about sharing animations on the web. Oh, and I build
		websites, so I’ll make sure Mathemagical.js has a good home on the web, with beginner friendly
		demos and docs.
	</Paragraph>
</Page>

<Page>
	<Hero text="Learn more" />

	<div class="flex flex-col xl:flex-row items-start justify-evenly gap-10 mt-20">
		<div class="xl:w-1/3 relative p-3 shadow-pink-600/10 shadow-xl rounded-xl">
			<div class="font-bold text-center text-3xl text-pink-600">Proposal Page</div>
			<div class="absolute opacity-5 -top-10 right-10 rotate-12 text-pink-600">
				<NotePencil size={200} />
			</div>
			<Paragraph>
				You can check out <Link text="our proposal page" link="/proposal" /> for more details and an
				FAQ that we’ll update based on questions from the community.
			</Paragraph>
		</div>
		<div class="xl:w-1/3 relative p-3 shadow-pink-600/10 shadow-xl rounded-xl">
			<div class="font-bold text-center text-3xl text-pink-600">Joint portfolio</div>
			<div class="absolute opacity-5 -top-10 right-10 -rotate-45 text-pink-600">
				<Intersect size={200} />
			</div>
			<Paragraph>
				You can take a gander at <Link text="our joint portfolio" link="/about" />, to see some of
				the cool stuff we’ve made.
			</Paragraph>
		</div>
		<div class="xl:w-1/3 relative p-3 shadow-pink-600/10 shadow-xl rounded-xl">
			<div class="font-bold text-center text-3xl text-pink-600">Community Form</div>
			<div class="absolute opacity-5 -top-10 right-10 -rotate-90 text-pink-600">
				<MicrophoneStage size={200} />
			</div>
			<Paragraph>
				If you’re interested in this project, please let us know by filling out our [community
				form](URL to Google form)! We’ll keep you updated.
			</Paragraph>
		</div>
	</div>
</Page>
