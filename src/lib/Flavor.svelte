<script>
	const text = [
		'Flash plugin failed to load.',
		'Are you a robot?',
		'This website is open source!',
		'✨ 🦕',
		'The ducks at the park are free.',
		'Get dinoed lol.',
		'Life is hard, life is stressful',
		'I need peace and tranquility',
		'dinosaurbbq.org',
		'No one is around to help',
		'Hack yeah.'
	];
	const index = Math.floor(Math.random() * text.length);

	const flavorText = text[index];
</script>

<p class="text-center"><em>{flavorText}</em></p>
