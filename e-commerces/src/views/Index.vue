<template>
  <head>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
  </head>
  <header>
    <div class="wrapper">
        <nav class="menu">
          <h1>CAMCLOTHE</h1>
            <ul>
              <li><a href="#"><RouterLink to="/">CHILDREN</RouterLink></a></li>
              <li><a href="#"><RouterLink to="/about">MAN</RouterLink></a></li>
              <li><a href="#"><RouterLink to="/product">WOMAN</RouterLink></a></li>
              <li><a href="#"><RouterLink to="/product">CONTACT</RouterLink></a></li>
            </ul>
          <!-- <button @click="$emit('checkout')">Go to checkout</button> -->
            <input type="text" placeholder="Search" class="text"><i class="fa-solid fa-magnifying-glass search"></i><i class="fa-solid fa-cart-shopping cart"></i>
        </nav>
    </div>
  </header>
  <RouterView />
</template>
<style>
  .cart{
    font-size: 25px;
    cursor: pointer;
    margin-left: 10px;
    margin-top: 25px;
  }
  .search{
    font-size: 25px;
    margin-left: -30px;
    margin-top: 25px;
    cursor: pointer;
  }
  .text{
    width: 150px;
    height: 60px;
    border-radius: 5px;
    margin-top: 5px;
  }
  input{
    padding: 0px 5px;
  }
  .menu{
    width: 100%;
    height: 70px;
    background-color: rgb(215, 215, 21);
    display: flex;
    border-radius:5px ;
  }
  .menu h1{
    color: red;
    font-size: 40px;
    margin: 15px 20px;
  }
  .menu ul li{
    list-style-type: none;
    float: left;
    margin: 25px auto;
    margin-left: 40px;
  }
  .menu ul li a{
    text-decoration: none;
    padding: 0px 20px;
    font-size: 25px;
    color: black;
    cursor: pointer;
    transition: 0.4s;
  }
  .menu ul li a :hover{
    background-color: black;
    color: white;
  }
</style>

