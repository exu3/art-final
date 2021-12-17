<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Neuro Doodle</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece features various lines which intersect at points. At each node, the edges are
			rounded and the lines are thickened. There are also patterns of various textures in certain
			areas. In a way, this piece shows how neural networks are interconnected.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/neurodoodle/neurodoodle.jpg?token=ARIDILBMRFTG4G32XS4I4BDBYSTF6"
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
