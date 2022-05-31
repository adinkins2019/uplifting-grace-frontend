<script>
    import Form from './Form.svelte'
    let username;
    let initpwd;
    let confirmpwd;
    let churchname;
    let email;

    function handleSubmit(event){
        event.preventDefault();
    }
</script>

<Form on:submit={handleSubmit}>
    <input bind:value={username} type="text" name="username" id="username">
    <input bind:value={email} type="email" name="email" id="email">
    <input bind:value={initpwd} type="password" name="initpwd" id="initpwd">
    <input bind:value={confirmpwd} type="password" name="confirmpwd" id="confirmpwd">
    <input bind:value={churchname} type="text" name="churchname" id="churchname">
    <button type="submit">Register</button>
    <button type="reset">Clear</button>
</Form>

<style>

</style>