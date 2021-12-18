<script>
	import Flavor from '../lib/Flavor.svelte';
</script>

<main>
	<h1>\o I'm Ella.</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<div class="flex intro">
			<img
				src="https://cloud-hvd4ca9hs-hack-club-bot.vercel.app/0image_from_ios.png"
				alt="A digital illustration of a person"
				class="pfp"
			/>
			<p class="ml-3 copy">Hi. I'm Ella, a senior at Foothill High School and maker of things.</p>
		</div>
		<span class="heading">About me</span>
		<p class="copy">
			My work samples a variety of art styles but is concentrated in digital mediums. I love to
			create interactive web experiences that are memorable, fun, and usable. I work with digital
			mediums for the freedom, accessibility, and powerful platform that the web provides. The
			concept of open source is hackable by design which makes it a perfect medium for exploring the
			intersection of design and usability.
		</p>
		<h2>About you</h2>
		<p class="copy">
			You are here because you are either my teacher, a student at FHS, Hack Clubber, or random
			person on the internet who has stumbled upon my website. While you're here, I hope you have a
			good time. Feel free to leave a message in the <a
				href="https://uwu.boats/guestbook"
				target="_blank">guestbook</a
			> if you wish.
		</p>
		<h2>Learnings</h2>
		<ol class="copy">
			<li>
				This semester, I learned about the fundamental elements of art which include line, shape,
				form, texture, color, value, space, among others. Through weekly art evaluations and
				prompted art projects, we thoroughly analyzed and gained hands-on experience with these
				concepts.
			</li>
			<li>
				I also learned the basics the most commonly used tools in Adobe Photoshop. From GIFs to
				digital illustrations to photo edits, all the class projects I created this semester
				utilized Photoshop in some way or another.
			</li>
			<li>
				One important concept I took away from this was the idea of color schemes. I learned how
				color choice affects the mood of the piece. I also learned the names and styles of various
				color schemes including monochromatic, triatic, analagous, complementary, among others.
			</li>
		</ol>
		<p class="copy">
			My favorite project this semester was the character illustration because it was the first
			project where we had a lot of freedom to create something that was original.
		</p>
		<details>
			<summary>I drew a dinosaur on a broom.</summary><br />
			<img
				class="drawing"
				src="https://user-images.githubusercontent.com/72365100/146421645-6b00e5ff-5721-44e0-a341-78d7a3858076.png"
				alt="hi"
			/>
		</details>

		<h2>S2 Goals</h2>
		<ol class="copy">
			<li>
				Next semester, I hope to further explore mediums of digital art such as typeface design,
				illustration, and 3D modeling. I've always wanted to learn Blender or try my hand at writing
				a shader. As a self-proclaimed avid typography nerd, I would love to gain hands-on
				experience by designing a custom font.
			</li>
			<li>
				I would like to become a better storyteller with my art. This includes making concious
				color, font, and design choices to convey a message.
			</li>
		</ol>
		<h2>Random Facts, I guess</h2>
		<ul class="copy">
			<li>
				I was born and raised in Pleasanton, and I've lived in the same house for all my life so
				far.
			</li>
			<li>
				I am a web designer-developer by trade. Some websites I've worked on in the past are <a
					href="https://hackclub.com/bank"
					target="_blank"
				>
					Hack Club Bank</a
				>,
				<a href="https://givebutter.com/fiscal-sponsorship" target="_blank"
					>Givebutter (fiscal sponsorship)</a
				>, and the
				<a href="https://foundation.dogecoin.com" target="_blank">Dogecoin Foundation</a>.
			</li>
			<li>
				Last summer (2021), I went on a train across America from Burlington, Vermont to SpaceX in
				Southern California known as the <a href="https://hack.af/zephyrdoc" target="_blank"
					>Hacker Zephyr</a
				>
				with a group of 42 high school students from around the world. On the train, we collectively
				built and shipped over 500 projects which live on the
				<a href="https://hack.af/zn" target="_blank">ZephyrNET</a>, a 60-pound physical server we
				build our own internet on.
			</li>
			<li>
				I love to send physical mail to people, especially <a
					href="https://hackclub.com/stickers"
					target="_blank">stickers</a
				> :D
			</li>
			<li>
				Last November (2021), I helped organize CodeDay Bay Area, a 24-hour, in-person coding event
				which was held in Pleasanton!
			</li>
			<li>
				I actively contribute to open source on <a href="https://github.com/eilla1" target="_blank"
					>GitHub</a
				>.
			</li>
			<li>
				I like to play with colorful <a
					href="https://cloud-jb6z79ny8-hack-club-bot.vercel.app/0ezgif-5-42c1267663.gif"
					target="_blank">lights</a
				>.
			</li>
			<li>
				I worked as a farm hand in summer (2019) on a small organic vegetable farm in Sunol, CA. It
				was a blast, but also tiring.
			</li>
			<li>I enjoy drawing dinosaurs and ducks.</li>
			<li>After high school, I plan to pursue higher education. I'm not sure where yet.</li>
		</ul>
	</article>
	<p class="text-center">******** END ********</p>
	<hr />
	<Flavor />
</main>

<style>
	main {
		padding: 1em;
		max-width: 450px;
		margin: 0 auto;
	}
	h1 {
		text-transform: uppercase;
		font-size: 1.5em;
		font-family: 'Merchant Copy Wide', 'Merchant Copy';
		text-align: center;
	}

	.pfp {
		width: 20%;
		margin: 0 auto;
		border-radius: 100%;
		border: 2px solid gray;
	}

	.drawing {
		width: 50%;
	}

	.flex {
		display: flex;
		flex-direction: row;
	}

	.intro {
		padding-bottom: 20px;
	}

	.heading {
		font-weight: bold;
		font-size: 1.5em;
	}

	.ml-3 {
		margin-left: 1em;
	}

	.copy {
		line-height: 1em;
	}

	li {
		padding-bottom: 12px;
	}
</style>
