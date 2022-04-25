<template>
  <div>
    <h1>this is a {{mes}} info</h1>
    <button class="btn" @click="handleClick">点击发射</button>
  </div>
</template>

<script>
export default {
  name:'About',
  data(){
    return{
      mes:"README.md"
    }
  },
  methods:{
    handleClick(){
      alert('我已出仓，感觉良好')
    }
  }

}
</script>

<style>
  .btn{
    width:80px;
    height: 50px;
  }
</style>