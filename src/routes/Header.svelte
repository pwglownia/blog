<script lang="ts">
</script>

<nav>
	<a href="/">blog-title-here</a>

	<ul class="grid">
		<li><a href="/about">about</a></li>
		<li><a href="/categories">categories</a></li>
		<li><a href="/hire-me">hire me</a></li>
		<li><a href="/rss.xml" target="_blank">RSS</a></li>
	</ul>

	<button />
</nav>

<style>
	nav {
		padding-block: var(--size-7);
	}

	li {
		margin-block: var(--size-7);
	}

	a {
		color: inherit;
		text-decoration: none;
	}

	@media (min-width: 768px) {
		nav {
			display: grid;
			justify-content: space-between;
		}

		li {
			display: flex;
			gap: var(--size-7);
			margin-block: 0;
		}
	}
</style>
