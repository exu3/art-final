<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Digital Mandala</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This digital mandala is a piece created in Photoshop as an exercise for using the lasso tool.
			The original photo is a sunrise landscape taken from the back of a rail car. After creating a
			triangular segment from the original photo, the piece repeats in a circular pattern.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/mandala/Mandala2.jpg?token=ARIDILDP2NLYOMO22UGZ5T3BYSTLY"
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
