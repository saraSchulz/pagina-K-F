<script setup lang="ts">

</script>

<template>
<header>
  <h1 class="logo">
    <img src="/public/logo.png" alt="logo">
  </h1>
  <nav>
    <ul>
      <li>Home</li>
      <li>Our Story</li>
      <li>Detals</li>
      <li>RSPV</li>
    </ul>
  </nav>
</header>
<section class="banner">
  <h2>
    Karen<span>&</span>Felipe
  </h2>
  <h3>june, 23rd 2026</h3>
</section>
<section class="intro">
  <p>
    With love and gratitude, we invite you to share in the joy of our wedding day.
  </p>
  <p>
    Tuesday, june, 2026 The Golden Elm Manor, St. Augustine, New York
  </p>
</section>
<section class="cards">
  <div class="story">
    <h3>Our Story</h3>
  </div>
  <div class="detals">
    <h3>The Detals</h3>
  </div>
  <div class="rspv">
    <h3>RSPV</h3>
  </div>
  <div class="regitry">
    <h3>Registry</h3>
  </div>
</section>
<section class="registry">
  <h3>Registry</h3>
  <p>
    Your presence is the most cherished gift. Should you wish to contribute, we've created a honeymoon registry to help us embark on a memorable adventure to the Amalfi Coast.
  </p>
  <button>GO to Registry</button>
</section>
</template>

<style scoped>
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #000;
  width: 100%;

  margin: 0;
  box-shadow: 0 0 75px rgba(0, 0, 0, 0.5);
  & img{
    margin: 20px;
  }

  & ul{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px;
  & li{
    color: #fff;
    list-style: none;
    margin: 10px;
    font-size: 30px;
    text-decoration: underline 1px solid;
  }
  }
}
.banner{
  width: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  & h2{
    color: #fff;
    font-size: 100px;
    font-weight: normal;
    margin: 60px 0 0 0;
    & span{
      color:  #FFF94D;
    }
  }
  & h3{
    color: #fff;
    font-size: 25px;
    font-weight: normal;
    margin: 0 0 60px 0;
  }
}
.intro{
  background: url(/public/flowers.png ) no-repeat center center/cover;
  min-height: 800px;
  align-items: center;
  display: flex ;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  & p{
    font-size: 45px;
    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    width: 50%;
  }
}
.cards{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  text-align: center;
  & div{
    width: 35%;
    padding: 300px 0;
    margin: 50px;
    box-shadow: 0 0 75px rgba(0, 0, 0, 0.705);
     & h3{
      color: #fff;
      text-shadow: 0 0 30px #ffffffaf;
      text-decoration: underline 1.5px;
      font-size: 45px;
      font-weight: normal;
     }

  }
  & .story{
    background: url(/public/folha.png) no-repeat center center/cover;

  }
  & .detals{
    background: url(/public/carta.png) no-repeat center center/cover;
  }
  & .rspv{
    background: url(/public/aliacas.png) no-repeat center center/cover;
  }
  & .regitry{
    background: url(/public/book.png) no-repeat center center/cover;
  }
}
.registry{
  background: url(/public/flores.png ) no-repeat center center/cover;
  min-height: 800px;
  align-items: center;
  display: flex ;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  & h3{
    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    font-weight: normal;
  }
  & p{

    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    width: 70%;
    
  }
}
</style>
