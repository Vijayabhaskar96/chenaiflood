<script>
    export let large = true;
</script>

<div>
    <h2>Tips</h2>
    <ol>
        {#if large}
            <li>Check for replies under the tweets</li>
        {/if}
        <li>
            Make sure search results are sorted by "Latest"
            <br />
            <img src="sort-click-here.jpg" alt="" />
        </li>
    </ol>
</div>
