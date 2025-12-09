<script lang="ts">
  // Navbar
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/95 backdrop-blur-sm border-b border-gray-100">
  <div class="max-w-[1440px] mx-auto px-4 h-16 flex items-center justify-between">
    <!-- Left: Logo & Menu -->
    <div class="flex items-center gap-8">
      <a href="/" class="text-black hover:opacity-80 transition-opacity">
        <svg class="w-6 h-9" viewBox="0 0 24 36" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6H6V18H12Z" fill="#1ABCFE"/>
          <path d="M6 18C2.68629 18 0 15.3137 0 12C0 8.68629 2.68629 6 6 6H12V18H6Z" fill="#0ACF83"/>
          <path d="M6 30C2.68629 30 0 27.3137 0 24C0 20.6863 2.68629 18 6 18H12V30H6Z" fill="#A259FF"/>
          <path d="M18 6C21.3137 6 24 3.31371 24 0C24 0 21.3137 0 18 0H12V6H18Z" fill="#F24E1E"/>
          <path d="M6 6C2.68629 6 0 3.31371 0 0C0 0 2.68629 0 6 0H12V6H6Z" fill="#F24E1E"/>
        </svg>
        <!-- Correct Figma Logo SVG construction -->
        <div class="relative w-[18px] h-[27px] hidden">
             <!-- Using inline SVG instead above -->
        </div>
      </a>

      <div class="hidden md:flex items-center gap-1 text-[15px] font-medium text-gray-900">
        <button class="px-3 py-2 hover:bg-gray-100 rounded-lg flex items-center gap-1">
          Products
          <svg class="w-3 h-3 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
        </button>
        <button class="px-3 py-2 hover:bg-gray-100 rounded-lg flex items-center gap-1">
          Solutions
          <svg class="w-3 h-3 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
        </button>
        <button class="px-3 py-2 hover:bg-gray-100 rounded-lg flex items-center gap-1">
          Community
          <svg class="w-3 h-3 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
        </button>
        <button class="px-3 py-2 hover:bg-gray-100 rounded-lg flex items-center gap-1">
          Resources
          <svg class="w-3 h-3 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
        </button>
        <a href="#" class="px-3 py-2 hover:bg-gray-100 rounded-lg">Pricing</a>
      </div>
    </div>

    <!-- Right: Actions -->
    <div class="flex items-center gap-2 md:gap-4">
      <a href="#" class="hidden md:block text-[15px] font-medium text-gray-900 hover:text-gray-700 px-2">Log in</a>
      <a href="#" class="hidden md:block text-[15px] font-medium text-gray-900 border border-gray-300 rounded-lg px-4 py-2 hover:bg-gray-50 transition-colors">Contact sales</a>
      <a href="#" class="text-[15px] font-medium text-white bg-black rounded-lg px-4 py-2 hover:bg-gray-800 transition-colors">Get started for free</a>
    </div>
  </div>
</nav>
