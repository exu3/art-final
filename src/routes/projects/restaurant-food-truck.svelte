<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Restaurant Food Truck</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece was created as a part of the Restaurant Rebrand project. It is a Food Truck design
			that uses the other elements in the branding package—colors, fonts, and logos. The bright
			colors are meant to make the truck stand out.
		</p>
		<img src="/sem2/foodtruck.png" alt="Food truck illustration" />
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
