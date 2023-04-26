<script>
	import { Link } from 'phosphor-svelte';

	export let title;
	export let link;
</script>

<div class="flex items-center space-x-1">
	<h3 class={'font-semibold my-3 text-lg ' + (link === undefined ? '' : 'underline')}>
		<a href={link}>
			{title}
		</a>
	</h3>
	{#if link !== undefined}
		<Link weight="bold" />
	{/if}
</div>
