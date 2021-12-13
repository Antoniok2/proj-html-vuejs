<template>
    <div class="jumbo">
    </div>
</template>

<script>
export default {
  name: 'Jumbotron',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .jumbo {
        width: 100%;
        height: 400px;
        background-color: yellow;
        background-image: url("../assets/images/first-order-background-scaled.jpg");
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        margin: 50px 0;
    }
</style>