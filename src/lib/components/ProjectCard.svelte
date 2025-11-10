<script>
    export let title;
    export let discription;
    export let url;
    export let buildtime;
    export let url_gh;
</script>

<main>
    <h2>{title}</h2>
    <p>started {buildtime}</p>
    <p>{discription}</p>
    <div>
        <a href={url}>Visit ⇱</a>
        <a href={url_gh}>Source ⇱</a>
    </div>
</main>

<style>
    main {
        background-color: transparent;
        color: white;
        border: white solid 1px;
        border-radius: 10px;
        padding: 5px;
        margin-bottom: 3%;
        backdrop-filter: blur(5px);
    }
</style>
