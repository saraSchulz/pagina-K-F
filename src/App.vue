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
    margin: 0;
  }
}
</style>
