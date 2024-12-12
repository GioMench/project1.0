<template>
    <section class="navbar">
        <div class="navbar_left">
            <h1>giorgia mancini</h1>
            <h3>web developer</h3>
        </div>

        <div class="navbar_right">
            <ul>
                <li><a href="https://github.com/GioMench" target="_blank" rel="noopener noreferrer">git</a></li>
                <li><a href="https://www.linkedin.com/in/giorgia-mancini-dev97/" target="_blank"
                        rel="noopener noreferrer">linkedin</a></li>
                <li><a href="mailto:mancinigiorgiadev@gmail.com">contact</a></li>
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

        a {
            text-decoration: none;
            color: var(--vt-c-white-soft);
        }
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
        top: 2.33em;
        letter-spacing: 0.897em;

    }

    ul {
        font-size: smaller;
    }
}

@media (max-width:600px) {
    .navbar {
        display: block;
    }

    ul {
        font-size: xx-small;
        padding: 0;
    }

    h1 {
        font-size: 2em;
        position: relative;
    }

    h3 {
        font-size: 1.01em;
        position: absolute;
        top: 2.35em;
        letter-spacing: 0.897em;

    }
}

@media(max-width :425px) {
    h1 {
        font-size: 1.8em;
        position: relative;
    }

    h3 {
        font-size: 0.944em;
        position: absolute;
        top: 2.24em;
        letter-spacing: 0.897em;

    }
}
</style>
