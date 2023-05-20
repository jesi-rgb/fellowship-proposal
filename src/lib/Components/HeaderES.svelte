<script>
	import { Handshake, House, MicrophoneStage, NotePencil, Translate } from 'phosphor-svelte';
	import HeaderLink from './HeaderLink.svelte';
</script>

<div class="flex flex-row justify-evenly md:justify-between">
	<HeaderLink link="/es" text="Inicio">
		<House slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink link="/es/proposal" text="Propuesta">
		<NotePencil slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink link="/es/portfolio" text="Portafolio">
		<Handshake slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink
		link="https://docs.google.com/forms/d/e/1FAIpQLSeaUbq5oLIuehUUCnKRd-mwHx1B8E5Ml6s6DAXXNZ0XMhHLiw/viewform?hl=es"
		text="Formulario de la comunidad"
	>
		<MicrophoneStage
			slot="icon"
			weight="regular"
			class="group-hover:rotate-12 transition-transform"
		/>
	</HeaderLink>

	<HeaderLink link="/en" text="English">
		<Translate slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>
</div>
