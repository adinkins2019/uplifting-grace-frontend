script>
    export let theme;
</script>
<Header />
<main class={theme === 'admin'? 'admin': 'user'}>
    <aside>
        <slot name="sidebar"></slot>
    </aside>
    <section>
        <slot name="content"><!-- optional fallback --></slot>
    </section>
    
</main>
<style>
    /* Admin Styles */


    /* User Styles */
</style>