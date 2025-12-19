<script>
    // Images
    const chaletImg = "https://images.unsplash.com/photo-1519817914152-22d216bb9170?q=80&w=1000&auto=format&fit=crop";
    const schoolImg = "https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?q=80&w=1000&auto=format&fit=crop";
    const japanImg = "https://images.unsplash.com/photo-1600965962102-9d260a71890d?q=80&w=1000&auto=format&fit=crop";
</script>

<footer class="bg-[#0A121D] text-white w-full border-t border-white/10">
    <!-- Highlights Header -->
    <div class="px-6 md:px-12 py-12 border-b border-white/10">
        <div class="max-w-[1600px] mx-auto flex justify-between items-center">
            <h2 class="text-3xl md:text-4xl font-medium">Project highlights</h2>
            <a href="#" class="text-[10px] uppercase font-bold tracking-wider hover:text-gray-300 flex items-center gap-2">
                <span class="w-2 h-2 bg-white rounded-full"></span>
                Discover all projects
            </a>
        </div>
    </div>

    <!-- Highlights Grid -->
    <div class="border-b border-white/10">
        <div class="grid grid-cols-1 md:grid-cols-4 min-h-[600px]">
            
            <!-- Col 1: Empty / Lines -->
            <div class="hidden md:block border-r border-white/10 relative"></div>

            <!-- Col 2: Chalet Image & Japan Image -->
            <div class="md:col-span-1 border-r border-white/10 flex flex-col">
                <!-- Chalet -->
                <div class="p-6 border-b border-white/10 flex-1 flex flex-col justify-center">
                    <div class="aspect-square w-full overflow-hidden mb-4 group cursor-pointer">
                        <img src={chaletImg} alt="Chalet al Foss" class="w-full h-full object-cover transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="flex justify-between text-[10px] uppercase text-gray-400 mb-1">
                        <span>Italy</span>
                        <span>2024</span>
                    </div>
                    <h3 class="text-lg font-medium">Chalet al Foss</h3>
                </div>
                
                <!-- Japan -->
                <div class="p-6 flex-1 flex flex-col justify-center">
                    <div class="aspect-square w-full overflow-hidden mb-4 group cursor-pointer">
                        <img src={japanImg} alt="Japan Project" class="w-full h-full object-cover transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="flex justify-between text-[10px] uppercase text-gray-400 mb-1">
                        <span>Japan</span>
                        <span>2024</span>
                    </div>
                    <h3 class="text-lg font-medium">Japan Project</h3>
                </div>
            </div>

            <!-- Col 3: Links List (History etc) -->
            <div class="md:col-span-1 border-r border-white/10 p-6 flex flex-col justify-end pb-24">
                <!-- This column is actually empty in the screenshot's grid for the top part, 
                     but contains the "History", "People", etc links in the lower part. 
                     Wait, looking at the screenshot, the "Chalet" is in the 2nd column (if 4 cols).
                     The 3rd column is empty at the top, but has "History..." text list at the bottom.
                     The 4th column has the "Justin Garza" image.
                -->
                 <div class="mt-auto flex flex-col gap-2 text-xl md:text-2xl text-gray-400 font-light">
                    <a href="#" class="hover:text-white transition">History</a>
                    <a href="#" class="hover:text-white transition">People and Culture</a>
                    <a href="#" class="hover:text-white transition">Partnerships</a>
                    <a href="#" class="hover:text-white transition">Corporate offices</a>
                    <a href="#" class="hover:text-white transition">Careers</a>
                </div>
            </div>

            <!-- Col 4: School Image -->
            <div class="md:col-span-1 p-6 flex flex-col justify-center pt-32">
                <div class="aspect-square w-full overflow-hidden mb-4 group cursor-pointer">
                    <img src={schoolImg} alt="Justin Garza High School" class="w-full h-full object-cover transition duration-500 group-hover:scale-105" />
                </div>
                <div class="flex justify-between text-[10px] uppercase text-gray-400 mb-1">
                    <span>United States</span>
                    <span>2024</span>
                </div>
                <h3 class="text-lg font-medium">Justin Garza High School</h3>
            </div>

        </div>
    </div>

    <!-- Bottom Footer Info -->
    <div class="px-6 md:px-12 py-16">
        <div class="max-w-[1600px] mx-auto grid grid-cols-1 md:grid-cols-4 gap-12">
            
            <!-- Address / Logo -->
            <div class="flex flex-col justify-between h-full min-h-[200px]">
                <div>
                    <p class="text-sm font-bold mb-1">Myrtha Pools – Via Solferino, 27</p>
                    <p class="text-sm font-bold mb-1">46043 Castiglione delle Stiviere (MN)</p>
                    <p class="text-sm font-bold">Italy</p>
                </div>

                <div class="mt-12">
                    <p class="text-[10px] uppercase text-gray-500 mb-2">We are partner of</p>
                    <div class="flex items-center gap-2">
                        <div class="w-8 h-8 rounded-full border-2 border-white flex items-center justify-center">
                            <!-- Simple Logo Placeholder -->
                            <div class="w-4 h-4 bg-white rounded-full"></div>
                        </div>
                        <span class="font-bold text-lg leading-none">WORLD<br/>AQUATICS</span>
                    </div>
                </div>
            </div>

            <!-- Links Columns -->
            <div class="grid grid-cols-2 md:grid-cols-4 col-span-1 md:col-span-3 gap-8 text-xs text-gray-300">
                
                <div class="flex flex-col gap-3">
                    <span class="text-[10px] uppercase text-gray-500 mb-2">Technologies</span>
                    <a href="#" class="hover:text-white">New Pool Construction</a>
                    <a href="#" class="hover:text-white">Pool Renovation</a>
                    <a href="#" class="hover:text-white">Pool Accessories</a>
                </div>

                <div class="flex flex-col gap-3">
                    <span class="text-[10px] uppercase text-gray-500 mb-2">Disciplines</span>
                    <a href="#" class="hover:text-white">Sport</a>
                    <a href="#" class="hover:text-white">Hospitality</a>
                    <a href="#" class="hover:text-white">Leisure</a>
                </div>

                <div class="flex flex-col gap-3">
                    <span class="text-[10px] uppercase text-gray-500 mb-2">Myrtha</span>
                    <a href="#" class="hover:text-white">Contact us</a>
                    <a href="#" class="hover:text-white">History</a>
                    <a href="#" class="hover:text-white">Our promise</a>
                    <a href="#" class="hover:text-white">Careers</a>
                    <a href="#" class="hover:text-white">ESG Reports</a>
                    <a href="#" class="hover:text-white">Code of Ethics</a>
                </div>

                <div class="flex flex-col gap-3">
                    <span class="text-[10px] uppercase text-gray-500 mb-2">Social Media</span>
                    <a href="#" class="hover:text-white">Linkedin</a>
                    <a href="#" class="hover:text-white">Youtube</a>
                    <a href="#" class="hover:text-white">Instagram</a>
                    <a href="#" class="hover:text-white">Facebook</a>
                    <a href="#" class="hover:text-white">Pinterest</a>
                </div>

            </div>
        </div>

        <!-- Legal Bottom -->
        <div class="max-w-[1600px] mx-auto mt-24 pt-8 border-t border-white/10 flex flex-col md:flex-row justify-between text-[10px] text-gray-500 uppercase tracking-wider">
            <div class="flex flex-col md:flex-row gap-4 md:gap-8">
                <span>VAT Europe 019 - VAT IT019...</span> <!-- Truncated for brevity -->
                <span>Registro Imprese di Mantova n. 019...</span>
                <span>REA MN167... - Capitale Sociale...</span>
            </div>
            <div class="flex gap-6 mt-4 md:mt-0">
                <a href="#" class="hover:text-white">Privacy Policy</a>
                <a href="#" class="hover:text-white">Cookies Policy</a>
                <a href="#" class="hover:text-white">Manage Cookie Preferences</a>
                <span class="ml-auto md:ml-0">Website by Basico</span>
            </div>
        </div>
    </div>
</footer>
