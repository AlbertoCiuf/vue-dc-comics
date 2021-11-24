<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo">
      </a>
      <nav>
        <ul>
          <li><a href="#">characters</a></li>
          <li class="active"><a href="#">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news</a></li>
          <li><a href="#">shop</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
   data(){
    return{
      topNavLinks: [
        {
          
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  header {
    height: 120px;
    // background-color: teal;
    
    .container {
      height: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;

      img {
        width: 85%;
      }
    }

    ul {
      display: flex;
      li {
        padding: 0 15px;
        a {
          line-height: 100%;
          text-transform: uppercase;
          text-decoration: none;
          color: black;
          font-weight: 700;
       }
          
            
          
      li:hover a, li.active a {
        color: #2582FA;
        border-bottom: 2px solid #2582FA;

       }
    }

  }
 }

</style>



