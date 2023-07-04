<script>
    import { page } from '$app/stores';

    const q = $page.url.searchParams.get('q') ?? '';
</script>

<h1>
    hello to search page.
</h1>

{#if q}
<p>your query is {q}</p>
{/if}