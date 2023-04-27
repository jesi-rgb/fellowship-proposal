<script>
	import ArrowScroll from './ArrowScroll.svelte';
	export let id;
	export let navigateTo;
	export let navigationArrow = false;
</script>

<div {id} class="h-[70vh] mt-80 relative">
	<slot />
	{#if navigationArrow}
		<ArrowScroll {navigateTo} />
	{/if}
</div>
