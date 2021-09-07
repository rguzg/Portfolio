<script>
    import { Router, Route } from "svelte-navigator";
</script>

<svelte:head>
    <title>Raúl Guzmán - Portfolio</title>
</svelte:head>

<Router>
    <Route path="/test"/>
</Router>

<style>
    @font-face {
        font-family: "Ubuntu";
        src: url("https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap");
    }

    * {
        font-family: Ubuntu;
        user-select: none;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
    }

    h1 {
        color: #ff3e00;
        text-transform: uppercase;
        font-size: 4em;
        font-weight: 100;
    }

    @media (min-width: 640px) {
        main {
            max-width: none;
        }
    }
</style>
