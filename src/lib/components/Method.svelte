<script>
    const methodImage = "https://images.unsplash.com/photo-1530549387789-4c1017266635?q=80&w=2500&auto=format&fit=crop";
</script>

<section class="w-full relative h-[600px] overflow-hidden text-white">
    <div class="absolute inset-0">
        <img src={methodImage} alt="Swimmers overhead" class="w-full h-full object-cover" />
        <div class="absolute inset-0 bg-blue-900/30 mix-blend-multiply"></div>
        <div class="absolute inset-0 bg-black/10"></div>
    </div>

    <div class="absolute inset-0 flex flex-col justify-center px-6 md:px-12 max-w-[1600px] mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 w-full h-full relative">
            
            <!-- Vertical Lines Overlay for Grid Continuity -->
            <div class="absolute inset-0 grid grid-cols-4 pointer-events-none border-l border-white/20 border-r border-white/20">
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
            </div>

            <div class="md:col-span-6 flex items-center z-10">
                <h2 class="text-3xl md:text-5xl font-medium leading-tight">
                    Every detail matters, from conception to final configuration. Precision inspires every step.
                </h2>
            </div>
            
            <div class="md:col-span-6 flex items-end justify-center md:justify-start pb-24 z-10">
                <div class="bg-white/10 backdrop-blur-md p-6 border border-white/20 max-w-xs">
                    <p class="text-xs mb-4 leading-relaxed">
                        We start by blending experience, technology and vision to support with design and engineering. Then we work closely with architects and engineers to develop innovative, sustainable, and tailored solutions by using high-quality materials and cutting-edge technology.
                    </p>
                    <button class="text-[10px] uppercase font-bold tracking-wider border-b border-white pb-1 hover:opacity-70 transition">
                        Discover our method
                    </button>
                </div>
            </div>

        </div>
    </div>
</section>
