<template>
<div id="board">
<sideBar/>
<dashBoardPartition/>
</div>
</template>
<script>
import sideBar from "../sideNavBar/sideBar.vue"
import dashBoardPartition from "./dashBoardPartition.vue"
export default{
    name:"dashBoardComponent",
    components:{
sideBar,
dashBoardPartition,
    },
    data(){
        return{

        }
    }
};
</script>
<style scoped>
#board{
    display:flex;
}
</style>