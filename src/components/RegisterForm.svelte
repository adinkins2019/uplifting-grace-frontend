<script>
    import Form from './Form.svelte'
    let username;
    let initpwd;
    let confirmpwd;
    let churchname;

    function handleSubmit(event){
        event.preventDefault();
    }
</script>

<Form on:submit={handleSubmit}>
    <input type="text" name="username" id="username">
    <input type="email" name="email" id="email">
    <input type="password" name="initpwd" id="initpwd">
    <input type="password" name="confirmpwd" id="confirmpwd">
    <input type="text" name="churchname" id="churchname">
    <button type="submit">Register</button>
    <button type="reset">Clear</button>
</Form>

<style>

</style>