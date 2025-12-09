<script lang="ts">
  // Templates Carousel
  const templates = [
    { title: "Websites", color: "bg-[#d4eebc]", image: "bg-green-800" },
    { title: "Social media", color: "bg-[#0099ff]", image: "bg-blue-800" },
    { title: "Mobile apps", color: "bg-[#0ACF83]", image: "bg-green-600" },
    { title: "Presentations", color: "bg-[#A259FF]", image: "bg-purple-800" },
    { title: "Invitations", color: "bg-[#9ca3af]", image: "bg-gray-600" },
  ];
</script>

<section class="py-24 bg-black text-white">
  <div class="max-w-[1440px] mx-auto px-6">
    <div class="flex flex-col md:flex-row justify-between items-end mb-12">
        <div>
            <h2 class="text-4xl md:text-5xl font-medium tracking-tight mb-6 max-w-2xl leading-tight">
                Start with a template. Make just about anything.
            </h2>
            <button class="border border-white rounded-lg px-6 py-3 font-medium hover:bg-white hover:text-black transition-colors">
                Explore all templates
            </button>
        </div>

        <div class="flex items-center gap-4 mt-8 md:mt-0">
            <span class="font-mono text-sm">1/10</span>
            <div class="flex gap-2">
                <button class="w-10 h-10 rounded-full border border-gray-700 flex items-center justify-center hover:bg-gray-800">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path></svg>
                </button>
                <button class="w-10 h-10 rounded-full border border-gray-700 flex items-center justify-center hover:bg-gray-800">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                </button>
            </div>
        </div>
    </div>

    <!-- Carousel (Static Grid for now) -->
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-5 gap-4">
        {#each templates as template}
            <div class="{template.color} text-black rounded-xl p-4 h-[400px] flex flex-col relative overflow-hidden group cursor-pointer transition-transform hover:-translate-y-2">
                <h3 class="text-xl font-bold mb-4">{template.title}</h3>
                
                <!-- Simulated Template Preview -->
                <div class="flex-1 bg-white rounded-lg shadow-lg overflow-hidden relative translate-y-4 group-hover:translate-y-2 transition-transform">
                    <div class="h-4 bg-gray-100 border-b border-gray-200 flex items-center px-2 gap-1">
                        <div class="w-2 h-2 rounded-full bg-red-400"></div>
                        <div class="w-2 h-2 rounded-full bg-yellow-400"></div>
                        <div class="w-2 h-2 rounded-full bg-green-400"></div>
                    </div>
                    <div class="p-2 grid grid-cols-2 gap-2">
                        <div class="h-20 bg-gray-200 rounded"></div>
                        <div class="h-20 bg-gray-200 rounded"></div>
                        <div class="col-span-2 h-32 bg-gray-200 rounded"></div>
                    </div>
                </div>
            </div>
        {/each}
    </div>
  </div>
</section>
