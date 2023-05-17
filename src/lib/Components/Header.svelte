<script>
	import { Handshake, House, MicrophoneStage, NotePencil, Translate } from 'phosphor-svelte';
	import HeaderLink from './HeaderLink.svelte';
</script>

<div class="flex flex-row mx-auto justify-evenly md:justify-between items-start">
	<HeaderLink link="/en" text="Home">
		<House slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink link="/en/proposal" text="Proposal">
		<NotePencil slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink link="/en/portfolio" text="Portfolio">
		<Handshake slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>

	<HeaderLink
		link="https://docs.google.com/forms/d/e/1FAIpQLScmVUW9doOZlzCN7k-P5XqKIGUIx_tWplqUySZSneT7IelDKA/viewform?usp=share_link"
		text="Community Form"
	>
		<MicrophoneStage
			slot="icon"
			weight="regular"
			class="group-hover:rotate-12 transition-transform"
		/>
	</HeaderLink>

	<HeaderLink link="/es" text="Español">
		<Translate slot="icon" weight="regular" class="group-hover:rotate-12 transition-transform" />
	</HeaderLink>
</div>
