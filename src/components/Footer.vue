<template>
    <div class="container">
        <div class="navigation_bars">
            <div class="bar">
                <h3>ORDER ONLINE</h3>
                <nav>
                    <ul>
                        <li>
                            <a href="#">Appetizers</a>
                        </li>
                        <li>
                            <a href="#">Burgers</a>
                        </li>
                        <li>
                            <a href="#">Pizza</a>
                        </li>
                        <li>
                            <a href="#">Fries</a>
                        </li>
                        <li>
                            <a href="#">Sides</a>
                        </li>
                        <li>
                            <a href="#">Dessert</a>
                        </li>
                        <li>
                            <a href="#">Beverages</a>
                        </li>
                        <li>
                            <a href="#">Specials</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="bar">
                <h3>NAVIGATE</h3>
                <nav>
                    <ul>
                        <li>
                            <a href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">Alternate Home</a>
                        </li>
                        <li>
                            <a href="#">Menu</a>
                        </li>
                        <li>
                            <a href="#">About</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                        <li>
                            <a href="#">Cart</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="bar">
                <h3>INFORMATION</h3>
                <nav>
                    <ul>
                        <li>
                            <a href="#">My Account</a>
                        </li>
                        <li>
                            <a href="#">Terms Of Service</a>
                        </li>
                        <li>
                            <a href="#">Privacy Policy</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="bar">
                <h3>OPENING HOUR</h3>
                <nav>
                    <ul>
                        <li>
                            <a href="#">Mon - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Tue - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Wed - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Thur - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Fri - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Sat - 10AM to 11PM</a>
                        </li>
                        <li>
                            <a href="#">Sun - 10AM to 11PM</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="bar">
                <h3>VOUCHER</h3>
                <img src="../assets/images/footer-coupon.png" alt="sale">
                <span>Just Use The Code</span>
                <h2>FIRSTORDER</h2>
                <span>AtCheckout</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Footer',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container {
        width: 100%;
        background-image: url("../assets/images/footer-background-scaled.jpg");
        background-position: center center;
        background-size: cover;
        background-repeat: no-repeat;

        .navigation_bars {
            display: flex;
            width: 90%;
            margin: 0 auto;

            h3 {
                color: white;
            }

            .bar {
                width: 20%;
                margin: 50px 10px;
                text-align: center;

                img {
                    display: block;
                    width: 50%;
                    margin: 15px auto;
                }

                span {
                    color: white;
                }

                h2 {
                    color: #efd22d;
                    font-size: 20px;
                }

                nav ul li {
                    list-style: none;
                    margin: 10px 0;

                    a {
                        color: white;
                        text-decoration: none;
                        font-size: 15px;
                    }
                }
            }
        }
    }
</style>