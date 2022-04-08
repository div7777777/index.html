# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>AGENCE DE VOYAGE</title>
</head>
<body>
  <style>
    *{
    padding: 0;
    margin: 0;
}
/* slider 1 */

div.slides1 {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    width: calc(500px*3);
    height: 1000;
    animation: glisse 14s infinite ease;
    max-width: 1000px;
    position: relative;
    margin: auto;

}

.img {
    width: 200px;
    height: 250px;
}
@keyframes glisse {
    0% {
        transform: translateX(0);
    }
    25% {
        transform: translateX(-250px);
    }
    50% {
        transform: translateX(-500px);
    }
    75% {
        transform: translateX(-750px);
    }
    100% {
        transform: translateX(-1000);
    }
}
/* slider 2 */


div.slides2 {
    display: flex;
    align-items: center;
    flex-direction: row;
    width: calc(500px*5);
    height: 1000;
    animation: glisse 12s infinite ease;
    max-width: 1000px;
    position: relative;
    margin: auto;

}

.img {
    width: 65px;
    height: 70px;
}
@keyframes glisse {
    0% {
        transform: translateX(0);
    }
    25% {
        transform: translateX(-250px);
    }
    50% {
        transform: translateX(-500px);
    }
    75% {
        transform: translateX(-250px);
    }
    100% {
        transform: translateX(0);
    }
}
/* contacte réseaux sociaux */


 /* menu humberger */
.accueil{
    color: red;
    font-family: 'Cinzel Decorative', cursive;
    max-width: 1000px;
    position: relative;
    margin: auto;
}
.burger a {
     display: block;
     color: white;
     font-size: 25px;
     padding-top: 18px; 
     text-decoration: none;
     max-width: 1000px;
     position: relative;
     margin: auto;
}
.flex{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;


}
.flex:hover{
    background-color: #800000;
}
.sidenav{

    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #111;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}
 .sidenav a:hover {
     background-color: #800080;
     width: 100%;
     padding: 4px;
 }
 .sidenav .closebtn{
     position: absolute;
     top: 0;
     right: 25px;
     font-size: 36px;
     margin-left: 50px;
 }

 @media screen and (max-heigth: 450px){
     .sidenav{padding-top: 15px;;}
     .sidenav a {font-size: 18px;}
 }
/* contacte */
.icones{
    display: flex;
    justify-content: center;
    align-items: center;
    background: black;
    padding: 5px;
    max-width: 1000px;
    position: relative;
    margin: auto;
}
.icone{
    display: inline-block;
}

/* slider responsive */

.style-menu {
    display: flex;
    justify-content: center;
    background: black;
}

.style-menu [type="text"] {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    background: greenyellow;
    color : black;
    padding: 15px;
    margin: 15px;
    height: 20px;
    width: 500px;
}
.soumetre {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: -110px;
}

/* slider */
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: red;
  font-size: 25px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}
.text:hover{
    background: darkred;
    padding-top: 1px;
    

}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color:#bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
/* menu */
.menu{
    display: flex;
    justify-content: center;
    background-color: black;
    max-width: 1000px;
    position: relative;
    margin: auto;

}
.item{
    display: inline-block;
}
  </style>
<div class="slider1">
    <div class="slides1">

        <div class="slide"><img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/3.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/3.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/2.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider1/1.jpg" alt=""></div>
    </div>
</div>
<div class="slider2">
    <div class="slides2">
        <div class="slide"><img src="images/slider2/terre.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/g.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/n.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/c.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/w.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/o.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/d.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/t.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/v.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/l.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/terre.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/g.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/n.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/c.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/w.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/o.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/d.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/t.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/r.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/a.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/v.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/e.jpg" alt=""></div>
        <div class="slide"> <img src="images/slider2/l.jpg" alt=""></div>
    </div>
