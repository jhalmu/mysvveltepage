<script>
	import '$lib/global.css';
	import Carousel from '$lib/components/Carousel.svelte';
	import Nav from '$lib/components/Nav.svelte';
	import Card from '$lib/components/Card.svelte';
	import Nav_btm from '$lib/components/Nav_btm.svelte';
	import Divider from '$lib/components/Divider.svelte';
</script>

<Carousel />
<Nav />
<Divider />
<main
	class="container rounded-lg mx-auto max-w-screen-lg min-h-screen border-base-300 bg-base-200 flex flex-wrap items-baseline justify-center gap-2 overflow-x-hidden border bg-cover bg-top p-2"
	style="background-size: 5px 5px"
>
	<slot />
	<div class="flex flex-wrap justify-center gap-8 mt-12">
		<h1 class="flex flex-wrap container justify-center text-4xl font-light font-mono rotate-6 text-pink-400">Minä</h1>
		<p class="p-5 pl-10 pr-10">Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. Minulla on ominaisuuksia. Isoimmat ominaisuuteni ovat ominaisia omenaisille. </p>
		
	</div>
	<Divider />
	<div class="flex flex-wrap justify-center gap-8 mt-8">
		<h1 class="flex flex-wrap container justify-center text-4xl font-light font-mono">Projektit</h1>
		<Card /><Card /><Card /><Card /><Card /><Card />
	</div>
	<Divider />
	<div class="flex flex-wrap justify-center gap-8 mt-8 columns-2">
		<h1 class="flex flex-wrap container justify-center text-4xl font-light font-mono">Blogi</h1>
		<Card /><Card /><Card /><Card /><Card /><Card />
	</div>
</main>
<Nav_btm />
