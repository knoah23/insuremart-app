<script>
    import Content from "../components/content.svelte";
    import Head from "../components/head.svelte";
    import Tab from "../components/tab.svelte";
</script>

<svelte:head>
    <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700;800&display=swap" rel="stylesheet">
</svelte:head>

<main>
    <Head/>
    <Content/>
    <Tab/>
</main>

<style>
    main {
        font-family: 'Raleway';
        padding: 0 20px;
    }
</style>
