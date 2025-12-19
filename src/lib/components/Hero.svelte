<script>
    import { onMount } from 'svelte';
    
    // SVG Icons
    const SearchIcon = `<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5"><path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" /></svg>`;
    
    // Background Image
    const heroImage = "https://images.unsplash.com/photo-1576610616656-d3aa5d1f4534?q=80&w=2874&auto=format&fit=crop"; 
    // This is an Olympic style pool, similar to the hero.
</script>

<section class="relative w-full h-screen min-h-[700px] text-white overflow-hidden">
    <!-- Background -->
    <div class="absolute inset-0">
        <img src={heroImage} alt="Olympic Pool Complex" class="w-full h-full object-cover" />
        <div class="absolute inset-0 bg-black/20"></div>
    </div>

    <!-- Header / Nav -->
    <header class="absolute top-0 left-0 w-full z-20 px-6 py-6 md:px-12 flex justify-between items-start">
        <div class="flex flex-col">
            <a href="/" class="text-2xl font-bold tracking-tight leading-none">
                Myrtha<br/>Pools
            </a>
        </div>

        <div class="flex items-center gap-4">
            <button class="w-10 h-10 flex items-center justify-center bg-white/20 backdrop-blur-sm hover:bg-white/30 transition rounded-full">
                {@html SearchIcon}
            </button>
            <button class="flex items-center gap-2 px-4 py-2 bg-white text-black text-sm font-medium hover:bg-gray-100 transition rounded-full">
                Menu
                <span class="text-[10px] ml-1">●●</span>
            </button>
        </div>
    </header>

    <!-- Hero Content -->
    <div class="absolute inset-0 flex flex-col justify-center px-6 md:px-12 z-10 pointer-events-none">
        <div class="max-w-4xl mt-20 pointer-events-auto">
            <h1 class="text-5xl md:text-7xl font-medium leading-[1.1] tracking-tight">
                Making aquatic spaces <br/>
                for sport and <br/>
                wellbeing.
            </h1>
        </div>
    </div>

    <!-- Floating Card -->
    <div class="absolute bottom-12 right-6 md:right-12 z-20 max-w-xs w-full">
        <div class="bg-white/10 backdrop-blur-md p-4 border border-white/20 text-white flex gap-4 hover:bg-white/20 transition cursor-pointer group">
            <div class="w-20 h-14 bg-gray-300 shrink-0 overflow-hidden">
                <img src="https://images.unsplash.com/photo-1585553616435-2dc0a54e271d?q=80&w=1000&auto=format&fit=crop" alt="Pool thumbnail" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition duration-500" />
            </div>
            <div class="flex flex-col justify-between flex-1">
                <p class="text-xs leading-tight opacity-90">
                    From Vietnam 2003 to Thailand 2023: Myrtha Pools and the SEA Games
                </p>
                <div class="flex items-center gap-2 mt-2">
                    <span class="text-[10px] uppercase font-bold tracking-wider">Discover more</span>
                    <span class="text-[10px]">→</span>
                </div>
            </div>
        </div>
    </div>
</section>
