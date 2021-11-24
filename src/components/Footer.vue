<template>
  <footer>

    <div class="f-top">
      <div class="container">
        <ul>
          <li class="big"><a href="#">dc comics</a></li>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>

          <li class="big"><a href="#">shop</a></li>
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>

        <ul>
          <li class="big"><a href="">dc</a></li>
          <li><a href="#">Terms Of Use</a></li>
          <li><a href="#">Privacy policy (New)</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>

        <ul>
          <li class="big"><a href="#">sites</a></li>
          <li><a href="">DC</a></li>
          <li><a href="">MAD Magazine</a></li>
          <li><a href="">DC Kids</a></li>
          <li><a href="">DC Univers</a></li>
          <li><a href="">DC Power Visa</a></li>
        </ul>

      </div>
    </div>

    <div class="f-bottom">
      <div class="container">
        <div class="sign-up">sign-up now!</div>
        <div class="social-links">
          <ul>
            <li class="big"><a href="#">follow us</a></li>
            <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
          </ul>
        </div>
      </div>
    </div>

  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
  footer {
    .f-top {
      background-image: url("../assets/img/footer-bg.jpg");
      .container {
        display: flex;
        background-image: url("../assets/img/dc-logo-bg.png");
        background-position: right;
        background-repeat: no-repeat;
        padding: 40px 0;
      }
      ul {
        padding-right: 50px;
      }
      ul li.big {
        text-transform: uppercase;
        font-weight: bold;
        font-size: 20px;
        padding: 15px 0;
        a{
          color: #fff;
          font-size: 20px;
        }
      }
      ul li a{
        color: #949494;
        font-size: 12px;
      }
    }
    .f-bottom {
      height: 140px;
      background-color: #303030;
      .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .sign-up{
          cursor: pointer;
          text-transform: uppercase;
          background: none;
          font-size: 18px;
          color: #fff;
          font-weight: 700;
          border: 2px solid #2582FA;
          padding: 20px;
        }
        .social-links ul{
          display: flex;
          align-items: center;
          li.big{
            text-transform: uppercase;
            font-weight: bold;
            font-size: 18px;
            padding-right: 20px;
            a {
              color: #2582FA;
            }
          }
          li {
            padding: 10px;
            img {
              vertical-align: middle;
            }
          }
        }
      }
    }
  }
</style>