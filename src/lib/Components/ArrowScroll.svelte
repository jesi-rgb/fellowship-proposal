<script>
	import { ArrowDown } from 'phosphor-svelte';
	export let navigateTo = undefined;
</script>

<div
	class="animate-bounce absolute right-1/2 bottom-[100px]"
	on:click={() =>
		document.getElementById(navigateTo).scrollIntoView(false, { behaviour: 'smooth' })}
>
	<ArrowDown weight="bold" size="20" />
</div>
