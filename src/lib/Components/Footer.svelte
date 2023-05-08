<script>
	import { Globe, Heart } from 'phosphor-svelte';
	import Link from './Link.svelte';
	import Paragraph from './Paragraph.svelte';

	import { onMount } from 'svelte';
	import { cubicInOut } from 'svelte/easing';

	let visible = false;
	onMount(() => {
		visible = true;
	});
</script>

{#if visible}
	<div class="mt-32 border-t-2 border-pink-600">
		<div class="grid grid-cols-1 xl:grid-cols-2">
			<div class="relative flex flex-col justify-between font-light text-2xl mt-14">
				<div>
					<div
						class="text-pink-600 scale-90 xl:scale-100 absolute -left-10 -z-10 opacity-5 -rotate-12 -top-10"
					>
						<Heart weight="duotone" size="300" />
					</div>
					Built with {' '}<span class="inline-block align-middle mb-1 text-pink-600"
						><Heart weight="fill" /></span
					>
					by <Link text="Jesús Rascón" link="https://jesirgb.com" /> and <Link
						text="Greg Stanton"
						link="http://www.highermathhelp.com/"
					/>
				</div>
				<div
					class="font-bold mt-12 text-pink-600 hover:text-pink-400 transition-colors tracking-tighter text-3xl"
				>
					<a href="/">Mathemagical.js fellowship proposal</a>
				</div>
			</div>

			<div class="relative font-light text-2xl mt-14 text-left xl:text-right">
				<div
					class="text-pink-600 scale-[70%] -p-3 xl:scale-100 absolute -right-10 -z-10 opacity-5 rotate-12 -top-10"
				>
					<Globe weight="duotone" size="300" />
				</div>
				Find us over the internet<span class="inline-block align-middle mb-1"
					><Globe weight="fill" /></span
				>
				<div class="grid grid-cols-2 mt-5">
					<div>
						<div class="font-bold text-pink-600 mb-5">Greg</div>
						<ul>
							<li><Link text="Twitter" link="https://twitter.com/HigherMathNotes" /></li>
							<li><Link text="Github" link="https://github.com/GregStanton" /></li>
							<li><Link text="Youtube" link="https://www.youtube.com/c/HigherMathNotes" /></li>
							<li><Link text="Reddit" link="https://www.reddit.com/user/HigherMathHelp" /></li>
							<li>
								<Link
									text="Wikimedia"
									link="https://meta.wikimedia.org/wiki/User:Greg_at_Higher_Math_Help"
								/>
							</li>
						</ul>
					</div>
					<div>
						<div class="font-bold text-pink-600 mb-5">Jesús</div>
						<ul>
							<li><Link text="Twitter" link="https://twitter.com/jesi_rgb" /></li>
							<li><Link text="Github" link="https://github.com/jesi-rgb" /></li>
							<li><Link text="Youtube" link="https://youtube.com/@Design_bits" /></li>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</div>
{/if}
