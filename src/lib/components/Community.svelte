<script lang="ts">
  // Community Section
  const items = [
    { title: "Virtual Teleportation Portal App", author: "Masaya Takizawa", color: "bg-purple-900" },
    { title: "Bubbles Design System", author: "Raul Marin Calleja", color: "bg-green-900" },
    { title: "Virtual Graffiti Wall", author: "Seungmee Lee", color: "bg-gray-200" },
    { title: "Pixel Editor", author: "Ayaneshu Bhardwaj", color: "bg-white border" },
    { title: "Cursor Images", author: "Gui Seiz", color: "bg-black" },
    { title: "Pattern Generator", author: "Benjamin Leonard", color: "bg-black" },
    { title: "Flower Catcher", author: "Nayli C. Naza", color: "bg-pink-100" },
    { title: "Earworm Studio", author: "Holly Li", color: "bg-gray-800" },
  ];
</script>

<section class="py-24">
  <div class="max-w-[1200px] mx-auto px-6">
    <h2 class="text-4xl md:text-5xl font-medium tracking-tight text-gray-900 mb-12">
      Explore what people are making
    </h2>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6 mb-12">
      {#each items as item}
        <div class="group cursor-pointer">
          <div class="{item.color} aspect-[4/3] rounded-lg mb-3 overflow-hidden relative shadow-sm border border-gray-100 transition-transform group-hover:-translate-y-1">
            <!-- Placeholder content for thumbnail -->
            {#if item.title.includes('Portal')}
                 <div class="absolute inset-0 bg-gradient-to-br from-purple-600 to-blue-900 opacity-80"></div>
                 <div class="absolute inset-0 flex items-center justify-center text-white text-xs opacity-50">UI Preview</div>
            {:else if item.title.includes('Bubbles')}
                 <div class="absolute inset-0 bg-[#002b36] flex items-center justify-center">
                    <div class="text-green-400 font-mono text-xs">Bubbles DS</div>
                 </div>
            {:else if item.title.includes('Graffiti')}
                 <div class="absolute inset-0 bg-gray-100 flex items-center justify-center">
                    <div class="flex gap-1">
                        <div class="w-2 h-8 bg-black rotate-12"></div>
                        <div class="w-2 h-8 bg-black -rotate-12"></div>
                        <div class="w-2 h-8 bg-black rotate-6"></div>
                    </div>
                 </div>
            {:else if item.title.includes('Pixel')}
                 <div class="absolute inset-0 bg-white flex items-center justify-center">
                    <div class="grid grid-cols-3 gap-1">
                        <div class="w-4 h-4 bg-green-400"></div>
                        <div class="w-4 h-4 bg-green-400"></div>
                        <div class="w-4 h-4 bg-white border border-gray-200"></div>
                        <div class="w-4 h-4 bg-green-400"></div>
                        <div class="w-4 h-4 bg-green-400"></div>
                    </div>
                 </div>
            {:else}
                 <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-12 h-12 rounded-full bg-white/10"></div>
                 </div>
            {/if}
          </div>
          <h3 class="font-bold text-sm text-gray-900 mb-1">{item.title}</h3>
          <div class="flex items-center gap-2">
            <div class="w-4 h-4 rounded-full bg-gray-300 overflow-hidden">
                <img src={`https://ui-avatars.com/api/?name=${item.author}&background=random&size=32`} alt={item.author} />
            </div>
            <span class="text-xs text-gray-500 hover:underline">{item.author}</span>
          </div>
        </div>
      {/each}
    </div>

    <div class="text-center">
        <a href="#" class="text-black font-medium border-b border-black hover:opacity-70 pb-0.5">Explore more</a>
    </div>
  </div>
</section>
