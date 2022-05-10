<template>
<div id="part1">
<div class="boxCotainer">
<p class= "heading">Dashboard</p>
<div class="dashboardItem">
<div class="boxes"></div>
<div class="boxes"></div>
<div class="boxes"></div>
<div class="boxes"></div>
</div>
</div>
<dashboardGraph/>
</div>
</template>
<script>
import dashboardGraph from "./dashboardGraph.vue"
export default{
    name:"dashBoardPartition",
    components:{
        dashboardGraph,
    },
    data(){
        return{

        }
    }
};
</script>
<style scoped>
#part1{
    display:flex;
    flex-direction:column;
    border: 1px solid black;
    display: flex;
    width: 100%;
    align-items: flex-start;
   
    padding:44px;
}
.boxCotainer{
        display: flex;
    flex-wrap: wrap;
    align-items: center;
    
    width: 100%;
    height: 218px;
    border-radius: 11px;
    margin-top: 18px;
}
.dashboardItem{
    display: flex;
    justify-content: space-between;
    width: 100%;
}
.boxes{
       width: 218px;
    height: 162px;
    border: 1px solid black;
    border-radius: 17px;}
.dashboardItem{
        display:flex;
    }
.heading{
        font-size: 20px;
    font-weight: 700;
    color: #263342;
    margin-bottom: 16px;
    margin-top: 24px;
    display: flex;
    }
</style>