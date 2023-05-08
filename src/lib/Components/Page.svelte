<script>
	import { fly } from 'svelte/transition';
	import { onMount } from 'svelte';

	import { cubicInOut } from 'svelte/easing';
	let visible = false;

	onMount(() => {
		visible = true;
	});
</script>

<div class="my-20 relative">
	{#if visible}
		<div in:fly={{ y: 20, duration: 1000, easing: cubicInOut }}>
			<slot />
		</div>
	{/if}
</div>
