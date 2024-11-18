<script>
    import Navbar from "$lib/components/navbar/Navbar.svelte";
    let { children } = $props();
</script>

<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>

<main>
    <Navbar/>
    {@render children()}
</main>