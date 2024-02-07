<script>

export default{
  name: "Main",
  
}

</script>

<template>
 

<div> 
  <div class="content">
    <p>Content goes here</p>
  </div>
</div>

</template>

<style lang="scss" scoped>

div{
  display: flex;
  align-items: center;
  width: 100%;
  height: 150px;
  background-color: black;
  .content{
    margin: 0 auto;
    width: 80%;
      p{
        font-size: 20px;
        color: white;
      }
  }
}
</style>