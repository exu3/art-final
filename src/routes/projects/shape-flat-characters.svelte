<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Shape Flat Characters</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece was created in Illustrator. It is a flat cartoon character created with only the
			shapes and the pathfinder tool. This was challenging, but I learned a lot about how basic
			shapes can tell a story.
		</p>
		<img src="/sem2/shapechar1.png" alt="Illustrated person making a face" />
		<img src="/sem2/shapechar2.png" alt="Illustrated person making a face" />
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
