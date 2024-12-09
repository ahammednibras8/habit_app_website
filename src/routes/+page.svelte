<script>
    import Hero from '$lib/componets/Hero.svelte';
    import Features from '$lib/componets/Features.svelte';
    import WhyChooseUs from '$lib/componets/WhyChooseUs.svelte';
</script>

<section class="container mx-auto px-6 py-16">
    <Hero />
    <Features />
    <WhyChooseUs />
</section>

<style>
    section {
        min-height: calc(100vh - 160px);
    }
    
    :global(body) {
        background: linear-gradient(to bottom, #000000, #121212);
    }
</style>