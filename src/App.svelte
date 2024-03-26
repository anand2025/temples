<script>
	import Carousel from './SvelteCarousel.svelte' 
	import TempleDetails from './details.svelte';
	import Moredetails from './Moredetails.svelte';
  	import CollapsibleTempleDetails from './CollapsibleTempleDetails.svelte';
    import Footer from './Footer.svelte';
</script>
<main>
	<Carousel />
</main>
<TempleDetails/>
<CollapsibleTempleDetails/>
<Moredetails/>
<Footer/>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>