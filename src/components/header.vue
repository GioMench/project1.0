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

    .navbar_right2 {
        display: none;
    }

}

h1 {
    font-size: 2.5em;
    position: relative;
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

@media(max-width :768px) {
    h1 {
        font-size: 2em;
        position: relative;
    }

    h3 {
        font-size: 1.007em;
        position: absolute;
        top: 2.6em;
        letter-spacing: 0.897em;

    }
}

@media (max-width:600px) {
    .navbar {
        display: block;


    }

}
</style>
