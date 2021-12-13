<template>
    <div class="jumbo2">
        <div class="download_app">
            <h3>Download Our</h3>
            <h4>Ordering App</h4>
            <div class="apple_google">
                <div>
                    <span><font-awesome-icon icon="car"></font-awesome-icon></span>
                    <h6>Download on the</h6>
                    <span>
                        App Store
                    </span>
                </div>
                <div>
                    <span><font-awesome-icon icon="car"></font-awesome-icon></span>
                    <h6>GET IT ON</h6>
                    <span>
                        Google Play
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

            .apple_google {
                display: flex;
                margin-top: 30px ;

                div {
                    width: 150px;
                    color: white;
                    background-color: black;
                    margin-top: 20px;
                    margin-right: 5px;
                    padding: 10px;
                    border-radius: 5px;
                }
            }
        }
    }
</style>