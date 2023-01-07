<script>
	import { fade } from 'svelte/transition';
	import '../app.css';

	export let data;
	let scrollY;

	$: homeLinkClass = 'home-link' + (scrollY < 20 ? ' full' : '');
</script>

<svelte:window bind:scrollY />

{#if data.url !== '/'}
	<a class={homeLinkClass} href="/" transition:fade={{ duration: 250 }}>
		&lt;<span class="home-link-text">Home</span>
	</a>
{/if}
<div class="container">
	{#key data.url}
		<div in:fade={{ delay: 300, duration: 250 }} out:fade={{ duration: 250 }}>
			<slot />
		</div>
	{/key}
</div>

<style>
	.home-link {
		position: fixed;
		top: 40px;
		width: 25px;
		height: 27px;
		padding: 5px 6px;

		border-radius: 10px;
		background-color: #fff;
		color: #4a4a55;
		box-shadow: 5px 5px 8px rgba(0, 0, 0, 0.2);

		text-decoration: none;
		text-overflow: clip;
		overflow: hidden;

		transition: all;
		transition-duration: 300ms;
	}

	.home-link.full {
		width: 5rem;
	}

	.home-link:hover {
		width: 5rem;
	}

	.home-link-text {
		margin-left: 10px;
	}
</style>
