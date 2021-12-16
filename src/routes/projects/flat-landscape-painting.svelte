<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Flat Landscape Painting</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This project uses a monochromatic color scheme. It is a combination of mountain layers created
			using the lasso and fill tools.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/flat_landscape_painting/landscape.jpg?token=ARIDILFG6H4QXJLY52PLOQDBYSS76"
			alt="hi"
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
