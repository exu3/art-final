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
			good time. Feel free to leave a message in the guestbook if you wish.
		</p>
		<h2>What I've learned</h2>
		<p class="copy">I don't remember.</p>
		<h2>Facts</h2>
		<ul>
			<li>I am a person!</li>
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
</style>
