<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Type Object</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece primarily uses the type-area tool in Illustrator. The outline was created using the
			Pen tool and resembles the shape of a deer. In the eyes of a normal person, the text inside is
			merely gibberish, but to the Caribou Cult, it is a recruitment tactic.
		</p>
		<img src="/sem2/typeobj.png" alt="Deer" />
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
