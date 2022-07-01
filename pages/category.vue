<template>
    <div class="container"> 
        <div class="flex">
            <div class="w-1/4  border">
                <Sidebar/>
            </div>
            <div class="w-3/4  border">
            </div>
        </div>
    </div>
</template>

<script>
import Sidebar from "../components/Sidebar.vue"
export default {
    name:"Category",
    components:{
        Sidebar
    }

}
</script>

<style>

</style>