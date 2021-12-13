<template>
    <div class="menu_categories">
        <div class="button">
            <h5>VIEW THE FULL MENU</h5>
        </div>
        <h1>Menu Categories</h1>
        <div class="types_categories">
            <div class="type">
                <img src="../assets/images/appetizers-menu-background.jpg" alt="">
                <h6>APPETIZERS</h6>
            </div>
            <div class="type">
                <img src="../assets/images/burgers-menu-background.jpg" alt="">
                <h6>BURGERS</h6>
            </div>
            <div class="type">
                <img src="../assets/images/pizza-menu-background.jpg" alt="">
                <h6>PIZZAS</h6>
            </div>
            <div class="type">
                <img src="../assets/images/fries-menu-background.jpg" alt="">
                <h6>FRIES</h6>
            </div>
            <div class="type">
                <img src="../assets/images/sides-menu-background.jpg" alt="">
                <h6>SIDES</h6>
            </div>
            <div class="type">
                <img src="../assets/images/desserts-menu-background.jpg" alt="">
                <h6>DESSERT</h6>
            </div>
            <div class="type">
                <img src="../assets/images/beverages-menu-background.jpg" alt="">
                <h6>BEVERAGES</h6>
            </div>
            <div class="type">
                <img src="../assets/images/specials-menu-background.jpg" alt="">
                <h6>SPECIALS</h6>
            </div>
        </div>
        <div class="genre_menu">
            <div class="genere vegetarian">
                <font-awesome-icon icon="leaf" class="veget"></font-awesome-icon>
                <h5>Vegetarian</h5>
            </div>
            <div class="genere gluten_free">
                <font-awesome-icon icon="leaf" class="gluten"></font-awesome-icon>
                <h5>Gluten Free</h5>
            </div>
            <div class="genere dairy_free">
                <font-awesome-icon icon="leaf" class="dairy"></font-awesome-icon>
                <h5>Dairy free</h5>
            </div>
            <div class="genere keto_friendly">
                <font-awesome-icon icon="wine-bottle" class="keto"></font-awesome-icon>
                <h5>Keto Friendly</h5>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Categories',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .menu_categories {
        width: 70%;
        margin: 0 auto;

        .button {
            display: flex;
            justify-content: flex-end;

            h5 {
                text-align: end;
                background-color: red;
                color: white;
                padding: 10px 20px;
                border-radius: 20px;
                cursor: pointer;
            }
        }

        .types_categories {
            display: flex;
            justify-content: flex-start;
            flex-wrap: wrap;
            width: 100%;
            height: 100%;

            .type {
                position: relative;
                width: calc((100% / 4) - 10px);
                margin: 10px 5px;

                img {
                    width: 100%;
                    object-fit: cover;
                    filter: brightness(0.6);
                }

                h6 {
                    position: absolute;
                    top: 50%;
                    left: 50%;
                    transform: translate(-50%, -50%);
                    color: white;
                    font-size: 15px;
                }
            }
        }
        .genre_menu {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;

            .genere {
                text-align: center;
                margin-bottom: 20px;

                .veget {
                    color: green;
                }
                .gluten {
                    color: yellow;
                }
                .dairy {
                    color: aqua;
                }
                .keto {
                    color: rgb(151, 74, 74);
                }
            }
        }

    }

</style>