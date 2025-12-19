<script>
    const sportImg = "https://images.unsplash.com/photo-1519315901367-f34ff9154487?q=80&w=1000&auto=format&fit=crop";
    const hospitalityImg = "https://images.unsplash.com/photo-1582653288634-4136fc870ca4?q=80&w=1000&auto=format&fit=crop";
    const leisureImg = "https://images.unsplash.com/photo-1571772996211-2f02c9727629?q=80&w=1000&auto=format&fit=crop";
</script>

<section class="w-full bg-white py-24 px-6 md:px-12">
    <div class="max-w-[1600px] mx-auto">
        <div class="max-w-4xl mb-16">
            <h2 class="text-2xl md:text-3xl font-normal leading-tight">
                From Olympic-sized pools to wellness centers, Myrtha offers more than traditional swimming pools by delivering comprehensive solutions through a range of expertise.
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Card 1 -->
            <div class="group cursor-pointer">
                <div class="relative aspect-[3/4] overflow-hidden mb-4">
                    <img src={sportImg} alt="Sport" class="w-full h-full object-cover transition duration-700 group-hover:scale-105" />
                    <div class="absolute top-4 left-4 text-white font-medium text-lg">Sport</div>
                    <div class="absolute top-4 right-4 text-white/80 text-xs border border-white/30 px-2 py-1 rounded-full">+</div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="group cursor-pointer">
                <div class="relative aspect-[3/4] overflow-hidden mb-4">
                    <img src={hospitalityImg} alt="Hospitality" class="w-full h-full object-cover transition duration-700 group-hover:scale-105" />
                    <div class="absolute top-4 left-4 text-white font-medium text-lg">Hospitality</div>
                    <div class="absolute top-4 right-4 text-white/80 text-xs border border-white/30 px-2 py-1 rounded-full">+</div>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="group cursor-pointer">
                <div class="relative aspect-[3/4] overflow-hidden mb-4">
                    <img src={leisureImg} alt="Leisure" class="w-full h-full object-cover transition duration-700 group-hover:scale-105" />
                    <div class="absolute top-4 left-4 text-white font-medium text-lg">Leisure</div>
                    <div class="absolute top-4 right-4 text-white/80 text-xs border border-white/30 px-2 py-1 rounded-full">+</div>
                </div>
            </div>
        </div>
    </div>
</section>
