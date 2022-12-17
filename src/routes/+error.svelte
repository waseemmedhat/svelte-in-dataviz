<script>
	import { page } from '$app/stores';
</script>

{#if $page.status === 404}
	<h1>Page not found or under construction</h1>
	<a href="/">Return to home</a>
{/if}
