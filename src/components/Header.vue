<template>
  <header>
    <div class="container">
      <a href="#">
        <img src="../assets/img/dc-logo.png" alt="logo">
      </a>
      <nav>
        <ul>
          <li 
          v-for="(item, index) in topNavLinks" :key="`topNav${index}`"
          :class="{active : item.isActive}">
            <a :href="item.url">{{item.text}}</a>
          </li>
          
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
          url:'#',
          text:'characters',
          isActive: false
        },
        {
          url:'#',
          text:'comics',
          isActive: true
        },
        {
          url:'#',
          text:'movies',
          isActive: false
        },
        {
          url:'#',
          text:'tv',
          isActive: false
        },
        {
          url:'#',
          text:'games',
          isActive: false
        },
        {
          url:'#',
          text:'collectibles',
          isActive: false
        },
        {
          url:'#',
          text:'videos',
          isActive: false
        },
        {
          url:'#',
          text:'fans',
          isActive: false
        },
        {
          url:'#',
          text:'news',
          isActive: false
        },
        {
          url:'#',
          text:'shop',
          isActive: false
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  header {
    height: 120px;
    
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
          line-height: 117px;
          text-transform: uppercase;
          color: #454545;
          font-weight: 700;
        }
      }
      li.active a, li:hover a{
      color: #2582FA;
      }
      li.active, li:hover {
        border-bottom: 3px solid #2582FA;
      }

    }
  }

</style>



