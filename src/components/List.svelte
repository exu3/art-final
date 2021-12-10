<script>
  const projects = [
    {
      name: "ID Badge",
      date: "10.09"
    },
    {
      name: "Animorph",
      date: "10.09"
    },
    {
      name: "Hand Collage",
      date: "10.09"
    },
    {
      name: "Digital Mandala",
      date: "10.09"
    },
    {
      name: "Color Scheme Collage",
      date: "10.09"
    },
    {
      name: "Flat Landscape Painting",
      date: "10.09"
    },
    {
      name: "Color Formula Monster",
      date: "10.09"
    },
    {
      name: "Animated GIF",
      date: "10.09"
    },
    {
      name: "Neuro Doodle",
      date: "10.09"
    },
    {
      name: "Photo Illustration",
      date: "10.09"
    }
  ]
</script>

<table>
    <thead>
      <tr>
        <th class="text-left">Project</th>
        <th class="text-right">Date</th>
      </tr>
    </thead>
    <tbody>
      {#each projects as p}
        <tr>
          <td class="project-name"><a href="/">{p.name}</a></td>
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