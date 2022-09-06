<template>
  <header>
    <section>
      <nav>
        <h3>NEX GEN</h3>

        <ul>
          <li>HOME</li>
          <li>ABOUT</li>
          <li>SERVICES</li>
          <li>PRICING</li>
          <li>BLOG</li>
          <li>
            <button>GET IN TOUCH</button>
          </li>
        </ul>
      </nav>

      <h1>Lead~Customer</h1>

      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, consequuntur rem! Molestiae molestias cupiditate dignissimos, ab magnam totam eos, dolorem obcaecati, exercitationem ipsa dolorum.</p>

      <span>
        <button>GET IN TOUCH</button>
        <button>READ MORE</button>
      </span>
    </section>
  </header>
    
</template>

<script>
export default {
    name: 'MyHeader'
}
</script>

<style lang="scss">
  header{
    background-image: url(../assets/image/hero-image.png);
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    section{
      background-color: rgba(0, 0, 0, 0.5);
    }
    nav{
      display: flex;
      justify-content: space-between;
      color: white;
      padding: 80px;
      margin-bottom: 100px;
      }   
      ul{
        list-style: none;
        li{
          display: inline-block;
          margin: 0px 10px;
          button{
            border-color: transparent;
            background-color: #038483;
            color: white;
            padding: 8px;
            border-radius: 8px;
          }
        }
      }
    }
  h1{
    font-size: 40px;
    color: white;
    text-align: center;
    }
  p{
    color: white;
    text-align: center;
   padding: 30px;
   
  }
  span{
    display: flex;
    justify-content: center;
    
  }
  
</style>