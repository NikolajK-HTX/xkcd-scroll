<script>
    import "bulma/css/bulma.css";
</script>

<div class="section">
    <div class="container is-max-desktop">
        <h1 class="title">xkcd scroll</h1>
        <p class="subtitle">
            Please use <a href="https://xkcd.com/">xkcd.com</a>
        </p>
    </div>
</div>

<div class="section">
    <div class="container is-max-desktop">
        {#each Array(5) as _, i}
            <div class="box">
                <p><strong>xkcd title {i}</strong></p>
                <div
                    class=" is-flex is-justify-content-center is-align-items-center"
                >
                    <img src="/placeholder.png" alt="A placeholder" />
                </div>
            </div>
        {/each}
    </div>
</div>
