<script lang="ts">
	import '../app.css';
	// import type { LayoutData } from './$types';

	// export let data: LayoutData;
</script>

<svelte:head>
	<title>Broscaru.eu</title>
</svelte:head>

<div
	class="h-full w-full bg-gradient-to-tr from-slate-900 via-60% via-indigo-950 to-slate-950 text-slate-300/80"
>
	<main>
		<slot />
	</main>
</div>
