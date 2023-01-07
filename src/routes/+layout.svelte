<script>
	import { fade } from 'svelte/transition';
	import '../app.css';

	export let data;
</script>

<div class="container">
	{#key data.url}
		<div in:fade={{ delay: 300, duration: 250 }} out:fade={{ delay: 0, duration: 250 }}>
			<slot />
		</div>
	{/key}
</div>
