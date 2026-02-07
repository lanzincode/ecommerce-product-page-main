<script>
	import favicon from '/assets/favicon-32x32.png';
	import '$lib/styles/tokens.css';
	import '$lib/styles/base.css';
	import '$lib/styles/layout.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Frontend Mentor | E-commerce product page</title>
</svelte:head>

{@render children()}
