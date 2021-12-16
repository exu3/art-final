<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Animorph</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece is a morph of multiple animals including a camel, dinosaur, and cat. The ears are
			that of a cat; the neck is that of a sauropod; and the body is that of a camel. This piece was
			created in Photoshop using various blending tools and layer masks.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/animorph_project/animal_camel_EX.jpg?token=ARIDILFRRIA2CIRUCMUQ7F3BYQU32"
			alt="A camel, dinosaur, and cat morphed into one animal."
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
