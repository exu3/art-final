<script>
	const toKebabCase = (string) => {
		return string.replace(/\s+/g, '-').toLowerCase();
	};

	const projects = [
		{
			name: 'ID Badge',
			date: '9.10'
		},
		{
			name: 'Animorph',
			date: '9.21'
		},
		{
			name: 'Hand Collage',
			date: '9.28'
		},
		{
			name: 'Digital Mandala',
			date: '10.11'
		},
		{
			name: 'Color Scheme Collage',
			date: '10.12'
		},
		{
			name: 'Flat Landscape Painting',
			date: '10.22'
		},
		{
			name: 'Color Formula Character',
			date: '11.02'
		},
		{
			name: 'Animated GIF',
			date: '11.19'
		},
		{
			name: 'Neuro Doodle',
			date: '10.09'
		},
		{
			name: 'Photo Illustration',
			date: '12.03'
		}
	];
</script>

<table>
	<thead>
		<tr>
			<th class="text-left">Project</th>
			<th class="text-right">Date (Year 2021)</th>
		</tr>
	</thead>
	<tbody>
		{#each projects as p}
			<tr>
				<td class="project-name"><a href="projects/{toKebabCase(p.name)}">{p.name}</a></td>
				<td class="project-date">{p.date}</td>
			</tr>
		{/each}
	</tbody>
</table>

<style>
	table {
		width: 100%;
		border-color: black;
	}
	.text-left {
		text-align: left;
	}
	.text-right {
		text-align: right;
	}
	.project-date {
		text-align: right;
	}
</style>
