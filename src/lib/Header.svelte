<script>
    import Navbar from '$lib/Navbar.svelte';
</script>

<div class="header-box">
    <p>You can achieve anything with the right tools and assistance. Don't let not being an expert in one thing stop you from achieving your goals.</p>
</div>
<Navbar />

<style>
    @import url('https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap');
    .header-box p {
        font-family: "Indie Flower", cursive;
        font-weight: 400;
        font-style: normal;
        font-size: 1.2em;
        color: #fdebf3; /* Set text color to contrast with background */
    }

    .header-box {
        background-color: #48484b;
        padding: 20px;
        border-bottom: 1px solid #fdebf3;
        position: relative;
        text-align: center;
        align-items: center;
    }
</style>
