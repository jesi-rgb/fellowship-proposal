<script>
	import { onMount } from 'svelte';

	// this just makes sure that the first time we come
	// to the page we are redirected to the english version
	onMount(() => (window.location.href = '/en'));
</script>
