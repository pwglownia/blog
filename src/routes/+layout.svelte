<script lang="ts">
	import { PAGE_DESCRIPTION, PAGE_TITLE } from '../constants';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';

	import 'open-props/style';
	import 'open-props/normalize';
	import 'open-props/buttons';
</script>

<svelte:head>
	<title>{PAGE_TITLE}</title>
	<meta name="description" content={PAGE_DESCRIPTION} />
</svelte:head>

<div class="layout">
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>

<style>
	.layout {
		height: 100%;
		max-inline-size: 1440px;
		display: grid;
		grid-template-rows: auto 1fr auto;
		margin-inline: auto;
		padding-inline: var(--size-7);
	}

	main {
		padding-block: var(--size-9);
	}

	@media (min-width: 1440px) {
		.layout {
			padding-inline: 0;
		}
	}
</style>
