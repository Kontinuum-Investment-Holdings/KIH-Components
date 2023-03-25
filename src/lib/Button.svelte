<script>
    import './app.css'
    import { Button } from '@svelteuidev/core';
    export let label = ""
    export let url = ""

    const newStyles = {
        fontFamily: "Centaur",
        fontSize: "12pt"
    };

</script>

<a href={url}>
<Button override={newStyles} radius="md" variant="outline" color="var(--theme-colour-dark)" class="center" ripple>{label}<slot></slot></Button>
</a>