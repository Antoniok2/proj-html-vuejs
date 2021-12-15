<template>
    <div class="jumbo2">
        <div class="download_app">
            <h3>Download Our</h3>
            <h4>Ordering App</h4>
            <div class="download">
                <div class="apple_google">
                    <span>
                        <font-awesome-icon icon="car" class="ico"></font-awesome-icon>
                        <div>
                            <h6>Download on the</h6>
                            <span>
                                App Store
                            </span>
                        </div>
                    </span>
                </div>
                <div class="apple_google">
                    <span>
                        <font-awesome-icon icon="car" class="ico"></font-awesome-icon>
                        <div>
                            <h6>GET IT ON</h6>
                            <span>
                                Google Play
                            </span>
                        </div>
                    </span>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
  name: 'Jumbotron2',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .jumbo2 {
        position: relative;
        width: 100%;
        height: 400px;
        background-color: yellow;
        background-image: url("../assets/images/app-ordering-scaled.jpg");
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        margin: 50px 0;

        .download_app {
            position: absolute;
            top: 30%;
            left: 20%;

            h3 {
                color: white;
            }

            h4 {
                font-size: 35px;
                color: #fcdc31;
            }

            .download {
                display: flex;
            }

            .apple_google {
                display: flex;
                width: 140px;
                margin-top: 30px;
                margin-right: 5px;
                background-color: black;
                color: white;
                border-radius: 5px;
                cursor: pointer;

                span {
                    display: flex;
                    align-items: center;
                    margin-right: 5px;

                    .ico {
                        margin: 5px 8px;
                        font-size: 25px;
                    }

                    div {
                        margin: 5px 2px;

                        h6 {
                            font-size: 8px;
                        }

                        span {
                            font-size: 15px;
                        }
                    }
                }
            }
        }
    }
</style>