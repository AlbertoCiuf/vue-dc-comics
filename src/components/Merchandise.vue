<template>
  <section class="merchandise">
    <div class="container">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <a href="#">digital comics</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <a href="#">dc merchandise</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <a href="#">subscription</a>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <a href="#">comic shop locator</a>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <a href="#">dc power visa</a>
        </li>
        
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name:'Merchandise'
}
</script>

<style lang="scss" scoped>
  section.merchandise {
    height: 160px;
    background-color: #2582FA;
    color: #fff;
    .container {
      width: 70%;
      margin: 0 auto;
      ul {
        height: 160px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        li {
          text-transform: uppercase;
        }
        li img {
          width: 50px;
          vertical-align: middle;
          margin-right: 20px;
        }
        li a {
          color: #fff;
          font-size: 18px;
        }
      }
    }

  }

</style>