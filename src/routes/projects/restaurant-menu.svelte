<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Restaurant Menu</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece was created as a part of the Restaurant Rebrand project. Side note that I did not
			fully complete this project, so the design below is just the Kids Menu portion of the project.
			The background features a kaleidoscopic pattern of dinosaurs and fish. The body font is
			Franuces, and the headings use the logo font, Wack Club Sans.
		</p>
		<img src="/sem2/menu.png" alt="Restaurant Menu" />
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
