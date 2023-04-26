<script>
	import WorkTitle from './WorkTitle.svelte';

	export let title;
</script>

<div>
	<WorkTitle {title} />
	<slot />
</div>
