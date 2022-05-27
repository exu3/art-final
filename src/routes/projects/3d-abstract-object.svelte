<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>3D Abstract Object</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece was created in Photoshop using the 3D Object tooling. It features a combination of
			colors combined into an abstract shape. To add to the 3D effect, there is also a shadow in the
			background.
		</p>
		<img src="/sem2/3dshape.png" alt="3-dimensional colorful shape" />
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
