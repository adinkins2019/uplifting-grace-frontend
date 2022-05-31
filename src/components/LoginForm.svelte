<script>
   import Form from "./Form.svelte"
   let username;
   let password;

   function handleSubmit(event){
        event.preventDefault()
   }
</script>

<Form on:submit={handleSubmit}>
    <input type="text" name="username" id="username">
    <input type="password" name="password" id="password">
    <button type="submit">Login</button>
</Form>

<style>
    
</style>