<script lang="ts">
	import { PAGE_DESCRIPTION, PAGE_TITLE } from '../constants';
</script>

<svelte:head>
	<title>{PAGE_TITLE}</title>
	<meta name="description" content={PAGE_DESCRIPTION} />
</svelte:head>

<slot />
