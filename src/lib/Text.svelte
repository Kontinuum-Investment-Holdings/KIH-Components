<script>
    import './app.css'
    export let text = ""
</script>

<p>{text}<slot></slot></p>

<style>
    p{
        font-size: var(--font-size);
    }

    :root{
        --font-size: 16pt;
    }
</style>