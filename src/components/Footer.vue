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
                <img class="download_app" src="../assets/images/app-store-badge.png" alt="appstore">
                <img class="download_app" src="../assets/images/play-store-badge.png" alt="appstore">
            </div>
            <div class="bar">
                <h3>OPENING HOUR</h3>
                <nav>
                    <ul>
                        <li>
                            <a href="#">Mon - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Tue - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Wed - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Thur - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Fri - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Sat - <span class="color">10AM to 11PM</span></a>
                        </li>
                        <li>
                            <a href="#">Sun - <span class="color">10AM to 11PM</span></a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="bar position">
                <h3>VOUCHER</h3>
                <img class="voucher" src="../assets/images/footer-coupon.png" alt="sale">
                <span>Just Use The Code</span>
                <h2>FIRSTORDER</h2>
                <span>AtCheckout</span>
            </div>
        </div>
        <div class="end_footer">
            <img src="../assets/images/takeout-logo.png" alt="logo">
            <h2>Stay In The Loop</h2>
            <span>Sign up to receive up to date news and offers directly in your inbox:</span>
            <input type="text" placeholder="you@email.com">
            <button>SUBSCRIBE</button>
        </div>
        <div class="follow">
            <img src="../assets/images/facebook-f-brands.svg" alt="facebook">
            <img src="../assets/images/twitter-brands.svg" alt="twitter">
            <img src="../assets/images/instagram-brands.svg" alt="instagram">
            <img src="../assets/images/linkedin-in-brands.svg" alt="linkedin">
            <img src="../assets/images/youtube-brands.svg" alt="youtube">
            <img src="../assets/images/envelope-regular.svg" alt="email">
            <div class="copyright">
                <span><font-awesome-icon icon="copyright"></font-awesome-icon><span class="color">Copyryght 2012-2020|Avada Theme by</span> ThemeFusion<span class="color">|All Right Reserved|Powered by</span> WordPress</span>
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
                text-align: start;

                &.position {
                    text-align: center;

                    .voucher {
                        display: block;
                        width: 40%;
                        margin: 15px auto;
                        border-radius: 10px;
                    }
                }

                .download_app {
                    display: block;
                    width: 40%;
                    margin: 15px 0;
                    border: 1px solid white;
                    border-radius: 10px;
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

                        .color {
                            color: #dac528;
                        }
                    }
                }
            }
        }

        .end_footer {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100%;

            img {
                width: 10%;
            }

            h2 {
                color: #fcdc31;
                margin: 10px 0;
            }

            span {
                display: block;
                margin-bottom: 15px;
                color: #d1cacc;
                font-size: 15px;
            }

            input {
                width: 500px;
                padding: 8px 15px;
                border-radius: 20px;
            }

            button {
                width: 500px;
                margin-top: 15px;
                margin-bottom: 30px;
                padding: 8px;
                color: white;
                background-color: #ce1a26;
                border-radius: 20px;
                border: solid rgba(0, 0, 0, 0);
                cursor: pointer;
            }
        }

        .follow {
            width: 100%;
            text-align: center;
            padding-bottom: 50px;

            img {
                filter: invert(1);
                width: 15px;
                margin: 10px;
            }

            .copyright {
                font-size: 13px;

                span {
                    color: white;
                }

                .color {
                    color: #dac528;
                }
            }
        }
    }
</style>