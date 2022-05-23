<script>
	import Flavor from '../lib/Flavor.svelte';
</script>

<main>
	<h1>Howdy. I'm Ella.</h1>
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
			You are here probably here because you are a robot or happen to be grading my project. While
			you're here, I hope you have a good time. Feel free to leave a message in the <a
				href="https://ella.cx/book"
				target="_blank">guestbook</a
			> if you wish.
		</p>
		<h2>Learnings</h2>
		<ol class="copy">
			<li>Three key concepts you learned during this semester in Digital Art (5 points)</li>
			<li>min 2 sentences each</li>
			<li>min 2 sentences each</li>
			<li>min 2 sentences each</li>
		</ol>
		<p class="copy">This was my favorite project from the semester:</p>
		<img
			class="drawing"
			src="https://user-images.githubusercontent.com/72365100/146421645-6b00e5ff-5721-44e0-a341-78d7a3858076.png"
			alt="hi"
		/>

		<h2>Post high school goals in art</h2>
		<ol class="copy">
			<li>minimum of three goals</li>
			<li>minimum of three goals</li>
			<li>minimum of three goals</li>
		</ol>
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
