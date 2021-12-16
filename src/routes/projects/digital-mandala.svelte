<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Digital Mandala</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p>main body here</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/mandala/Mandala2.jpg?token=ARIDILDP2NLYOMO22UGZ5T3BYSTLY"
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
