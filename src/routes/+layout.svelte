<script>
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<header>
	<h1>
		WELKOM
	</h1>
	<h2>
		welkom op mijn site
	</h2>
</header>

{@render children()}

<style>

* {
	margin: 0;
	padding: 0;
}

header {
	padding: 1em;
	color: white;
}




</style>
