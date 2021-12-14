<template>
    <div class="container">
        <div class="latest_news">
            <h2>Latest News</h2>
            <span>READ MORE NEWS</span>
        </div>
        <div class="items">
            <div class="item">
                <img src="../assets/images/pancake-burger.jpg" alt="">
                <h1>NEW: The Pancake Burger</h1>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non quaerat commodi officia, mollitia unde earum? Molestiae voluptatibus quaerat</span>
            </div>
            <div class="item">
                <img src="../assets/images/new-milkshake-menu.jpg" alt="">
                <h1>New Milkshake Menu</h1>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non quaerat commodi officia, mollitia unde earum? Molestiae voluptatibus quaerat</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'News',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container {
        width: 75%;
        margin: 0 auto;

        .latest_news {
            display: flex;
            justify-content: space-between;
            margin: 0 75px;

            span {
                background-color: red;
                color: white;
                padding: 5px 10px;
                border-radius: 20px;
                font-size: 15px;
                cursor: pointer;
            }
        }

        .items {
            display: flex;
            width: 100%;
            margin: 40px 0;
            
            .item {
                display: flex;
                justify-content: center;
                align-items: center;
                flex-direction: column;
                width: 48%;
                margin: 10px auto;

                img {
                    width: 80%;
                }

                h1 {
                    font-size: 30px;
                    margin: 5px 0;
                }

                span {
                    width: 70%;
                    text-align: center;
                    color: #93a8b4;
                }
            }
        }
    }
</style>