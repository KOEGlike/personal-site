<script lang="ts">
	import { projects } from '$lib/content/projects';
</script>

Hi there, I'm Marcell! <br /> I'm excited about embedded systems and designing PCBs! <br /> <br />
Here are some of my projects:

<ul>
	{#each projects as project}
		<li>
			<b>
				<a href={project.repo} target="_blank" rel="noopener noreferrer">
					{project.name}
				</a>
			</b>: {project.description}
		</li>
	{/each}
</ul>

<br />

Check out my
<a href="https://github.com/koeglike" target="_blank" rel="noopener noreferrer">GitHub</a>
and
<a href="https://www.linkedin.com/in/marcell-balazs123/" target="_blank" rel="noopener noreferrer">
	LinkedIn
</a>

<br />

My email is: <a href="mailto:koeglike@proton.me">koeglike@proton.me</a>
