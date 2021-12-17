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
			You are here because you are either Ms. LaDuca, a student at FHS, Hack Clubber, or random
			person on the internet who has stumbled upon my website. While you're here, I hope you have a
			good time. Feel free to leave a message in the <a
				href="https://uwu.boats/guestbook"
				target="_blank">guestbook</a
			> if you wish.
		</p>
		<h2>What I've learned</h2>
		<p class="copy">I don't remember.</p>
		<p class="copy">My favorite project this semester was this.</p>
		<h2>S2 Goals</h2>
		<ol class="copy">
			<li>My goal yeah.</li>
			<li>Other goal yeah.</li>
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
				<a href="https://hack.af/zephyr" target="_blank">ZephyrNET</a>, a 60-pound physical server
				we build our own internet on.
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
					href="https://cloud-jb6z79ny8-hack-club-bot.vercel.app/0ezgif-5-42c1267663.gif">lights</a
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

	img {
		width: 20%;
		margin: 0 auto;
		border-radius: 100%;
		border: 2px solid gray;
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
