<script>
	import { onMount } from 'svelte';
	import { MetaTags } from 'svelte-meta-tags';

	// this just makes sure that the first time we come
	// to the page we are redirected to the english version
	onMount(() => (window.location.href = '/en'));
</script>

<MetaTags
	title="Mathemagical.js"
	description="Mathemagical.js is a proposed p5.js library for making web-based mathematical figures, animations, and interactives in 2D and 3D. Designed for learners, educators, and creators, it will be easy enough for beginners and flexible enough for experts."
	canonical="https://fellowship-proposal.vercel.app/en"
	twitter={{
		handle: '@HigherMathNotes',
		cardType: 'summary_large_image',
		title: 'Mathemagical.js',
		description:
			'Mathemagical.js is a proposed p5.js library for making web-based mathematical figures, animations, and interactives in 2D and 3D. Designed for learners, educators, and creators, it will be easy enough for beginners and flexible enough for experts.'
	}}
	openGraph={{
		url: 'https://fellowship-proposal.vercel.app/en',
		title: 'Mathemagical.js',
		description: 'Landing page for Mathemagical.js proposal website.',
		images: [{ url: 'https://fellowship-proposal.vercel.app/og_image.png' }],
		site_name: 'Mathemagical.js'
	}}
	additionalLinkTags={[
		{
			rel: 'alternate',
			href: 'https://fellowship-proposal.vercel.app/en'
		},
		{
			rel: 'alternate',
			href: 'https://fellowship-proposal.vercel.app/es'
		}
	]}
/>
