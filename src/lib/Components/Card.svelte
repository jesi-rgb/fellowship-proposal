<script>
	import { NotePencil } from 'phosphor-svelte';
	import Paragraph from './Paragraph.svelte';

	export let title;
	export let link;
</script>

<a
	class="group xl:w-1/3 relative p-3 hover:shadow-pink-600/10 hover:shadow-xl hover:-translate-y-1 rounded-xl transition-all"
	href={link}
>
	<div class="tracking-tight font-bold text-center text-3xl text-pink-600">{title}</div>
	<div
		class="absolute opacity-5 -top-10 right-10 group-hover:rotate-12 transition-all duration-500 -rotate-12 text-pink-600"
	>
		<slot name="icon" />
	</div>
	<Paragraph>
		<slot name="content" />
	</Paragraph>
</a>
