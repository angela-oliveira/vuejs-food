<template>
  <Banner />
  <div class="main-container">
    <BurgerForm />
  </div>
</template>

<script>
import BurgerForm from '../components/BurgerForm'
import Banner from '../components/Banner'
export default {
  name: "Home",
  components: {
    Banner,
    BurgerForm
  }
}
</script>
