<script>
	import { onMount } from 'svelte';
	import { fly } from 'svelte/transition';
	import '../app.css';
	import Footer from '../lib/Components/Footer.svelte';
	import Header from '../lib/Components/Header.svelte';

	let visible = false;

	onMount(() => {
		visible = true;
	});
</script>

<div class="mx-auto max-w-xs sm:max-w-sm xl:max-w-screen-lg my-20">
	<Header />
	{#if visible}
		<div in:fly={{ y: 20, duration: 1000 }}>
			<slot />
		</div>
	{/if}
	<Footer />
</div>
