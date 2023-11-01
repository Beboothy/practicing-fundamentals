<script>
    import Title from '$lib/Title.svelte'
    import Footer from '$lib/Footer.svelte'
    import '../../styles/global.css'
</script>

<header>
    <Title title="Practicing Fundamentals - Layout Reset" />
    <div class="links">
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/guides">Guides</a>
    </div>
</header>
<main>
    <slot></slot>
</main>

<Footer/>

<style>
    header {
        display: flex;
        justify-content: center;
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