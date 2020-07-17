<template>
  <div>
    <h1>Hello!! I am the second child....</h1>
    <h2>my name is yash .</h2>
    <h2>i am {{age}} years old .</h2>
  </div>
</template>

<script>
export default {
    props:{
        age : Number
    }
}
</script>

<style scoped>
    div{
        background-color: darkgray;
        margin: 3rem;
        padding: 2rem;
    }
</style>