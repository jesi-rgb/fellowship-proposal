<script>
	import Fellow from '../lib/Components/Fellow.svelte';
	import Hero from '../lib/Components/Hero.svelte';
	import Link from '../lib/Components/Link.svelte';
	import WorkItem from '../lib/Components/WorkItem.svelte';
	import WorkTitle from '../lib/Components/WorkTitle.svelte';
</script>

<div class="mx-auto max-w-sm xl:max-w-xl my-20">
	<Hero text="Processing Fellowship 2023" />
	<div class="text-lg font-medium">
		<p>
			Hi! We are Greg and Jesús, two developers eager to participate in <Link
				link="https://processingfoundation.org/fellowships"
				text="2023's Processing Fellowship"
			/>.
		</p>
		<p>
			We present here our work as well as our proposal, consisting of a mathematical engine built on
			top of <Link text="p5.js" link="https://p5js.org/" />
		</p>
	</div>

	<div class="my-10 max-w-md flex-col space-y-32">
		<Fellow
			name="Greg"
			bio="I’m a professional math tutor and a YouTuber. My long-term ambition is to share my education online with learners around the world, for free. Over the last decade, I’ve created YouTube videos, a mathematical visualization library, and curricula informed by my tutoring practice. I plan to turn all of this into a full-time career based on crowdfunding donations."
		>
			<div class="flex-col space-y-3">
				<WorkItem title={'Graphing Calculator'}>
					<iframe
						height="500px"
						class="w-full"
						src="https://editor.p5js.org/highermathnotes/full/Up0ONQ9dE"
					/>
				</WorkItem>
			</div>
		</Fellow>
		<Fellow name="Jesús" bio="I am a mathematical animator, web developer and designer." />
	</div>
</div>
