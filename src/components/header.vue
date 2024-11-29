<template>
    <section class="navbar">
        <div class="navbar_left">
            <h1>giorgia mancini</h1>
            <h3>web developer</h3>
        </div>

        <div class="navbar_right">
            <ul>
                <li>git</li>
                <li>linkedin</li>
                <li>menu</li>
            </ul>
        </div>
    </section>
</template>

<style scope>
.navbar {
    color: var(--vt-c-white-soft);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

h1 {
    font-size: 2.5em;
    position: realtive;
}

h3 {
    position: absolute;
    top: 2.5em;
    letter-spacing: 0.897em;

}

h1,
h3 {
    margin: 0;
}

ul {
    list-style: none;
    display: flex;
    justify-content: space-between;


    li {
        padding-inline: 1em;
    }
}
</style>
