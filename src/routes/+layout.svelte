<script>
	import '../app.css';
	import Footer from '../lib/Components/Footer.svelte';
	import Header from '../lib/Components/Header.svelte';
</script>

<div class="mx-auto max-w-sm xl:max-w-screen-lg my-20">
	<Header />
	<slot />
	<Footer />
</div>
