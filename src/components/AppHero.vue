<script>
export default {
    name: 'AppHero'
}
</script>

<template>
    <div class="jumbo">
        <span>
            Con un incredibile
        </span>
        <h2>
            JUMBOTRON
        </h2>
    </div>
</template>

<style scoped>
.jumbo {
    height: 50vh;
    padding: 5rem;
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
}

h2 {
    font-size: 4rem;
    align-self: flex-end;
    text-shadow: 0 0 15px var(--details-color);
}
</style>