<script>
    import Logo from './Logo.svelte';
    const name = 'Marchel';
</script>
<style>
    h1 {
        color: red;
    }
</style>

<h1>Hello {name.toUpperCase()}!</h1>

<Logo />
