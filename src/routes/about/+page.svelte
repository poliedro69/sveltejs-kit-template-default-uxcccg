<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<script>
    import tools from '/src/tools.json';
</script>

<div class="text-column">
	<h1>About this app</h1>
	{#each tools as tool}
		<p>{tool.id}</p>
	{/each}
</div>
