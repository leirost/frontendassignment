<style>
    body {
        margin: 0;
        padding: 20px;
        background-image: url(/src/source/background.png);
        display: grid;
    }

    @font-face {
        font-family: "My Custom Font";
        src: url(/src/source/PlayfairDisplay-VariableFont_wght.ttf) format("truetype");
    }
    a {
        margin: 20px;
    }
    h1 {
        text-align: center;
        font-size: 1.7em;
        background-color: #87CEEB;
        font-family: "My custom Font";
    }

    nav{
        text-align: center;
        font-family: "My Custom Font";
        font-size: 25px;
    }

</style>
<body>
    <main>
        <h1 style="color:blue;" > ✨Hello and welcome!✨ </h1>
    </main>
    <nav>
        <a href="/Profile">Profile</a>
        <span>🐱</span>
        <a href="/Interests">My Interests!</a>
    </nav>
    <slot />
</body>
