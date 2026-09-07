<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Marcell Balázs's Personal Site</title>
	<meta
		name="description"
		content="Portfolio of Marcell Balázs, embedded systems and PCB design projects including Meko, Hackxpansion, and Mito."
	/>
</svelte:head>
<div
	class="flex h-screen w-screen flex-row prose-xl py-2 leading-snug prose-ul:my-1 prose-li:my-0 prose-a:text-[#0000EE] prose-a:visited:text-[#551A8B] prose-a:active:text-[#EE0000] prose-a:underline prose-a:font-normal"
>
	<div class="h-full border-r-2 border-black px-4">
		<a href="/">Home</a>
		<br />
		<a href="/blog">Blog</a>
	</div>
	<div class="mx-4">{@render children()}</div>
</div>
