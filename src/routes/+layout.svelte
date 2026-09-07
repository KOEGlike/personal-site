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

{@render children()}
