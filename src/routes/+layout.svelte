<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Testing sveltekit app v1</title>
</svelte:head>

<div>
	<p>This is something constant for all pages as it is the layout page</p>
</div>

{@render children()}