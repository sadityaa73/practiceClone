<template>
  <div>
  <headerCompo/>
  <dashBoardComponent/>
  </div>
</template>
<script>
import headerCompo from "./headerComponent/headerCompo.vue"
import dashBoardComponent from "./dashBoard/dashBoardComponent.vue"
export default {
  name:"MainPage",
  components:{
    headerCompo,
    dashBoardComponent,
  },
  data() {
    return {};
  },
};
</script>
<style scoped>
</style>