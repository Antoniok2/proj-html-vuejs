<template>
    <div class="container">
        <PopularDishes/>
    </div>
</template>

<script>
import PopularDishes from '@/components/PopularDishes.vue'

export default {
  name: 'Main',
  components: {
    PopularDishes
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container {
        position: relative;
        width: 75%;
        margin: 0 auto;
    }
</style>
