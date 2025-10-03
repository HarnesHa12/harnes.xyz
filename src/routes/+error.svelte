<svelte:head><title>Error</title></svelte:head>

<script lang="ts">
import { page } from '$app/state';
import CatIcon from '$lib/components/icons/CatIcon.svelte';
</script>

<main class="flex flex-col min-w-screen min-h-screen overflow-hidden">
    <div class="flex flex-col justify-center items-center w-full h-[800px] gap-6">
        <CatIcon class="text-neutral-300/50 w-36 h-36" />
        <span class="text-6xl font-semibold">{page.status}</span>
        <span class="text-3xl">{page.error?.message}</span>
    </div>
</main>