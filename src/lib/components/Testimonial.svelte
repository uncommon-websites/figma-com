<script lang="ts">
  export let name: string;
  export let role: string;
  export let quote: string;
  export let logo: string; // Just text for now or svg
  export let color: string = "text-cyan-400";
</script>

<div class="max-w-[1200px] mx-auto px-6 py-24 flex flex-col md:flex-row gap-12 items-start">
  <div class="flex-1">
    <div class="{color} mb-6">
      <svg width="48" height="48" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
        <path d="M14.017 21L14.017 18C14.017 16.8954 14.9124 16 16.017 16H19.017C19.5693 16 20.017 15.5523 20.017 15V9C20.017 8.44772 19.5693 8 19.017 8H15.017C14.4647 8 14.017 8.44772 14.017 9V11C14.017 11.5523 13.5693 12 13.017 12H12.017V5H22.017V15C22.017 18.3137 19.3307 21 16.017 21H14.017ZM5.01697 21L5.01697 18C5.01697 16.8954 5.9124 16 7.01697 16H10.017C10.5693 16 11.017 15.5523 11.017 15V9C11.017 8.44772 10.5693 8 10.017 8H6.01697C5.46468 8 5.01697 8.44772 5.01697 9V11C5.01697 11.5523 4.56925 12 4.01697 12H3.01697V5H13.017V15C13.017 18.3137 10.3307 21 7.01697 21H5.01697Z" />
      </svg>
    </div>
    <h2 class="text-3xl md:text-5xl font-medium leading-tight tracking-tight text-gray-900">
      {quote}
    </h2>
  </div>
  <div class="w-full md:w-auto flex flex-col gap-4 min-w-[200px]">
    <div class="flex items-center gap-2 text-gray-900 font-bold text-xl">
        <!-- Logo placeholder -->
        {#if logo === 'perplexity'}
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 7l10 5 10-5-10-5zm0 9l2-1-2-1-2 1 2 1zm0 2l-10 5 10 5 10-5-10-5z"/></svg>
            <span>perplexity</span>
        {:else if logo === 'github'}
            <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.66-3.795-1.455-3.795-1.455-.54-1.38-1.335-1.755-1.335-1.755-1.095-.75.075-.735.075-.735 1.215.09 1.845 1.245 1.845 1.245 1.08 1.845 2.805 1.32 3.495 1.005.105-.78.42-1.32.765-1.62-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405 1.02 0 2.04.135 3 .405 2.28-1.56 3.285-1.23 3.285-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.285 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
            <span>GitHub</span>
        {/if}
    </div>
    <div class="flex items-center gap-3">
      <div class="w-10 h-10 rounded-full bg-gray-300 overflow-hidden">
        <!-- Avatar placeholder -->
        <img src={`https://ui-avatars.com/api/?name=${name}&background=random`} alt={name} class="w-full h-full object-cover" />
      </div>
      <div class="flex flex-col text-sm">
        <span class="font-semibold text-gray-900">{name}</span>
        <span class="text-gray-600">{role}</span>
      </div>
    </div>
  </div>
</div>
