<template>
  <div class="main-container">
    <h1>Gerenciar Pedidos:</h1>
    <Dasboard />
  </div>
</template>
<script>
import Dasboard from '../components/Dashboard'
export default {
  name: "Pedidos",
  components: {
    Dasboard
  }
}
</script>
<style scoped>
h1 {
  color: rgb(78, 78, 78);
}
</style>