<script>
   import Section from './Section.svelte';
   export let articles = [];
</script>

<main>
    {#each articles as article }
    <Section article={article} />
    {/each}
</main>