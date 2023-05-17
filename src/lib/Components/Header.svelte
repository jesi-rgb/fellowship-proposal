<script>
	import { Handshake, House, MicrophoneStage, NotePencil, Translate } from 'phosphor-svelte';
</script>

<div class="flex flex-row justify-between">
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/en"
	>
		<House weight="regular" class="group-hover:scale-110 transition-transform" />
		<p class="hidden xl:block">Home</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/en/proposal"
	>
		<NotePencil weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Proposal</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/en/portfolio"
	>
		<Handshake weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Portfolio</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="https://docs.google.com/forms/d/e/1FAIpQLScmVUW9doOZlzCN7k-P5XqKIGUIx_tWplqUySZSneT7IelDKA/viewform?usp=share_link"
	>
		<MicrophoneStage weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Community form</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/es"
	>
		<Translate weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Español</p>
	</a>
</div>
