<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Animated GIF</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece is an animated GIF of a dinosaur. It is a 15-frame, looping animation of a jumping
			dinosaur. I was inspired to create this as a small feature for a livestream overlay.
		</p>
		<img
			src="https://user-images.githubusercontent.com/72365100/146412875-44a6100e-a981-45fd-9e39-39647edcf505.gif"
			alt="Animated dinosaur yay"
		/>
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
