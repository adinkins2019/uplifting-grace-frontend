<script>
    export let theme;
    import Header from './Header.svelte'
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
    main {
        display: grid;
        grid-template-rows: 1;
        grid-template-columns: minmax(2, 1fr);
        
    }
    /* Admin Styles */
    .admin aside{
        background: navy;
    }
    /* User Styles */
    .user aside{
        background: beige;
    }
</style>