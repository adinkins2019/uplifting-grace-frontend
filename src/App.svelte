<script>
	export let name;
	import LoginRegister from './pages/LoginRegister.svelte'
</script>

<main>
	<h1 class='text-6xl font-bold underline bg-blue-500'>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.de bg-blue-v/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<LoginRegister/>
</main>
