<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="s" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="fu.css">
</head>

<body>

  <div class="NavBar">

    <form action="" method="get">
      <a data-color="primary" class="box1" href="gg.html">Home</a>
      <a class="box1" href="http://google.com">Content</a>
      <a class="box1" href="##">Medicine</a>
      
      <select id="cars" <option value="volvo">T-Shirts</option>
        <option value="saab" style="background-color: beige; color: black; font-style: italic;">T-shirts Brands</option>
        <option value="opel" style="background-color: beige; color: black; font-style: italic;">Opel</option>
        <option value="audi" style="background-color: beige; color: black; font-style: italic ; cursor: pointer;">Audi
        </option>
      </select>
      <input type="text" name="q" placeholder="Search" />


    </form>
    <marquee scrollamount="10" direction="left">WELCOME TO OUR MOST PREMIUM HOTEL WEBSERIES </marquee>



    <h1>HOTEL CANVAS</h1>
    <h4>THE RIGHT PATHWAY OF LIVING
      <br>know more about the hotel and enjoy our service</br>
    </h4>

    <div class="boxes">
      <div class="boxes1">CONTACT </div>
      <div class="boxes1">BOOK</div>
      <div class="boxes1">MORE TO KNOW</div>
    </div>



</body>

<footer>Hotel Canvas
  <pre style="color: black; font-weight: 600; ">Lorem ipsum, dolor  sit amet consectetur adipisicing elit. Consequatur voluptas dicta hic. Voluptate neque, aliquam vel cum laborum reiciendis doloribus iusto quidem quam.
    here you can more focus on hotel rooms and various food you can enjoy
        
  </pre>
  <div class="bed">
    
    <img src="bed1.jpg" width="400px" alt="">
    <img src="bed3.jpeg" width="400px" alt="">
    <img src="bed2.avif" width="380px" alt="">
  </div>
</footer>


</html>
!--CSS...........
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Playwrite+AU+VIC+Guides&family=Rubik+Vinyl&family=Teko:wght@300..700&display=swap');

:root {
    --color: rgb(4, 2, 72);

}

body {
    background-image: url(hotel.webp);
    background-repeat: repeat-x;
    object-fit: fill;
}


* {

    margin: 0;
    padding: 0;


}

form {
    position: sticky;
    top: 0;
    /* Ensures stickiness */
    background-color: var(--color);
    filter: brightness(200%);
    padding: 10px;
    z-index: 1000;
    /* Keeps the navbar above other elements */
    /* overflow-x: hidden; */
}


.box1 {
    display: inline-block;

    padding: 10px;
    border: 2px solid rgb(10, 10, 213);
    margin: px;
    width: 15vw;
    align-self: center;
    background-color: blue;
    color: rgb(251, 255, 255);
    text-decoration-line: none;
    text-align: center;

}

#cars {
    display: inline-block;

    padding: 10px;
    border: 2px solid rgb(10, 10, 213);
    margin: 5px;
    width: 15vw;
    align-self: center;
    background-color: blue;
    color: antiquewhite;
    text-decoration-line: none;
    text-align: center;

}

@media only screen and (max-width:230px) {
    .NavBar {
        background-color: blueviolet;
    }
}

.box1:nth-child(4) {
    background-color: rgb(16, 22, 177);
}




[data-color="primary"] {
    background-color: aqua;
}

marquee {
    font-size: 30px;
    font-family: "Rubik Vinyl", serif;
    font-weight: 900;
    font-style: normal;
    text-shadow: 20px 80px 10px rgba(196, 12, 12, 0.5);
    text-decoration: underline;
    color: rgb(5, 2, 54);
}
h1{
    display: flex;
    justify-content:center ;
    position: relative;
    top: 2.5em;
    font-size: 40px;
    color: rgb(27, 1, 26);
}
h4{
    display: flex;
    justify-content:center ;
    position: relative;
    top: 5em;
    height: 50px;
    width: 600px;
    font-size: 20px;
    color: rgb(13, 0, 13);
    padding: 20px;
    border: 5px solid rgb(49, 1, 1);
    outline: 3px solid #ee3f0a; /* Red outline */
    outline-offset: 10px;
    margin: auto;
    box-shadow: 4px -13px 8px rgba(196, 12, 12, 0.5); 
} 

 
  .boxes1{
    position: relative;
    top: 10em;
    left: 19em;
    
    
    display: inline-block;
   padding: 10px;
   border: 2px solid rgb(244, 240, 240);
   margin: 20px;
   width: 14vw;
   background-color: rgb(199, 194, 215);
   text-indent: 50px;;
   border-radius: 10px;
   color: rgb(217, 216, 225);
   font-family: 'Arial', sans-serif;
   background: linear-gradient(135deg, #185e94, #030125);
   cursor: pointer;
  

  }
  .boxes1:hover {
    background: linear-gradient(45deg, #c99ea8, #3a020f);
    transform: translateY(10px);
}
footer{
    position: relative;
    top: 20em;
    padding: 30px;
    border: 2px solid rgb(241, 237, 237);
    background-color: rgb(197, 204, 210);
 
}
img:hover{
    transform: scale(1.3);
    box-shadow:3px -12px 8px rgba(196, 12, 12, 0.5); 
    border-radius: 30px;
}
*::selection{
    background-color: #363cef;
    font-style: italic;
}
input::placeholder{
    font-size: 10px;
    color: #030125;
    font-size: 10px; 
    margin: 30px;
}
