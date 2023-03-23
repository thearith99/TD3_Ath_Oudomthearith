<template>
  <div class="home">
    <div class="top">
      <div class="left">
        <div class="left-top">
          <p>Welcome to CamClothe!</p>
          <span>For The Old Customer</span>
        </div>
        <div class="left-buttom">
          <div class="left-buttom-1">
            <p>20%    To    30%</p>
            <button type="submit">MAN</button>
            <button type="submit">WOMAN</button>
          </div>
          <div class="left-buttom-2">
            <p>DEPARTMENTS</p>
            <span>Skiing Bibs</span><br>
            <span>Snow Pants &bibs</span><br>
            <span>Snow Suits</span><br>
            <span>Outerwear Jackets & Coats</span><br>
            <span> Activewear</span>
          </div>
        </div>
      </div>
      <div class="right">
        <img style="width: 80%; height: 100%; margin-left: 60px;" src="./images/p1.jfif" alt="">
      </div>
    </div>
    <div class="middle">
      <p>Good Price & Good Products & Quality & Responsibilities</p>
    </div>
    <div class="buttom">
      <img style="width: 100%; height: 80%; margin-top: 20px;" src="./images/photo_2023-03-22_22-43-24.jpg" alt="">
    </div>
  </div>
  <div class="footer">
    <div class="footer-left">
      <h1>Site Name</h1>
      <button type="submit">Classic</button>
      <button type="submit">Fashion</button>
      <button type="submit">Normal</button>
    </div>
    <div class="footer-middle">
      <img style="width: 70px; height: 60px; margin: 5px 10px;" src="./images/ABA.jpg" alt="">
      <img style="width: 70px; height: 60px; margin: 5px 10px;" src="./images/AC.jpg" alt="">
      <img style="width: 70px; height: 60px; margin: 5px 10px;" src="./images/wing.jpg" alt="">
    </div>
    <div class="footer-right">
      <h1>Stay In Touch! Join our Newsletter</h1>
      <input type="text" placeholder="Enter Email   Subscribe">
    </div>
  </div>
</template>

<style>
/* @media (min-width: 1024px) {
  .home {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
} */
@import url('https://fonts.googleapis.com/css2?family=Monofett&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Monofett&family=Monoton&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Monofett&family=Monoton&family=Montserrat+Alternates:wght@100;300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Monofett&family=Monoton&family=Montserrat+Alternates:wght@100;300;400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Monofett&family=Monoton&family=Montserrat+Alternates:wght@100;300;400&family=Quando&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300&family=Monofett&family=Monoton&family=Montserrat+Alternates:wght@100;300;400&family=Quando&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300&family=Monofett&family=Monoton&family=Montserrat+Alternates:wght@100;300;400&family=Norican&family=Quando&display=swap');
*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}
.home{
  width: 80%;
  height: 600px;
  /* background-color: blueviolet; */
  margin: 10px auto;
}
.top{
  width: 100%;
  height: 45%;
  /* background-color: brown; */
  display: flex;
}
.left{
  width: 50%;
  height: 100%;
  background-color: rgb(166, 174, 175);
  display: block;
  border-radius: 5px;
}
.left-top{
  width: 100%;
  height: 40%;
  /* background-color: grey; */
}
.left-top p{
  font-family: 'Monofett', cursive;
  font-size: 35px;
  text-align: center;
  padding-top: 5px;
}
.left-top span{
  font-size: 35px;
  font-family: 'Monofett', cursive;
  font-family: 'Monoton', cursive;
  margin-left: 20px;
}
.left-buttom{
  width: 100%;
  height: 60%;
  /* background-color: rgb(30, 29, 29); */
  display: flex;
}
.left-buttom-1{
  width: 50%;
  height: 100%;
  background-color: rgb(166, 174, 175);
}
.left-buttom-1 p{
  font-family: 'Montserrat Alternates', sans-serif;
  font-size: 25px;
  text-align: center;
}
.left-buttom-1 button{
  background-color: rgb(215, 215, 21);
  width: 100px;
  height: 40px;
  font-family: 'Monofett', cursive;
  font-size: 30px;
  border-radius: 5px;
  margin: 50px 0px;
  margin-left: 35px;
  transition: 0.4s;
  cursor: pointer;
}
.left-buttom-1 :hover {
  background-color: white;
}
.left-buttom-2{
  width: 50%;
  height: 100%;
  /* background-color: rgb(82, 87, 87); */
}
.left-buttom-2 p{
  font-size: 25px;
}
.left-buttom-2 span{
  padding-left: 20px;
}
.right{
  width: 50%;
  height: 100%;
  /* background-color: blueviolet; */
}
.middle{
  width: 100%;
  height: 10%;
  background-color: rgb(215, 215, 21);
  border-radius: 5px;
  margin-top: 20px;
}
.middle p{
  font-size: 30px;
  text-align: center;
  font-family: 'Montserrat Alternates', sans-serif;
  padding-top: 10px;
}
.buttom{
  width: 100%;
  height: 45%;
  /* background-color: brown; */
}
.footer{
  width: 100%;
  height: 70px;
  background-color: rgb(215, 215, 21);
  display: flex;
  border-radius:5px ;
}
.footer-left{
  width: 45%;
  height: 100%;
  /* background-color: gray; */
  display: flex;
}
.footer-left h1{
  font-family: 'Quando', serif;
  font-size: 25px;
  padding: 20px 30px;
}
.footer-left button{
  width: 80px; 
  height: 40px;
  border-radius: 5px;
  background-color: black;
  color: white;
  font-size: 18px;
  margin: 15px 5px;
  margin-left: 30px;
  cursor: pointer;
}
.footer-middle{
  width: 25%;
  height: 100%;
  /* background-color: green; */
}
.footer-right{
  width: 35%;
  height: 100%;
  /* background-color: blueviolet; */
}
.footer-right h1{
  font-family: 'Norican', cursive;
  font-size: 20px;
  padding: 5px 10px;
}
.footer-right input{
  width: 160px;
  height: 30px;
  border-radius: 5px;
  padding: 5px 9px;
  margin-left: 200px;
}
</style>
