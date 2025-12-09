<script lang="ts">
  // Feature 3: Ship products
</script>

<section class="py-24 bg-gray-100">
  <div class="max-w-[1200px] mx-auto px-6">
    <h2 class="text-4xl md:text-5xl font-medium tracking-tight text-gray-900 mb-16 max-w-2xl leading-tight">
      Ship products, any way you want
    </h2>

    <div class="flex flex-col md:flex-row gap-12">
        <!-- Left Menu -->
        <div class="w-full md:w-1/3 space-y-8">
            <div class="group cursor-pointer">
                <div class="flex items-start gap-3 mb-2">
                    <svg class="w-6 h-6 text-black mt-1" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 7l10 5 10-5-10-5zm0 9l2-1-2-1-2 1 2 1zm0 2l-10 5 10 5 10-5-10-5z"/></svg>
                    <h3 class="text-xl font-bold text-gray-900">Turn Figma context into code</h3>
                </div>
                <div class="pl-9">
                    <p class="text-gray-600 mb-3 text-lg leading-relaxed">Our Figma MCP server lets you bring Figma context directly into your agentic coding tools.</p>
                    <a href="#" class="text-black font-medium border-b border-black hover:opacity-70 pb-0.5">Explore Figma MCP</a>
                </div>
            </div>

            <div class="group cursor-pointer opacity-50 hover:opacity-100 transition-opacity">
                 <div class="flex items-start gap-3 mb-2">
                    <h3 class="text-xl font-bold text-gray-900 pl-9">Publish custom websites—with or without code</h3>
                </div>
            </div>

            <div class="group cursor-pointer opacity-50 hover:opacity-100 transition-opacity">
                 <div class="flex items-start gap-3 mb-2">
                    <h3 class="text-xl font-bold text-gray-900 pl-9">Ship products faster with AI</h3>
                </div>
            </div>
        </div>

        <!-- Right Image -->
        <div class="flex-1 bg-[#1e1e1e] rounded-2xl overflow-hidden shadow-2xl min-h-[500px] relative p-8 font-mono text-sm">
            <div class="flex justify-between items-center text-gray-500 mb-6 border-b border-gray-700 pb-4">
                <span>CoLab / Profile</span>
                <div class="flex gap-2">
                    <div class="w-3 h-3 rounded-full bg-red-500"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                    <div class="w-3 h-3 rounded-full bg-green-500"></div>
                </div>
            </div>

            <div class="grid grid-cols-2 gap-8">
                <div class="text-gray-400 space-y-4">
                    <div class="flex items-center gap-2 text-green-400">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                        Called get_code_for_selection
                    </div>
                    <div class="flex items-center gap-2 text-green-400">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                        Called get_variable_defs
                    </div>
                     <div class="flex items-center gap-2 text-green-400">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                        Called get_code_connect_map
                    </div>
                     <div class="flex items-center gap-2 text-green-400">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                        Called get_metadata
                    </div>
                    
                    <div class="mt-8 pt-4 border-t border-gray-700">
                        <p class="text-gray-300">Add this profile page based on my selected Figma designs.</p>
                    </div>

                    <div class="mt-4 flex items-center gap-2 bg-gray-800 rounded px-3 py-2 w-max">
                        <span>Agent ^</span>
                    </div>
                </div>

                <!-- Preview of the profile page -->
                <div class="bg-white rounded-lg p-4 text-black transform rotate-1 translate-y-8 shadow-lg">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden">
                             <img src="https://ui-avatars.com/api/?name=Julia+Simmons" alt="Profile" />
                        </div>
                        <div>
                            <div class="font-bold text-lg">Julia Simmons</div>
                            <div class="text-xs text-gray-500">Member since Oct 12, 2022</div>
                        </div>
                    </div>
                    <div class="flex gap-2 mb-6">
                        <button class="bg-black text-white text-xs px-3 py-1 rounded-full">Follow</button>
                        <button class="border border-gray-300 text-xs px-3 py-1 rounded-full">Message</button>
                    </div>
                    <div class="text-xs font-bold mb-2">Recent Activity</div>
                    <div class="space-y-2">
                        <div class="flex gap-2 items-center text-[10px] text-gray-600 border-b border-gray-100 pb-2">
                            <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
                            <div>Julia left a comment on Field research on the American Pika</div>
                        </div>
                        <div class="flex gap-2 items-center text-[10px] text-gray-600 border-b border-gray-100 pb-2">
                            <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
                            <div>Julia updated the file Bacterial Water Quality Monitoring</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</section>
