<script>
	import { Handshake, House, MicrophoneStage, NotePencil } from 'phosphor-svelte';
</script>

<div class="flex flex-row space-x-6 justify-around">
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/"
	>
		<House weight="bold" class="group-hover:scale-110 transition-transform" />
		<p class="hidden xl:block">Home</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/proposal"
	>
		<NotePencil weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Proposal</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="/about"
	>
		<Handshake weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Our Work</p>
	</a>
	<a
		class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors"
		href="https://docs.google.com/forms/d/e/1FAIpQLScmVUW9doOZlzCN7k-P5XqKIGUIx_tWplqUySZSneT7IelDKA/viewform?usp=share_link"
	>
		<MicrophoneStage weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Community Form</p>
	</a>
</div>
