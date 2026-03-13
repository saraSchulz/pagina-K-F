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
    <a href="#" class="story">
      <h3>Our Story</h3>
    </a>
    <a href="#" class="detals">
      <h3>The Detals</h3>
    </a>
    <a href="#" class="rspv">
      <h3>RSPV</h3>
    </a>
    <a href="#" class="regitry">
      <h3>Registry</h3>
    </a>

  </section>
  <section class="registry">
    <h3>Registry</h3>
    <p>
      Your presence is the most cherished gift. Should you wish to contribute, we've created a honeymoon registry to
      help us embark on a memorable adventure to the Amalfi Coast.
    </p>
    <button>
      <a href="#">
        GO to Registry
      </a>
    </button>
  </section>
  <section class="message">
    <h3>
      message
    </h3>
    <p>
      Here you can leave a message, advice, a memory, or just a few special words for us. Each message will be like a
      little star kept in our history, illuminating this very important moment. We will be very happy to read everything
      you want to share. Your affection is part of this chapter of our lives.
    </p>
    <button>
      <a href="#">
      leave message
      </a>
    </button>
  </section>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #000;
  width: 100%;

  margin: 0;
  box-shadow: 0 0 75px rgba(0, 0, 0, 0.5);

  & img {
    margin: 20px;
  }

  & ul {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px;

    & li {
      color: #fff;
      list-style: none;
      margin: 10px;
      font-size: 30px;
      text-decoration: underline 1px solid;
    }
  }
}

.banner {
  width: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;

  & h2 {
    color: #fff;
    font-size: 100px;
    font-weight: normal;
    margin: 60px 0 0 0;

    & span {
      color: #FFF94D;
    }
  }

  & h3 {
    color: #fff;
    font-size: 25px;
    font-weight: normal;
    margin: 0 0 60px 0;
  }
}

.intro {
  background: url(/public/flowers.png ) no-repeat center center/cover;
  min-height: 800px;
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;

  & p {
    font-size: 45px;
    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    width: 50%;
  }
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  text-align: center;

  & a {
    width: 35%;
    padding: 300px 0;
    margin: 50px;
    box-shadow: 0 0 75px rgba(0, 0, 0, 0.705);
    cursor: pointer;
    text-decoration: none;

    & h3 {
      color: #fff;
      text-shadow: 0 0 30px #ffffffaf;
      text-decoration: underline 1.5px;
      font-size: 45px;
      font-weight: normal;
      transition: all 1s ease;
    }
    & h3:hover{
      color: #000;
    }

  }

  & .story {
    background: url(/public/folha.png) no-repeat center center/cover;

  }

  & .detals {
    background: url(/public/carta.png) no-repeat center center/cover;
  }

  & .rspv {
    background: url(/public/aliacas.png) no-repeat center center/cover;
  }

  & .regitry {
    background: url(/public/book.png) no-repeat center center/cover;
  }
}

.registry {
  background: url(/public/flores.png ) no-repeat center center/cover;
  min-height: 800px;
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  margin: 50px 0;

  & h3 {
    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    font-weight: normal;
  }

  & p {

    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    width: 65%;

  }
  & button{
    background-color: #ff590083;
    border: 5px solid #fff;
    color: #fff;
    font-family: "Marcellus SC", serif;
    font-size: 30px;
    border-radius: 40px;
    padding: 10px 100px;
    cursor: pointer;
    transition: all 0.7s ease;
  }
  & button:hover{
    background-color: #ffffff81;
    color: #000;
  }
}
.message {
  background: url(/public/mesage.png ) no-repeat center center/cover;
  min-height: 800px;
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  margin: 100px 0;

  & h3 {
    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    font-weight: normal;
  }

  & p {

    color: #fff;
    text-shadow: 0 0 30px #ffffffaf;
    font-size: 45px;
    width: 65%;

  }
  & button{
    background-color: #ff590083;
    border: 5px solid #fff;
    color: #fff;
    font-family: "Marcellus SC", serif;
    font-size: 30px;
    border-radius: 40px;
    padding: 10px 100px;
    cursor: pointer;
    transition: all 0.7s ease;
  }
  & button:hover{
    background-color: #ffffff81;
    color: #000;
  }
}

</style>
