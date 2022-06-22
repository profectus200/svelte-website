<script lang="ts">
	import About from "./pages/About.svelte";
    import Intro from './pages/Intro.svelte'
    import Portfolio from "./pages/Portfolio.svelte";
    import Contact from "./pages/Contact.svelte";
    import Recipe from "./pages/Recipe.svelte";
</script>

<main>
    <Intro />
    <About />
    <Portfolio />
    <Contact />
    <Recipe />
</main>

<style>
	@font-face {
		font-family: "Xirod";
		src: url("/webfonts/xirod.woff2") format("woff2"),
		url("/webfonts/xirod.woff") format("woff");
		font-weight: normal;
		font-style: normal;
		font-display: swap;
	}

	:global(body) {
        padding: 0;
		margin: 0;
		overflow-x: hidden;
		text-shadow: 0 0 7px white,
		0 0 42px aqua,
		0 0 82px aqua;
	}
</style>