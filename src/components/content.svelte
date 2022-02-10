<script>
    import Cards from "./cards.svelte";
</script>

<div class="child">
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
    <Cards/>
</div>

<style>
    .child {
        display: grid;
        grid-gap: 1rem;
        width: 100%;
        margin: 0 auto;
        margin-top: 20px;
    }
</style>