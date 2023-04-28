<script>
	import Hero from '../lib/Components/Hero.svelte';
	import Link from '../lib/Components/Link.svelte';
	import Page from '../lib/Components/Page.svelte';
	import Paragraph from '../lib/Components/Paragraph.svelte';
</script>

<Page id="Intro" navigateTo="Proposal" navigationArrow={true}>
	<Hero text="Processing Fellowship 2023" />
	<Paragraph>
		<p>
			Hi! We are <span class="font-bold">Greg</span> and <span class="font-bold">Jesús</span>, two
			developers based in Denver, CO and Jaén, Spain, eager to participate in <Link
				link="https://processingfoundation.org/fellowships"
				text="2023's Processing Fellowship"
			/>.
		</p>
		<br />
		<p>
			We present here our work as well as our proposal, consisting of a mathematical engine built on
			top of <Link text="p5.js" link="https://p5js.org/" />
		</p>
		<br />
	</Paragraph>
</Page>

<Page id="Proposal">
	<Hero text="Proposal" />
	<div>
		<Paragraph>
			<p>
				We propose a <span class="font-bold">mathematical engine</span> for the web, similar to
				tools that are already out there like <Link
					text="Manim"
					link="https://www.manim.community/"
				/>, <Link text="Desmos" link="https://www.desmos.com/" /> and alike.
			</p>

			<br />

			<p>
				Building it natively for the web means unparalleled levels of <span
					class="font-extrabold text-pink-600">accessibility</span
				>. We believe that <b>learning is making</b>, and as such, we aim to provide a sensible and
				robust framework for students and teachers to build upon,
				<b>making it easy for everyone</b> to engage with mathematical edeavours in a computational context.
			</p>

			<br />

			Please, visit the <Link text="proposal page" link="/proposal" /> to know more!
		</Paragraph>
		<br />
	</div>
</Page>

<Hero text="About us" />
<Paragraph>
	To know more about our work, please visit the <Link text="about" link="/about" /> page.
</Paragraph>
