<svelte:head>
	<title>Harnes</title>
</svelte:head>

<script lang="ts">
import CatIcon from '$lib/components/icons/CatIcon.svelte';
import PrismaIcon from '$lib/components/icons/PrismaIcon.svelte';
import Navbar from '$lib/components/Navbar.svelte';
</script>

<main class="bg-linear-to-b from-[#171717] to-[#1E1E1E] text-neutral-300 flex flex-col min-h-screen w-screen relative overflow-hidden">
	<Navbar />

    <section class="flex flex-col py-30 justify-center items-center gap-4">
		<div class="relative w-36 h-36">
            <div class="absolute inset-0 rounded-full blur-xl opacity-80 scale-90 z-0 bg-gradient-to-br from-neutral-200 to-neutral-400"></div>
            <img src="/favicon.png" alt="Logo" class="relative z-10 w-36 h-36 rounded-full" draggable="false" />
        </div>
		<span class="text-6xl font-semibold">Harnes</span>
		<span class="py-5 text-xl">Full Stack Web Developer</span>
		<div class="rounded-4xl bg-[#242424] gap-3 flex justify-center items-center p-3">
			<a href="https://svelte.dev/"><img src="/logos/svelte.png" alt="Svelte Logo" width="24" height="29" /></a>
			<a href="https://code.visualstudio.com/"><img src="/logos/visualstudiocode.png" alt="Visual Studio Code Logo" width="24" height="24" /></a>
			<a href="https://www.typescriptlang.org/"><img src="/logos/typescript.png" alt="Typescript Logo" width="24" height="24" /></a>
			<a href="https://nodejs.org/en"><img src="/logos/nodejs.png" alt="NodeJS Logo" width="24" height="15" /></a>
			<a href="https://pl.wikipedia.org/wiki/HTML5"><img src="/logos/html5.png" alt="HTML5 Logo" width="24" height="24" /></a>
			<a href="https://pl.wikipedia.org/wiki/Kaskadowe_arkusze_styl%C3%B3w"><img src="/logos/css.svg" alt="CSS Logo" width="24" height="24" /></a>
			<a href="https://www.prisma.io/"><PrismaIcon class="h-6 w-6" /></a>
			<a href="https://turborepo.com/"><img src="/logos/turborepo.png" alt="Turborepo Logo" width="24" height="24" /></a>
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