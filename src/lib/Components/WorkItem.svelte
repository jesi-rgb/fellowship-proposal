<script>
	import WorkTitle from './WorkTitle.svelte';

	export let title;
	export let link;
	const iframeLink =
		link +
		'/embedded?id=1682504806298-0.18545174546998788&origin=http%3A%2F%2Flocalhost%3A5173&editor=no&buttons=no&author=yes&embed=yes';
</script>

<!-- https://www.khanacademy.org/computer-programming/spin-off-of-project-animal-attack/5961848678645760/embedded?amp;origin=http%3A%2F%2Flocalhost%3A5173&amp;editor=no&amp;buttons=no&amp;author=yes&amp;embed=yes -->
<div>
	<WorkTitle {title} {link} />
	{#if link}
		<iframe
			{title}
			src={iframeLink}
			class="w-[400px] h-[400px] border-2 rounded-xl border-pink-600"
			scrolling="no"
			frameborder="0"
		/>
	{:else}
		<slot />
	{/if}
</div>
