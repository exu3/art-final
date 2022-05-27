<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Restaurant Logo</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This logo was created in Illustrator as a part of the Restaurant Rebrand project. Prior to
			creating this design, I made several other logos as a proof-of-concept. This logo was created
			using the Pen tool in Illustrator juxtaposed with the <a
				href="https://github.com/exu3/wack-club-sans">Wack Club Sans font</a
			>.
		</p>
		<img src="/sem2/logo.png" alt="Wahoo's Fish Taco logo" />
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
