<script>
import RedirectIcon from './icons/RedirectIcon.svelte';
</script>
<nav class="flex w-full h-24 items-center justify-between px-30 bg-none bg-transparent backdrop-blur-md">
    <a href="/" class="flex items-center gap-4">
        <div class="relative w-14 h-14">
            <div class="absolute inset-0 rounded-full blur-xl opacity-80 scale-90 z-0 bg-gradient-to-br from-neutral-200 to-neutral-400"></div>
            <img src="/favicon.png" alt="Logo" class="relative z-10 w-14 h-14 rounded-full" draggable="false" />
        </div>
        <span class="font-semibold text-neutral-300 text-4xl">Harnes</span>
    </a>
    <div class="flex items-center gap-4">
        <!--<a href="/about" aria-label="About" class="text-neutral-500 hover:bg-neutral-800 transition-colors ease-in-out duration-300 px-2 py-1 rounded-lg">About</a>-->
        <!--<a href="/projects" aria-label="Projects" class="text-neutral-500 hover:bg-neutral-800 transition-colors ease-in-out duration-300 px-2 py-1 rounded-lg">Projects</a>-->
        <a href="/contact" aria-label="Contact" class="text-neutral-500 hover:bg-neutral-800 transition-colors ease-in-out duration-300 px-2 py-1 rounded-lg">Contact</a>
        <!--<a href="/blog" aria-label="Blog" class="flex justify-center items-center text-neutral-500 hover:bg-neutral-800 transition-colors ease-in-out duration-300 px-2 py-1 rounded-lg gap-2"><RedirectIcon class="h-4 w-4" />Blog</a>-->
    </div>
</nav>