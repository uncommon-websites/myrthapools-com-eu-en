<script>
    // Images
    const resortPool = "https://images.unsplash.com/photo-1540541338287-41700207dee6?q=80&w=2000&auto=format&fit=crop";
    const olympicPool = "https://images.unsplash.com/photo-1575429198097-0414ec08e8cd?q=80&w=1000&auto=format&fit=crop";
    const cityPool = "https://images.unsplash.com/photo-1565557623262-b51c2513a641?q=80&w=1000&auto=format&fit=crop";
</script>

<section class="w-full bg-white border-t border-gray-200">
    <div class="grid grid-cols-1 md:grid-cols-4 min-h-[800px]">
        <!-- Column 1: Empty with border -->
        <div class="hidden md:block border-r border-gray-200 relative">
            <!-- Vertical line decoration if needed -->
        </div>

        <!-- Column 2 & 3 & 4 Container -->
        <div class="md:col-span-3 grid grid-cols-1 md:grid-cols-3">
            
            <!-- Top Right Large Image (Spans 3 cols effectively in the subgrid) -->
            <div class="md:col-span-3 relative h-[400px] md:h-[500px] border-b border-gray-200 p-6 md:p-12 flex items-center justify-center">
                 <div class="w-full h-full overflow-hidden relative group">
                     <img src={resortPool} alt="Resort Pool" class="w-full h-full object-cover transition duration-700 group-hover:scale-105" />
                 </div>
            </div>

            <!-- Bottom Left Image (Paris 2024) -->
            <div class="md:col-span-1 border-r border-gray-200 p-6 flex flex-col gap-4">
                <div class="w-full aspect-[4/3] overflow-hidden">
                    <img src={olympicPool} alt="Paris 2024" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
                </div>
                <div class="mt-auto">
                    <div class="flex justify-between text-[10px] uppercase font-bold text-gray-400 mb-1">
                        <span>France</span>
                        <span>2024</span>
                    </div>
                    <h3 class="text-lg font-medium leading-tight">Paris 2024, Olympic Games</h3>
                </div>
            </div>

            <!-- Spacer Column (Middle bottom) -->
             <div class="hidden md:block border-r border-gray-200"></div>

            <!-- Bottom Right Image (Parramatta) -->
            <div class="md:col-span-1 p-6 flex flex-col gap-4">
                <div class="w-full aspect-[4/3] overflow-hidden">
                    <img src={cityPool} alt="Parramatta Aquatic Centre" class="w-full h-full object-cover hover:scale-105 transition duration-500" />
                </div>
                <div class="mt-auto">
                    <div class="flex justify-between text-[10px] uppercase font-bold text-gray-400 mb-1">
                        <span>Australia</span>
                        <span>2023</span>
                    </div>
                    <h3 class="text-lg font-medium leading-tight">Parramatta Aquatic Centre</h3>
                </div>
            </div>

        </div>
    </div>
</section>
