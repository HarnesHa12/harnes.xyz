<svelte:head><title>Harnes - About</title></svelte:head>

<script>
import CatIcon from '$lib/components/icons/CatIcon.svelte';
import DiscordIcon from '$lib/components/icons/DiscordIcon.svelte';
import XIcon from '$lib/components/icons/XIcon.svelte';
import Navbar from '$lib/components/Navbar.svelte';
</script>

<main class="relative bg-linear-to-b from-[#171717] to-[#1E1E1E] text-neutral-300 flex flex-col min-h-screen w-screen">
    <Navbar />
    <section class="flex flex-col w-full justify-center items-center h-[500px]">
        <span class="text-4xl font-semibold">Contact me via</span>
        <div class="flex gap-8 w-full justify-center items-center py-8">
            <a href="https://discord.com/users/914970468392521728/" class="flex w-[80px] h-[80px] rounded-2xl bg-[#5865f2] justify-center items-center"><DiscordIcon class="w-12 h-12" /></a>
            <a href="https://x.com/harnesha12" class="flex w-[80px] h-[80px] rounded-2xl bg-[#242424] justify-center items-center"><XIcon class="text-neutral-200 w-12 h-12" /></a>
        </div>
    </section>
    
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-40 left-20" rotate="30"/>
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-56 left-80" rotate="60" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-52 left-[600px]" rotate="260" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-[500px] left-10" rotate="300" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-[430px] left-80" rotate="0" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-[500px] left-[600px]" rotate="70" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-30 left-60" rotate="260" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-32 left-[600px]" rotate="10" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-48 left-[900px]" rotate="40" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-20 right-[700px]" rotate="300" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-60 right-[600px]" rotate="110" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-20 right-96" rotate="180" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-40 right-20" rotate="220" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 bottom-80 right-70" rotate="260" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-80 right-[400px]" rotate="220" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-90 right-[600px]" rotate="210" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-30 right-[600px]" rotate="330" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-20 right-[400px]" rotate="20" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-96 right-20" rotate="260" />
	<CatIcon class="absolute text-neutral-50/15 w-32 h-32 top-40 right-40" rotate="30" />
</main>