<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Logos from "$lib/components/Logos.svelte";
	import ValueProp from "$lib/components/ValueProp.svelte";
	import Solutions from "$lib/components/Solutions.svelte";
	import Integrations from "$lib/components/Integrations.svelte";
	import Testimonial from "$lib/components/Testimonial.svelte";
	import Security from "$lib/components/Security.svelte";
	import Stats from "$lib/components/Stats.svelte";
	import Footer from "$lib/components/Footer.svelte";

	export let data;
</script>

<svelte:head>
	<title>{data.title}</title>
	<meta name="description" content={data.description} />
	<meta property="og:title" content={data.title} />
	<meta property="og:description" content={data.description} />
	<meta property="og:type" content="website" />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={data.title} />
	<meta name="twitter:description" content={data.description} />
</svelte:head>

<main class="min-h-screen bg-[#F9F9F9]">
	<Navbar />
	<Hero />
	<Logos />
	<ValueProp />
	<Solutions />
	<Integrations />
	<Testimonial />
	<Security />
	<Stats />
	<Footer />
</main>

