<script lang="ts">
	import Billing from "$lib/sections/Billing.svelte";
  import Business from "$lib/sections/Business.svelte";
	import CardDeal from "$lib/sections/CardDeal.svelte";
	import Clients from "$lib/sections/Clients.svelte";
	import Cta from "$lib/sections/CTA.svelte";
	import Footer from "$lib/components/Footer.svelte";
  import Hero from "$lib/sections/Hero.svelte";
	import Stats from "$lib/sections/Stats.svelte";
	import Testimonials from "$lib/sections/Testimonials.svelte";

  
</script>

<div>
  <Hero/>
</div>

<div>
  <Stats/>
  <Business/>
  <Billing/>
  <CardDeal/>
  <Testimonials/>
  <Clients/>
  <Cta/>
  <Footer/>
</div>
