<script>
	import { Handshake, House, MicrophoneStage, NotePencil } from 'phosphor-svelte';
</script>

<div class="flex flex-row space-x-6 justify-around">
	<a href="/">
		<div class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors">
			<House weight="bold" class="group-hover:scale-110 transition-transform" />
			<p class="hidden xl:block">Home</p>
		</div>
	</a>
	<div class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors">
		<NotePencil weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Proposal</p>
	</div>
	<div class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors">
		<Handshake weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Our Work</p>
	</div>
	<div class="flex items-center space-x-2 text-2xl group hover:text-pink-600 transition-colors">
		<MicrophoneStage weight="bold" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Community Form</p>
	</div>
</div>
