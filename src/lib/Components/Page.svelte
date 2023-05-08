<script>
	import { onMount } from 'svelte';
	import ArrowScroll from './ArrowScroll.svelte';
	import { fly } from 'svelte/transition';

	import { cubicInOut } from 'svelte/easing';
	export let id;
	export let navigateTo = undefined;
	export let navigationArrow = false;

	let visible = false;

	onMount(() => {
		visible = true;
	});
</script>

<div {id} class="my-20 relative">
	{#if visible}
		<div in:fly={{ y: 150, duration: 1000, easing: cubicInOut }}>
			<slot />
		</div>
	{/if}
	{#if navigationArrow}
		<ArrowScroll {navigateTo} />
	{/if}
</div>
