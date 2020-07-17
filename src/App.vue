<template>
  <div class="kk">
    <h1>Hello!! I am the parent....</h1>
    <h2>my Name is chirag</h2>
    <Child :age="myage" @pleasechange="myage=21"></Child>
    <Child2 :age="myage"></Child2>
  </div>
</template>

<script>
import child from './child';
import Secondchild from './Secondchild';
export default {
  components:{
    Child : child,
    Child2 : Secondchild
  },
  data:function (){
    return{
      myage :15
    }
  },
}
</script>

<style scoped>
  h1{
    color: red;
  }
  div{
    margin: 3rem;
  }
  .kk{
    background-color: cornsilk;
    padding: 3rem;
  }
</style>>
