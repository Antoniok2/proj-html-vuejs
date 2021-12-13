<template>
  <div class="container">
    <!-- Button header -->
    <div class="button">
      <div class="add_button"><span>+</span></div>
    </div>
    <!-- Barra di navigazione -->
    <div class="navigation_bar">
      <div class="logo">
        <img src="../assets/images/takeout-logo.png" alt="">
      </div>
      <nav class="menu">
        <ul>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Order Online</a>
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
            <a href="#">Carrello</a>
          </li>
        </ul>
      </nav>
    </div>
    <!-- ICONS -->
    <div class="icons">
      <div class="icone">
        <div class="icon_demos">
          <span><font-awesome-icon icon="folder-plus"></font-awesome-icon></span>
          <h6>Demos</h6>
        </div>
        <div class="icon_sale">
          <span>$39</span>
          <h6>On sale</h6>
        </div>
      </div>
    </div>
    <div class="jumbo_text">
      <span>Hungry?</span>
      <h2>Great Food</h2>
      <h3>Delivered</h3>
      <button>VIEW OUR MENU </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .button {
    display: flex;
    justify-content: flex-end;
    width: 100%;
    padding: 5px 10px;

    .add_button {
      position: relative;
      width: 40px;
      height: 40px;
      background-color: red;
      color: white;
      border-radius: 25px;
      text-align: end;
      cursor: pointer;

      span {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
    }
  }

  .navigation_bar {
    display: flex;
    justify-content: space-around;
    align-items: center;

    .logo img {
      width: 80%;
    }

    .menu ul li {
      display: inline-block;
      list-style: none;

      a {
        color: white;
        text-decoration: none;
        padding: 0 10px;
      }
    }
  }

  .icons {
    display: flex;
    justify-content: flex-end;
    margin: 10px;

    .icon_demos {
      margin: 2px 0;
      text-align: center;
      border: solid 1px black;
      background-color: white;
      border-radius: 5px;
      padding: 5px;
    }

    .icon_sale {
      text-align: center;
      border: solid 1px black;
      background-color: white;
      border-radius: 5px;
      padding: 5px;

      span {
        color: green;
      }
    }
  }

  .jumbo_text {
    position: absolute;
    left: 15%;
    width: 200px;
    height: 100px;

    span {
      color: white;
    }

    h2 {
      color: #f2d22f;
    }

    h3 {
      color: white;
    }

    button {
      font-size: 10px;
      background-color: red;
      color: white;
      padding: 5px 10px;
      border-radius: 20px;
      margin: 10px 0;
    }
  }
</style>
