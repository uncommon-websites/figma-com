<script lang="ts">
  // Hero section
</script>

<section class="pt-24 pb-16 overflow-hidden">
  <div class="max-w-[1440px] mx-auto px-4 relative">
    
    <!-- Background Collage (Simulated) -->
    <div class="relative h-[500px] w-full bg-gray-50 rounded-3xl overflow-hidden mb-12">
        <!-- We will create a grid of colored blocks/images to simulate the collage -->
        <div class="absolute inset-0 grid grid-cols-4 grid-rows-2 gap-4 p-4 opacity-80">
            <!-- Row 1 -->
            <div class="bg-gradient-to-br from-purple-500 to-pink-500 rounded-xl col-span-1 row-span-2 relative overflow-hidden group">
                <div class="absolute top-4 left-4 text-white font-mono text-xs">72°</div>
                <div class="absolute bottom-4 left-4 text-white font-mono text-xs">
                    <div>JFK</div>
                    <div>non-stop</div>
                </div>
                <!-- Abstract shapes -->
                <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-32 h-32 rounded-full border-4 border-white/20"></div>
            </div>
            
            <div class="bg-[#f0f0f0] rounded-xl col-span-1 overflow-hidden relative">
                <div class="p-4">
                    <h3 class="font-serif text-2xl italic">Rhythm<br>Dance</h3>
                </div>
                <div class="absolute bottom-0 right-0 w-24 h-24 bg-green-200 rounded-tl-full"></div>
            </div>

            <div class="bg-gray-200 rounded-xl col-span-1 overflow-hidden relative">
                 <div class="absolute inset-0 bg-[url('https://placehold.co/400x300/e0e0e0/ffffff?text=Interface')] bg-cover"></div>
            </div>

            <div class="bg-yellow-300 rounded-xl col-span-1 overflow-hidden flex items-center justify-center">
                <h2 class="text-4xl font-black text-blue-600 rotate-[-10deg]">FOOD WORKS</h2>
            </div>

            <!-- Row 2 -->
            <div class="bg-white border border-gray-200 rounded-xl col-span-1 overflow-hidden p-4 relative">
                 <div class="absolute top-2 left-2 w-8 h-8 rounded-full bg-green-400"></div>
                 <div class="mt-8 space-y-2">
                    <div class="h-2 bg-gray-100 rounded w-3/4"></div>
                    <div class="h-2 bg-gray-100 rounded w-1/2"></div>
                 </div>
            </div>

            <div class="bg-black rounded-xl col-span-2 overflow-hidden relative">
                 <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-full h-full opacity-50 bg-gradient-to-r from-gray-800 to-black"></div>
                 </div>
            </div>
        </div>

        <!-- Center Overlay Card -->
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-white rounded-2xl shadow-xl p-8 md:p-12 text-center max-w-2xl w-[90%] z-10">
            <h1 class="text-4xl md:text-6xl font-medium tracking-tight text-gray-900 mb-8 leading-[1.1]">
                Make anything possible, all in Figma
            </h1>
            <button class="bg-[#5551ff] text-white font-medium text-lg px-8 py-3 rounded-xl hover:bg-[#4440ee] transition-colors">
                Get started
            </button>
        </div>

        <!-- Floating cursors/elements for decoration -->
        <div class="absolute top-[30%] left-[25%] z-20">
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M9.5 28L4 4L28 14.5L16.5 17.5L9.5 28Z" fill="#0ACF83" stroke="white" stroke-width="2"/>
            </svg>
            <div class="absolute top-6 left-4 bg-[#0ACF83] text-white text-xs px-2 py-0.5 rounded">Ria</div>
        </div>
        <div class="absolute bottom-[30%] right-[25%] z-20">
             <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M9.5 28L4 4L28 14.5L16.5 17.5L9.5 28Z" fill="#F24E1E" stroke="white" stroke-width="2"/>
            </svg>
             <div class="absolute top-6 left-4 bg-[#F24E1E] text-white text-xs px-2 py-0.5 rounded">Tom</div>
        </div>
    </div>

    <!-- Bottom Text & Controls -->
    <div class="flex flex-col md:flex-row justify-between items-end gap-6">
        <p class="text-xl md:text-2xl text-gray-900 max-w-2xl leading-relaxed">
            Figma lets you turn big ideas into real products.<br>
            Brainstorm, design, and build with your team.
        </p>

        <div class="flex items-center gap-2">
            <button class="w-10 h-10 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path></svg>
            </button>
            <button class="w-10 h-10 rounded-full border border-gray-900 flex items-center justify-center hover:bg-gray-50 text-gray-900">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 9v6m4-6v6m7-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
            </button>
            <button class="w-10 h-10 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
            </button>
        </div>
    </div>

  </div>
</section>
