<template>
    <div class="container">
        <PopularDishes/>
        <Jumbotron/>
        <Categories/>
        <Jumbotron2/>
        <News/>
    </div>
</template>

<script>
import PopularDishes from '@/components/PopularDishes.vue'
import Jumbotron from '@/components/Jumbotron.vue'
import Categories from '@/components/Categories.vue'
import Jumbotron2 from '@/components/Jumbotron2.vue'
import News from '@/components/News.vue'

export default {
  name: 'Main',
  components: {
    PopularDishes,
    Jumbotron,
    Categories,
    Jumbotron2,
    News
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
