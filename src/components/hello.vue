<template>
    <section class="hello_container">

        <h2>hello!</h2>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia cupiditate dolor adipisci blanditiis, nisi
            accusantium similique vel pariatur amet dignissimos harum laboriosam, velit excepturi quis repellendus ea?
            Aut, nobis porro?</p>


    </section>

</template>
<style scoped>
* {
    margin: 0;
    padding: 0;
}

.hello_container {
    width: 65vw;
    height: 100vh;
    margin: auto;
    margin-top: 8rem;
}

h2 {
    font-size: 7rem;
}

p {
    font-size: 1.5rem;
    letter-spacing: 0.1rem;
}

@media(max-width :768px) {
    .hello_container {
        margin-top: 4rem;
    }
}

@media(max-width :600px) {
    .hello_container {
        margin-top: 2rem;
    }
}

@media(max-width :425px) {
    .hello_container {
        margin-top: 1rem;
    }
}
</style>