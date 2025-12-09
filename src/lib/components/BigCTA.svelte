<script lang="ts">
  // Big CTA with shapes
</script>

<section class="py-32 relative overflow-hidden">
  <div class="max-w-[1200px] mx-auto px-6 relative z-10 flex flex-col items-center justify-center">
    
    <!-- Abstract Shapes Background (Absolute positioned around the button) -->
    
    <!-- Left Blue Shape -->
    <div class="absolute left-0 md:left-20 top-1/2 -translate-y-1/2 w-32 h-32 bg-[#5551ff] rounded-full mix-blend-multiply opacity-90"></div>
    
    <!-- Left Zigzag -->
    <div class="absolute left-10 md:left-40 top-20 w-48 h-24 bg-orange-200 rounded-xl overflow-hidden border-4 border-orange-500">
        <svg width="100%" height="100%" viewBox="0 0 100 50" preserveAspectRatio="none">
            <path d="M0 25 Q 12.5 0 25 25 T 50 25 T 75 25 T 100 25" stroke="#009955" stroke-width="8" fill="none" />
        </svg>
    </div>

    <!-- Right Shapes -->
    <div class="absolute right-0 md:right-20 top-10 w-40 h-40">
        <div class="absolute top-0 right-0 w-24 h-24 bg-[#ff7b5f]"></div> <!-- Orange Square -->
        <div class="absolute bottom-0 left-0 w-24 h-24 bg-[#b5a500] rounded-full mix-blend-multiply"></div> <!-- Gold Circle -->
    </div>

    <!-- Bottom Left Checkered -->
    <div class="absolute left-10 bottom-0 w-24 h-24 grid grid-cols-3 grid-rows-3 gap-1">
        {#each Array(9) as _, i}
            {#if i % 2 === 0}
                <div class="bg-[#d9b310]"></div>
            {:else}
                <div class="bg-transparent"></div>
            {/if}
        {/each}
    </div>

    <!-- Bottom Center Pink/Blue Arcs -->
    <div class="absolute bottom-[-50px] left-1/2 -translate-x-1/2 w-64 h-32 overflow-hidden">
        <div class="w-64 h-64 rounded-full border-[20px] border-[#d900ff] border-t-0 border-l-0 rotate-45 transform origin-center"></div>
    </div>

    <!-- Right Bottom Green/Purple -->
    <div class="absolute right-20 bottom-10 w-32 h-32 bg-[#d4eebc] rounded-2xl flex items-center justify-center overflow-hidden">
        <div class="w-20 h-20 bg-[#6b2c48] rounded-full mix-blend-multiply"></div>
    </div>


    <!-- Main CTA Button -->
    <button class="bg-black text-white text-4xl md:text-6xl font-medium px-12 py-6 rounded-2xl hover:scale-105 transition-transform shadow-2xl z-20">
      Get started for free
    </button>

  </div>
</section>
