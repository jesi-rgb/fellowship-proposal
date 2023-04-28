<script>
	import { Quotes } from 'phosphor-svelte';
	import Paragraph from './Paragraph.svelte';
	import Heading from './Heading.svelte';
	export let name;
	export let bio;
</script>

<div>
	<div class="text-pink-600">
		<Heading>{name}</Heading>
	</div>
	<div class="flex flex-row mb-10">
		<div class="relative">
			<Quotes
				weight="fill"
				size="90"
				class="absolute -right-10 -top-10 text-pink-600 opacity-20 text-3xl"
			/>
			<Paragraph>
				{bio}
			</Paragraph>
		</div>
	</div>

	<Heading>Work</Heading>
	<slot />
</div>
