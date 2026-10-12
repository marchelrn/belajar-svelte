<script>
    import Logo from './Logo.svelte';
    const name = 'Marchel';
    const content = '<p>Hello World</p>';
</script>
<style>
    h1 {
        color: red;
    }
</style>

<h1>Hello {name.toUpperCase()}!</h1>

{@html content}
<Logo />
