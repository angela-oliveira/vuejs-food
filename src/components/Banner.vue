<template>
  <div id="main-banner">
    <h1>Monte seu Hamburguer</h1>
  </div>
</template>
<script>
export default {
  name: "Banner"
  
}
</script>
<style scoped>

  #main-banner {
    background-position: 0 -250px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #main-banner h1 {
    margin-top: 10px;
    color: rgb(78, 78, 78);
    text-align: center;
    border-radius: 30px;
    padding: 20px 40px;
  }
</style>