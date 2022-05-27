<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Restaurant T-shirt</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This t-shirt design was created as a part of the Restaurant Rebrand project. It reflects a
			minimalist design with the basic logo on the right chest in the front and the full logo
			centered on the back. The gold and navy colors complement each other to create a neat visual
			appeal.
		</p>
		<img src="/sem2/wahooshirt.png" alt="Gold t-shirt with a navy blue emblem" />
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
