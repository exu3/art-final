<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Tourist Map</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece was created in Illustrator. It is a map of San Francisco featuring many streets and
			landmarks. The icons and roads were outlined using the Pen tool in illustrator. The colour
			scheme was chosen to resemble natural Earth tones.
		</p>
		<img src="/sem2/touristmap.png" alt="Illustrated map of San Francisco" />
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
