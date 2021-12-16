<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Fake ID Badge</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece is a [fake] ID badge representing an organization and position of choice. This
			project was designed in Adobe Photoshop, and it was my first time using the software. I
			labeled myself as a Dino Connisseur because I am a maintainer of a large <a
				href="https://hack.af/dino"
			>
				open-source repository of dinosaurs</a
			>.
		</p>
		<img
			src="https://user-images.githubusercontent.com/72365100/146411714-6d3395c1-89ea-4e36-a001-8bc39c1e30a0.png"
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
