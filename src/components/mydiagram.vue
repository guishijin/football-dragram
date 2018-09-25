<template>
  <div class="mydiagram">
    <img src="../assets/header.png">
    <operation></operation>
    <div class="main">
      <mytools class="menu" :type="type"></mytools>
      <myground class="myground" ref="ground" :type="type" :index="index"></myground>
    </div>
  </div>
</template>

<script>
  import myoperation from "./myoperation.vue";
  import mytools from "./mytools.vue";
  import myground from "./myground.vue";
  export default {
    name: 'mydiagram',
    components:{
      myoperation,
      mytools,
      myground
    },
    data () {
      return {

      }
    },
    computed:{
      type(){
        return this.$route.params.type;
      },
      index(){
        return this.$route.params.index;
      }
    }
  }
</script>

<style lang="scss" scoped>
  img{
    width: 100%;
  }
  .main{
    display: flex;
    width: 100%;
  }
  .menu{
    flex: 2;
  }
  .myground{
    flex: 11;
  }
</style>
