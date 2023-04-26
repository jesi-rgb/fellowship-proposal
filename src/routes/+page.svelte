<script>
	import Fellow from '../lib/Components/Fellow.svelte';
	import Hero from '../lib/Components/Hero.svelte';
	import Link from '../lib/Components/Link.svelte';
	import WorkItem from '../lib/Components/WorkItem.svelte';
</script>

<div class="mx-auto max-w-sm xl:max-w-xl my-20">
	<Hero text="Processing Fellowship 2023" />
	<div class="text-lg font-medium">
		<p>
			Hi! We are Greg and Jesús, two developers based in Denver, CO and Jaén, Spain, eager to
			participate in <Link
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
			<div class="flex-col space-y-10">
				<WorkItem title="Graphing Calculator">
					<iframe
						title="graphing calc"
						height="500px"
						class="w-full"
						src="https://editor.p5js.org/highermathnotes/full/Up0ONQ9dE"
					/>
				</WorkItem>

				<WorkItem
					title="Fish in water"
					link="https://www.khanacademy.org/computer-programming/spin-off-of-project-animal-attack/5961848678645760"
				/>
				<WorkItem
					title="Normal Distribution"
					link="https://www.khanacademy.org/computer-programming/interactive-normal-distribution/6221313412710400"
				/>

				<WorkItem
					title="Spiral Animator"
					link="https://www.khanacademy.org/computer-programming/spiral-animator/5291927036985344"
				/>

				<WorkItem
					title="Visual ODE Demo"
					link="https://www.khanacademy.org/computer-programming/visualode-demo/6127327220629504"
				/>

				<WorkItem
					title="Eccentricity of conic sections"
					link="https://www.khanacademy.org/computer-programming/eccentricity-of-conic-sections-interactive/6491492594040832"
				/>

				<WorkItem
					title="Degenerate Hyperbola"
					link="https://www.khanacademy.org/computer-programming/degenerate-hyperbola-interactive/5729571474915328"
				/>

				<WorkItem
					title="Logo animation featuring cycloid"
					link="https://www.khanacademy.org/computer-programming/spin-off-of-project-ad-design/6473163029282816"
				/>

				<WorkItem
					title="Numerical Differentiation"
					link="https://www.khanacademy.org/computer-programming/numerical-differentiation-applet/4587401748643840"
				/>
				<WorkItem
					title="Log spiral arc length reparameterization"
					link="https://www.khanacademy.org/computer-programming/log-spiral-arc-length-reparametrization-spin-off/5908979894534144"
				/>
				<WorkItem
					title="Implicit curve animator"
					link="https://www.khanacademy.org/computer-programming/implicit-curve-animator-with-tangents/4886044829777920"
				/>
			</div>
		</Fellow>
		<Fellow name="Jesús" bio="I am a mathematical animator, web developer and designer." />
	</div>
</div>
