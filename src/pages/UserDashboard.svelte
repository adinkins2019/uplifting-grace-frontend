<script>
    import Dashboard from '../components/Dashboard.svelte'
    import SideBar from '../components/SideBar.svelte';
    
</script>

<Dashboard theme='user'>
    <SideBar theme='user' slot='sidebar'/>
    <div slot="content"></div>
</Dashboard>
<style></style>