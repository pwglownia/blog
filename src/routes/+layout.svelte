<script lang="ts">
	import { PAGE_DESCRIPTION, PAGE_TITLE } from '../constants';
	import Header from './Header.svelte';
	import '../app.css';
</script>

<svelte:head>
	<title>{PAGE_TITLE}</title>
	<meta name="description" content={PAGE_DESCRIPTION} />
</svelte:head>

<Header />

<slot />
