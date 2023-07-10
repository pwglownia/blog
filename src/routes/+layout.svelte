<script lang="ts">
	import { PAGE_DESCRIPTION, PAGE_TITLE } from '../constants';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<svelte:head>
	<title>{PAGE_TITLE}</title>
	<meta name="description" content={PAGE_DESCRIPTION} />
</svelte:head>

<div>
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>

<style>
</style>
