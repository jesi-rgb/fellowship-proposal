<script>
	import { onMount } from 'svelte';
	import { fly } from 'svelte/transition';
	import '../../app.css';
	import Footer from '$lib/Components/FooterES.svelte';
	import Header from '$lib/Components/HeaderES.svelte';
	import { MetaTags } from 'svelte-meta-tags';

	let visible = false;

	onMount(() => {
		visible = true;
	});
</script>

<MetaTags
	title="Mathemagical.js"
	description="Mathemagical.js es una propuesta para construir una librería de figuras, animaciones y sistemas interactivos matemáticos basados en tecnología web."
	canonical="https://fellowship-proposal.vercel.app/"
	twitter={{
		handle: '@HigherMathNotes',
		cardType: 'summary_large_image',
		title: 'Mathemagical.js',
		description:
			'Mathemagical.js es una propuesta para construir una librería de figuras, animaciones y sistemas interactivos matemáticos basados en tecnología web.'
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

<!-- this will make it so that the webpage flies in on load, but only the first time -->
<div
	class="mx-auto selection:bg-pink-600 selection:text-white max-w-xs sm:max-w-sm md:max-w-md xl:max-w-screen-lg my-20"
>
	<Header />
	{#if visible}
		<div in:fly={{ y: 20, duration: 1000 }}>
			<slot />
		</div>
	{/if}
	<Footer />
</div>
