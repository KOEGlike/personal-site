<script lang="ts">
	let { children } = $props();
</script>

<svelte:head>
	<title>Marcell Balázs's Personal Site</title>
	<meta
		name="description"
		content="Portfolio of Marcell Balázs, embedded systems and PCB design projects including Meko, Hackxpansion, and Mito."
	/>
</svelte:head>
<div id="container">
	<div id="sidebar">
		<a href="/">Home</a>
		<br />
		<a href="/blog">Blog</a>
	</div>
	<div id="content">{@render children()}</div>
</div>

<style>
	:global(body) {
		margin: 0;
		height: 100vh;
	}

	#container {
		display: flex;
		flex-direction: row;

		width: 100%;
		height: 100%;
		box-sizing: border-box;

		padding: 1em 0;
	}

	#sidebar {
		height: 100%;

		border-right: 0.125em solid black;
	}

	#content,
	#sidebar {
		padding: 0 1em;
	}
</style>
