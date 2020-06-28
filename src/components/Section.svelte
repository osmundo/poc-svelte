<script>
    export let article = {};
</script>

<section>
    <h2>{article.title}</h2>
    {#each article.article as line }
        <p>{line}</p>
    {/each}
</section>