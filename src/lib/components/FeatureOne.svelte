<script lang="ts">
  // Feature 1: Prompt, code, and design
</script>

<section class="py-24">
  <div class="max-w-[1200px] mx-auto px-6">
    <h2 class="text-4xl md:text-5xl font-medium tracking-tight text-gray-900 mb-12 max-w-2xl leading-tight">
      Prompt, code, and design from first idea to final product
    </h2>

    <div class="bg-gray-100 rounded-3xl overflow-hidden shadow-sm border border-gray-200">
      <!-- Header/Toolbar simulation -->
      <div class="bg-white border-b border-gray-200 p-3 flex items-center justify-between px-6">
        <div class="flex items-center gap-4">
            <div class="flex gap-2">
                <div class="w-3 h-3 rounded-full bg-red-400"></div>
                <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                <div class="w-3 h-3 rounded-full bg-green-400"></div>
            </div>
            <span class="text-sm font-medium text-gray-600">Media Player</span>
        </div>
        <div class="flex items-center gap-4 text-sm text-gray-500">
            <span>Preview</span>
            <span>Code</span>
            <button class="bg-blue-600 text-white px-3 py-1 rounded">Share</button>
        </div>
      </div>

      <div class="flex flex-col md:flex-row h-[600px]">
        <!-- Left Sidebar: Prompt -->
        <div class="w-full md:w-1/3 bg-white border-r border-gray-200 p-6 flex flex-col">
            <div class="flex-1">
                <div class="bg-gray-50 p-4 rounded-xl mb-4 text-sm text-gray-600">
                    <p class="mb-2">Turn this design into a functional music player with spinning disc animation. The player will have track selection, play/pause functionality, and visual feedback for the currently playing track. The disc will spin when any track is playing.</p>
                </div>
                
                <div class="space-y-4">
                    <div class="flex items-center gap-2 text-sm font-medium text-gray-700">
                        <span>Reasoning</span>
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </div>
                    
                    <div class="pl-4 border-l-2 border-gray-200 space-y-2 text-sm text-gray-600">
                        <p>• Identify the main components: disc, controls, track list.</p>
                        <p>• Add audio file integration with actual sound playback.</p>
                        <p>• Implement progress bars and seek functionality.</p>
                    </div>
                </div>
            </div>

            <div class="mt-auto">
                <div class="flex items-center gap-2 mb-2">
                    <div class="w-6 h-6 rounded-full bg-purple-500 text-white flex items-center justify-center text-xs">M</div>
                    <span class="text-xs text-gray-500">Maria</span>
                </div>
                <div class="relative">
                    <input type="text" placeholder="Make anything..." class="w-full bg-gray-50 border border-gray-200 rounded-lg px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500">
                    <button class="absolute right-2 top-1/2 -translate-y-1/2 p-1 hover:bg-gray-200 rounded">
                        <svg class="w-4 h-4 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </button>
                </div>
            </div>
        </div>

        <!-- Right Content: The Design -->
        <div class="flex-1 bg-gray-100 relative flex items-center justify-center p-8">
            <!-- Simulated Music Player UI -->
            <div class="bg-[#1e1e1e] rounded-xl shadow-2xl w-full max-w-2xl h-[400px] flex overflow-hidden text-white font-sans relative">
                <!-- Album Art Side -->
                <div class="w-1/2 p-8 flex flex-col items-center justify-center bg-gradient-to-br from-orange-900 to-gray-900 relative">
                    <div class="text-xl font-medium mb-8">Dreamy Haze</div>
                    <div class="w-48 h-48 rounded-full bg-[url('https://placehold.co/200x200/orange/white?text=CD')] bg-cover border-4 border-white/10 shadow-lg animate-spin-slow relative">
                        <div class="absolute inset-0 bg-gradient-to-tr from-transparent to-white/20 rounded-full"></div>
                        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-12 h-12 bg-black rounded-full border border-gray-700"></div>
                    </div>
                    
                    <!-- Cursor overlay -->
                    <div class="absolute top-1/2 left-1/2 transform translate-x-8 translate-y-8 z-10">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M5.65376 12.3673H5.46026L5.31717 12.4976L0.500002 16.8829L0.500002 1.19841L11.7841 12.3673H5.65376Z" fill="#1ABCFE" stroke="white"/></svg>
                        <div class="bg-[#1ABCFE] text-white text-[10px] px-1.5 py-0.5 rounded ml-2 mt-1">Robin</div>
                    </div>
                </div>

                <!-- Controls Side -->
                <div class="w-1/2 bg-[#252525] p-6 flex flex-col">
                    <div class="flex justify-between text-xs text-gray-400 mb-6">
                        <span>TIME</span>
                        <span>BPM</span>
                        <span>BR</span>
                    </div>
                    
                    <div class="space-y-2 mb-6">
                        <div class="flex items-center justify-between p-2 rounded bg-white/5 border border-white/10">
                            <div class="flex items-center gap-3">
                                <div class="w-8 h-8 bg-green-500 rounded flex items-center justify-center text-xs">▶</div>
                                <div>
                                    <div class="text-sm font-medium">Amina</div>
                                    <div class="text-[10px] text-gray-400">WAVES</div>
                                </div>
                            </div>
                            <div class="text-xs text-gray-400">02:30</div>
                        </div>
                        <div class="flex items-center justify-between p-2 rounded hover:bg-white/5">
                            <div class="flex items-center gap-3">
                                <div class="text-gray-500 text-xs">02</div>
                                <div>
                                    <div class="text-sm font-medium text-gray-400">WHISPERS SOFT</div>
                                </div>
                            </div>
                            <div class="text-xs text-gray-500">03:45</div>
                        </div>
                         <div class="flex items-center justify-between p-2 rounded hover:bg-white/5">
                            <div class="flex items-center gap-3">
                                <div class="text-gray-500 text-xs">03</div>
                                <div>
                                    <div class="text-sm font-medium text-gray-400">CLOUDED SKIES</div>
                                </div>
                            </div>
                            <div class="text-xs text-gray-500">04:12</div>
                        </div>
                    </div>

                    <!-- Waveform -->
                    <div class="mt-auto h-12 flex items-end gap-0.5 opacity-50">
                        {#each Array(30) as _, i}
                            <div class="w-1 bg-green-500" style="height: {Math.random() * 100}%"></div>
                        {/each}
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>

    <!-- Tabs below image -->
    <div class="flex flex-wrap justify-center gap-2 mt-8">
        {#each ['Prompt', 'Design', 'Draw', 'Build', 'Publish', 'Promote', 'Jam', 'Present'] as tab, i}
            <button class="px-4 py-2 rounded-full text-sm font-medium transition-colors {i === 0 ? 'bg-gray-200 text-gray-900' : 'bg-transparent text-gray-600 hover:bg-gray-100'}">
                {tab}
            </button>
        {/each}
    </div>

    <div class="text-center mt-8">
        <p class="text-xl text-gray-900 mb-4">Prompt to code anything you can imagine with AI.</p>
        <a href="#" class="text-black font-medium border-b border-black hover:opacity-70 pb-0.5">Explore Figma Make</a>
    </div>
  </div>
</section>
