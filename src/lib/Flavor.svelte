<script>
	const text = [
		'Flash plugin failed to load.',
		'Are you a robot?',
		'Merry Christmas.',
		'Wahoo!',
		'Moooooooo.',
		'Errrrrrrrrr...',
		'Nutella.',
		'Ella eating chair.'
	];
	const index = Math.floor(Math.random() * text.length);

	const flavorText = text[index];
</script>

<p class="text-center">{flavorText}</p>
