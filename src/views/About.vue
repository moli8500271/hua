<template>
  <div class="about">
     <!-- 1.定义组件 2.渲染组件表 -->
     <input type="button" value="获取元素" @click="btn"/>
      <h3 id="h33" ref="myh3">zwwasdsdsdf</h3>
       <div>zwwasdfasdf</div>
  </div>
</template>
<script>
export default {
  
  data(){
    return{

    }
  },
  methods:{
     btn(){
       //用dom获取
      //  console.log(document.getElementById('h33').innerText);
      let aa=this.$refs.myh3.innerText;
      console.log(aa);
     }
  }
}
</script>
