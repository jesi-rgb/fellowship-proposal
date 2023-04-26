<script>
	import { Quotes } from 'phosphor-svelte';
	export let name;
	export let bio;
</script>

<div>
	<h1 class="font-bold text-3xl text-pink-600 mb-5">{name}</h1>
	<div class="flex flex-row mb-10">
		<div class="relative">
			<Quotes
				weight="fill"
				size="90"
				class="absolute -right-10 -top-10 text-pink-600 opacity-20 text-3xl"
			/>
			<p class="text-justify">{bio}</p>
		</div>
	</div>

	<h2 class="font-bold text-xl">Work</h2>
	<slot />
</div>
