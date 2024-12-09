<script>
    import '../app.css';
    import Navigation from '$lib/componets/Navigation.svelte';
    import Footer from '$lib/componets/Footer.svelte';
    
    let { children } = $props();
</script>

<div class="min-h-screen bg-black text-white">
    <Navigation />

    <main>
        {@render children()}
    </main>

    <Footer />
</div>

<style>
    :global(html) {
        scroll-behavior: smooth;
    }
</style>