<script>
    import Title from "$lib/Title.svelte";
    import Footer from "$lib/Footer.svelte";
    import "../../styles/global.css";
</script>

<header>
    <nav>
        <Title title="Practicing Fundamentals - Layout Reset" />
        <div class="links">
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/guides">Guides</a>
        </div>
    </nav>
</header>
<main>
    <slot />
</main>

<Footer />

<style>
    header {
        text-align: center;
        background-color: rgba(0,0,0,0.1);
        width: 100%;
    }

    nav {
        display: flex;
        align-items: center;
        max-width: 960px;
        margin: 0 auto;
    }

    main {
        max-width: 960px;
        margin: 20px auto;
    }

    .links {
        margin-left: auto;
    }

    a {
        margin-left: 10px;
    }

</style>
