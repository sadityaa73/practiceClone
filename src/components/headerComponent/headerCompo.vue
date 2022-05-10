<template>
<div id="header"><div class="header_text"><h2> hello from header.</h2></div></div>
</template>
<script>
export default{
    name:"headerCompo",
    data(){
        return{}
    }
};
</script>
<style scoped>
#header{
    border:1px solid black;
    height:74px ;
    with:100%;
}
.header_text{
    display:flex;
    align-content:center;
    justify-content:center;

}
</style>