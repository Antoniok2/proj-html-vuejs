<template>
<div class="container">
    <div class="banner">
        <div class="informations">
            <div class="info">
                <span><font-awesome-icon icon="clock"></font-awesome-icon></span>
                <span>DELIVERY</span>
            </div>
            <div class="info">
                <span><font-awesome-icon icon="hamburger"></font-awesome-icon></span>
                <span>OVER 100 DISHES</span>
            </div>
            <div class="info">
                <span><font-awesome-icon icon="mobile-alt"></font-awesome-icon></span>
                <span>IN APP ORDERING</span>
            </div>
            <div class="info">
                <span><font-awesome-icon icon="car"></font-awesome-icon></span>
                <span>FAST DELIVERY</span>
            </div>
        </div>
    </div>
    <h1>Our Most Popular Dishes</h1>
    <div class="popular_dishes">
        <div class="product">
            <img src="../assets/images/skin-on-fries.jpg" alt="fries">
            <h3>Skin On Fries</h3>
            <span>$3.00 - $6.00</span>
        </div>
        <div class="product">
            <img src="../assets/images/choco-cookie-frappe.jpg" alt="frappe">
            <h3>Choco Cookie Frappe</h3>
            <span>$4.99</span>
        </div>
        <div class="product">
            <img src="../assets/images/donut-burger.jpg" alt="burger">
            <h3>The Donat Burger</h3>
            <span>$6.99</span>
        </div>
    </div>
    <div class="start_order">
        <span>START YOUR ORDER</span>
    </div>
</div>
</template>

<script>
export default {
  name: 'PopularDishes',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container {
        position: relative;
        width: 75%;
        margin: 0 auto;

        .banner {
            position: absolute;
            top: -30px;
            width: 100%;
            height: 80px;
            background-color: white;

            .informations {
                display: flex;
                height: 100%;
                justify-content: space-around;
                align-items: center;

                .info span {
                    margin: 0 5px;
                }
            }
        }
        h1 {
            padding-top: 80px;
            padding-bottom: 20px;
            text-align: center;
        }
        .popular_dishes {
            display: flex;
            width: 100%;

            .product {
                width: calc((100% / 3) - 10px);
                margin: 0 auto;
                text-align: center;

                &:hover {
                transform: scale(1.05);
                }

                img {
                    width: 80%;
                }

                span {
                    color: red;
                }
            }
        }
        .start_order {
            text-align: center;
            margin: 20px 0;

            span {
                background-color: red;
                color: white;
                padding: 10px 20px;
                border-radius: 25px;
                font-size: 10px;
                cursor: pointer;
            }
        }
    }
</style>