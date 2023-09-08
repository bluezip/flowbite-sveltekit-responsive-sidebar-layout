<script lang="ts">
	import type { PageData } from './$types';
	export let data: PageData;
</script>

<svelte:head>
	<title>{data.title}</title>
</svelte:head>

<svelte:component this={data.content} />
