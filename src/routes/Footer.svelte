<script>
	import { PAGE_TITLE } from '../constants';
</script>

<footer class="p-4 bg-slate-300">
	<p>{PAGE_TITLE} &copy {new Date().getFullYear()}</p>
</footer>

<style>
	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
	}

	p {
		color: var(--text-2);
	}
</style>
