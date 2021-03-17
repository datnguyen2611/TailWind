<script type="ts">
    import Tailwind from "./Tailwind.svelte";
    import {routes, Router } from 'svelte-hash-router';
    import Home from './view/Home.svelte';
    import About from './view/About.svelte';
    import DarkMode from './view/dark-mode.svelte';
    routes.set({
        '/':{
            'home': Home,
            'about': About,
            'dark-mode' :DarkMode,
  } 
})
</script>
<Router/>
<Tailwind />

