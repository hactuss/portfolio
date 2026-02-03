<script>
  import { flip } from "svelte/animate";
  import { fade } from "svelte/transition";

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

    background: #141414;
    background: linear-gradient(
      0deg,
      rgba(20, 20, 20, 1) 50%,
      rgba(34, 34, 34, 1) 74%,
      rgba(50, 50, 50, 1) 90%
    );
  }
</style>
