<img src="https://media1.tenor.com/m/mc3OyxhLazUAAAAC/doggo-doge.gif" alt="" />
<main>
    <p>this is text</p>
</main>

<style>
    @layer content, background;
    * {
        margin: 0;
    }
    @layer content {
        main {
            position: absolute;
            top: 10px;
            width: 250px;
            height: 250px;
            border: solid white 2px;
            border-radius: 7px;
            background-color: rgba(0 0 0 0.6);
            /*backdrop-filter: blur(10px);*/
        }
        img {
            filter: brightness(0.5);
        }
    }
    @layer background {
    }
</style>
