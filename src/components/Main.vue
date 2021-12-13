<template>
    <div class="container">
        <PopularDishes/>
        <Jumbotron/>
        <Categories/>
    </div>
</template>

<script>
import PopularDishes from '@/components/PopularDishes.vue'
import Jumbotron from '@/components/Jumbotron.vue'
import Categories from '@/components/Categories.vue'

export default {
  name: 'Main',
  components: {
    PopularDishes,
    Jumbotron,
    Categories
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
