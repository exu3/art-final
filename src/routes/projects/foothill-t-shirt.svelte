<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Foothill T-Shirt</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This t-shirt design was created for the Class of 2026 class shirt. It features an 8-bit style
			falcon juxtaposed with a bitmap font. Like the other t-shirt designs, it is minimalistic and
			clean.
		</p>
		<img src="/sem2/asbshirt.png" alt="T-shirt with 8bit falcon design" />
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
