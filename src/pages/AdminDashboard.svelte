<script>
    import Dashboard from '../components/Dashboard.svelte'
    import SideBar from '../components/SideBar.svelte';
    
</script>

<Dashboard theme='admin'>
    <SideBar theme='admin' slot='sidebar'/>
    <div slot="content"></div>
</Dashboard>
<style></style>