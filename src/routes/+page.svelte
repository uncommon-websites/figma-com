<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import LogoBanner from "$lib/components/LogoBanner.svelte";
  import FeatureOne from "$lib/components/FeatureOne.svelte";
  import Testimonial from "$lib/components/Testimonial.svelte";
  import FeatureTwo from "$lib/components/FeatureTwo.svelte";
  import FeatureThree from "$lib/components/FeatureThree.svelte";
  import Community from "$lib/components/Community.svelte";
  import BigCTA from "$lib/components/BigCTA.svelte";
  import Templates from "$lib/components/Templates.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<main class="font-sans antialiased text-gray-900 bg-white">
  <Navbar />
  
  <Hero />
  
  <LogoBanner />
  
  <FeatureOne />
  
  <Testimonial 
    quote="Figma helps us paint the north star for the whole company. It keeps everyone aligned and excited."
    name="Henry Modisett"
    role="Head of Design"
    logo="perplexity"
    color="text-[#0ACF83]"
  />
  
  <FeatureTwo />
  
  <FeatureThree />
  
  <Testimonial 
    quote="Nearly everything that designers and developers need is available in Figma."
    name="Diana Mounter"
    role="Head of Design"
    logo="github"
    color="text-[#d9b310]"
  />
  
  <Community />
  
  <BigCTA />
  
  <Templates />
  
  <Footer />
</main>


