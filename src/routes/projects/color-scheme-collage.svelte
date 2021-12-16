<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Color Scheme Collage</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece uses a triatic color scheme. It includes a digital dinosaur illustration as well as
			other textures including paper and ink. It's meant to reflect features of a postage stamp.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/color_scheme_collage/postage_riveter_dino.jpg?token=ARIDILDVIAWDXCPHLO5T7MLBYSTRA"
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
