<script>
	import { Handshake, House, MicrophoneStage, NotePencil } from 'phosphor-svelte';
</script>

<div class="flex flex-row justify-between">
	<a
		class="flex items-center space-x-2 text-3xl group hover:text-pink-600 transition-colors"
		href="/"
	>
		<House weight="regular" class="group-hover:scale-110 transition-transform" />
		<p class="hidden xl:block">Inicio</p>
	</a>
	<a
		class="flex items-center space-x-2 text-3xl group hover:text-pink-600 transition-colors"
		href="/proposal"
	>
		<NotePencil weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Propuesta</p>
	</a>
	<a
		class="flex items-center space-x-2 text-3xl group hover:text-pink-600 transition-colors"
		href="/portfolio"
	>
		<Handshake weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Portafolio</p>
	</a>
	<a
		class="flex items-center space-x-2 text-3xl group hover:text-pink-600 transition-colors"
		href="https://docs.google.com/forms/d/e/1FAIpQLScmVUW9doOZlzCN7k-P5XqKIGUIx_tWplqUySZSneT7IelDKA/viewform?usp=share_link"
	>
		<MicrophoneStage weight="regular" class="group-hover:rotate-12 transition-transform" />
		<p class="hidden xl:block">Formulario comunitario</p>
	</a>
</div>
