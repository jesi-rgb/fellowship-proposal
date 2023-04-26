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

	<Hero text="Proposal" />
	<div>
		<p class="text-justify">
			We propose a mathematical engine for the web, similar to tools that are already out there like
			Manim, Desmos and alike. Building it natively for the web means unparalleled levels of
			accessibility. We believe that learning is making, and as such, we aim to provide a sensible
			and robust framework for students and teachers to build upon, making it easy for everyone to
			engage with mathematical edeavours in a computational context.
		</p>
		<br />
		<p class="text-pink-600 font-extrabold">
			Here we would add more info about the propsal I guess? Let me know what you think
		</p>
	</div>

	<Hero text="About us" />
	<div class="my-10 max-w-md flex-col space-y-32">
		<Fellow
			name="Greg"
			bio="I’m a professional math tutor and a YouTuber. My long-term ambition is to share my education online with learners around the world, for free. Over the last decade, I’ve created YouTube videos, a mathematical visualization library, and curricula informed by my tutoring practice. I plan to turn all of this into a full-time career based on crowdfunding donations."
		>
			<div class="my-5 font-medium text-justify">
				<p>
					Greg has participated extensively in the math, math education, and software communities,
					having presence in <Link
						text="Reddit"
						link="https://www.reddit.com/user/HigherMathHelp"
					/>, <Link text="Twitter" link="https://twitter.com/HigherMathNotes" /> and <Link
						text="Github"
						link="https://github.com/issues?q=is%3Aissue+commenter%3AGregStanton"
					/>, as well as having his own <Link
						text="Wikimedia page"
						link="https://meta.wikimedia.org/wiki/User:Greg_at_Higher_Math_Help"
					/>. Some of his work also includes a myriad of math examples built on top of p5.js, as
					well as <Link text="a youtube channel" link="https://www.youtube.com/c/HigherMathNotes" />
					explaining math in great detail.
				</p>
				<br />
				<p>
					Here are some examples of his work in the library <span class="font-bold">visual ODE</span
					>:
				</p>
			</div>
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
		<Fellow
			name="Jesús"
			bio="I am a freelance mathematical animator, web developer and designer. I am mainly a technical content creator, using a myriad of tools to create beautiful and engaging explainers on the internet."
		>
			<p class="my-5 font-medium text-justify">
				Jesús has mainly worked as an animator and web developer on a freelance basis. He's also
				participated in <Link
					text="GSoC'22 with the Processing Foundation"
					link="https://medium.com/@ProcessingOrg/google-summer-of-code-2022-wrap-up-post-cb64caa840f0"
				/>, helping to build <Link
					text="native GIF encoding in the p5.js ecosystem"
					link="https://www.jesirgb.com/blog/gif-encoding"
				/>. One can find more of his work as a designer and web developer throughout <Link
					text="his website"
					link="https://jesirgb.com"
				/>.
			</p>
			<br />
			<p>Here are some examples of the videos he's helped to create:</p>

			<WorkItem title="The Simplest Math Problem No One Can Solve">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/094y1Z2wpJg?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>

			<WorkItem title="The Unreasonable Effectiveness of JPEG">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/0me3guauqOU?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/></WorkItem
			>

			<WorkItem title="How PNG works">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/EFUYNoFRHQI?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="The Discrete Fourier Transform">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/yYEMxqreA10?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="The Traveling Salesman Problem">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/GiDsjIBOVoA?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
			<WorkItem title="but what are Blend Modes?">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/D7Yg4H8e7uw?controls=0"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
					allowfullscreen
				/>
			</WorkItem>
		</Fellow>
	</div>
</div>
