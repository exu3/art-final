<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Project</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p>main body here</p>
		<img src="https://github.com/eilla1.png" alt="hi" />
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

	.text-center {
		text-align: center;
	}
</style>
