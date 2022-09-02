<template>
    <div class="jumbo">
        <h2>Hello Jumbo!</h2>
        <p>
            This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured
            content or information.
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia, saepe.
        </p>
        <button class="my_btn">Learn more</button>
    </div>
</template>

<script>
export default {
    name: 'MyJumbo',
}
</script>

<style lang="scss">
h2 {
    text-align: center;
    font-size: 2rem;
}

.jumbo {
    background-color: lightgray;
    padding: 1rem;
    text-align: left;
}

.jumbo p {
    padding: 1.75rem 1rem;
}

p:first-of-type {
    border-bottom: 1px solid rgb(174, 174, 174);
    font-weight: bold;
}

.my_btn {
    border-radius: 0.5rem;
    background-color: blue;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    font-size: 1.25rem;
    margin: 1rem;
}
</style>