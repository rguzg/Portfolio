<script>
    import { Router, Route } from "svelte-navigator";
    import Palette from "./pages/palette.svelte";
    import { Styles } from "sveltestrap";
</script>

<svelte:head>
    <title>Raúl Guzmán - Portfolio</title>
</svelte:head>

<Router>
    <Route path="/palette" component={Palette} primary={false} />
</Router>

<Styles />

<style>
    @font-face {
        font-family: "Ubuntu";
        src: url("https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap");
    }

    :global(body) {
        font-family: Ubuntu !important;
        user-select: none;
        padding: 1em;
        margin: 0 auto;
    }

    :global(h1) {
        font-size: 6rem !important;
    }

    :global(h2) {
        font-size: 5rem !important;
    }

    :global(h3) {
        font-size: 4rem !important;
    }

    :global(h4) {
        font-size: 3rem !important;
    }

    :global(h5) {
        font-size: 2rem !important;
    }
</style>