</div>
<!-- menu -->
<div id="mySidenav" class="sidenav">
    <a href="javascript:void(0)" class="closebtn"  onclick="closeNav()">&times;</a>
    <div class="burger">
            <div class="flex">
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/home.png"/>  Home </a>
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/service.png"/>  Services</a>
                <a href="#"> <img src="https://img.icons8.com/external-others-iconmarket/23/ffffff/external-client-essential-others-iconmarket-3.png"/>  Clients</a>
                <a href="#"><img src="https://img.icons8.com/ios-filled/23/ffffff/phone-not-being-used.png"/>  Contact</a>
                <a href="#"> <img src="https://img.icons8.com/ios-filled/23/ffffff/order-delivered.png"/>  Adresse</a>
                <a href="#"><img src="https://img.icons8.com/wired/23/ffffff/book-and-pencil.png"/>  À propos</a>


            </div>

    </div>


</div>
<!-- accueil -->
<div class="accueil">
        <span style="font-size: 30px; cursor: pointer"; onclick = "openNav()"> &#9776; <img src="https://img.icons8.com/metro/50/000000/airplane-mode-on.png"/>AGENCE WORD TRAVEL
            <style>
                @import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative&family=El+Messiri&family=Palette+Mosaic&family=Rajdhani:wght@400;500&family=Schoolbell&display=swap');
                </style>
            
        </span>

</div>

<!-- services -->
    <!-- menu -->
    <nav class="menu">
          <ul class="items">
            <li class="item"><a href=""></a><img src="menu/1.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/2.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/3.jpg" alt=""></li>
            <li class="item"><a href=""></a><img src="menu/4.jpg" alt=""></li>
          </ul>
     </nav>

<!-- slider -->

<div class="slideshow-container">

    <div class="mySlides fade">
      <div class="numbertext">1 / 8</div>
      <img src="images/1.jpg" style="width: 100%">
      <div class="text">Espagne</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext">2 / 8</div>
      <img src="images/2.jpg"style="width: 100%">
      <div class="text">France</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext">3 / 8</div>
      <img src="images/3.jpg"style="width: 100%">
      <div class="text">Tunisie</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">4 / 8</div>
      <img src="images/4.jpg"style="width: 100%">
      <div class="text">Canada</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">5 / 8</div>
      <img src="images/5.jpg"style="width: 100%">
      <div class="text">Turquie</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">6 / 8</div>
      <img src="images/6.jpg"style="width: 100%">
      <div class="text">Abu Dhabi</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">7 / 8</div>
      <img src="images/7.jpg"style="width: 100%">
      <div class="text">Qatar</div>
    </div>
    <div class="mySlides fade">
      <div class="numbertext">8 / 8</div>
      <img src="images/8.jpg"style="width: 100%">
      <div class="text">Arabie Saoudit</div>
    </div>

    
    <a class="prev" onclick="plusSlides(-1)">❮</a>
    <a class="next" onclick="plusSlides(1)">❯</a>
    
    </div>
    <br>
    
    <div style="text-align:center">
      <span class="dot" onclick="currentSlide(1)"></span> 
      <span class="dot" onclick="currentSlide(2)"></span> 
      <span class="dot" onclick="currentSlide(3)"></span> 
      <span class="dot" onclick="currentSlide(4)"></span> 
      <span class="dot" onclick="currentSlide(5)"></span> 
      <span class="dot" onclick="currentSlide(6)"></span> 
      <span class="dot" onclick="currentSlide(7)"></span> 
      <span class="dot" onclick="currentSlide(8)"></span> 
    </div>
    <!-- menu contacte -->
<div class="icones">
  <ul>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-glyphs/90/E74C3C/facebook.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/small/90/E74C3C/instagram.png"/> </li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/dotty/90/E74C3C/email.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/fluency-systems-filled/90/E74C3C/call-squared.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-filled/90/E74C3C/linkedin.png"/></li>
    <li class="icone"><a href=""></a><img src="https://img.icons8.com/ios-filled/90/E74C3C/twitter-circled--v1.png"/></li>
  </ul>

</div>   
<script>
  // menu burgeur
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}



// slider

let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script> 

<!-- javascript -->
<script src="code.js"></script>
    
</body>
</html>
