<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Free Project</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			For my free project, I chose to design stickers. I am an avid fan of stickers and regularly
			exchange stickers with friends through the mail. The 1st sticker resembles the DuckDuckDuckGo
			logo but uses a Dinosaur instead of a duck. The second logo is a play on the old MasterCard
			logo.
		</p>
		<img src="/sem2/hackhackclub.png" alt="Duck duck go logo but modified" />
		<img src="/sem2/mastercardsticker.png" alt="Mastercard logo but modified" />
	</article>
	<hr />
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
		width: 100%;
		margin: 0 auto;
	}
</style>
