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

	// Project list
	// 	3D Abstract object
	// Shape Flat Characters
	// Tourist Map
	// Type Objet
	// Restaurant Logo/mark
	// Restaurant Tshirt - one design
	// Restaurant Menu
	// Restaurant Food Truck design both sides
	// FOothill T-Shirt Design - favorite one out of two
	// Free Project
	// Extra credit: any art pieces from outside of classs

	const projects2 = [
		{
			name: '3D Abstract Object',
			date: '1.20'
		},
		{
			name: 'Shape Flat Characters',
			date: '2.04'
		},
		{
			name: 'Tourist Map',
			date: '2.16'
		},
		{
			name: 'Type Object',
			date: '3.04'
		},
		{
			name: 'Restaurant Logo',
			date: '3.25'
		},
		{
			name: 'Restaurant T-shirt',
			date: '4.01'
		},
		{
			name: 'Restaurant Menu',
			date: '5.03'
		},
		{
			name: 'Restaurant Food Truck',
			date: '5.10'
		},
		{
			name: 'Foothill T-Shirt',
			date: '4.15'
		},
		{
			name: 'Free Project',
			date: '5.20'
		}
	];
</script>

<table>
	<thead>
		<tr>
			<th class="text-left">Project</th>
			<th class="text-right">Date</th>
		</tr>
	</thead>
	<tbody>
		{#each projects2 as p2}
			<tr>
				<td class="project-name"><a href="projects/{toKebabCase(p2.name)}">{p2.name}</a></td>
				<td class="project-date">{p2.date}</td>
			</tr>
		{/each}
		<tr><td /><td /></tr>
		<tr>
			<td><strong>Semester 1 below:</strong></td>
			<td class="project-date"><strong>Year 2021</strong></td>
		</tr>
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
