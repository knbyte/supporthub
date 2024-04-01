<script>
    import Header from '$lib/Header.svelte';
    import Footer from '$lib/Footer.svelte';
</script>
<div class="layout">
    <Header />
    <br>
    <br>
    <slot />
    <br>
    <br>
    <br>
    <br>
    <Footer />
</div>