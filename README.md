<?php include "config.php"; ?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sweet</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
   <header>
    
    <nav class="navbar">
            <a href="#"class="nav-logo">
        <h2 class="logo-text">🧇The Sweet Corner</h2>
    
    
           </a>
           <ul class="nav-menu">

        <li class="nav-item">
            <a href="index.php"class="nav-link">Home</a>

        </li>
        <li class="nav-item">
            <a href="aboutus.php"class="nav-link">About Us</a>

        </li>
        <li class="nav-item">
            <a href="menu.php"class="nav-link">Menu</a>

        </li>
        <li class="nav-item">
            <a href="Reviews.php"class="nav-link">Reviews</a>

        </li>
        <li class="nav-item">
            <a href="contactus.php"class="nav-link">contact us
</a>
<li class="nav-item">
            <a href="admin.php"class="nav-linkk">👤
</a>


  

         </ul>   
        
 

    </nav>
   </header> 
   <main>
    <section class="hero-section">
        <div class="section-content">
            <div class="hero-details">
                <h2 class="title">Welcome</h2>
                <h3 class="subtitle">make your day great with our special sweet</h3><br>
                <p class="descrption">


  Welcome to our shop! We are delighted to have you here <br>
   and invite you to explore our products.
  Our goal is to offer you quality, comfort,<br> and a pleasant experience every time you visit us.
</p>
<div class="buttons">
    <a href="menu.php" class="button">Order Now</a>
        <a href="contactus.php" class="contactus">Contact Us</a>
</div>          
</div>


        </div>

    </section>
   </main>
   

<footer class="footer">
  <div class="footer-box">
    <h3>The Sweet Corner</h3>
    <ul>
      <li>Home</li>
      <li>About Us</li>
      <li>Menu</li>
      <li>Reviews</li>
      <li>Contact Us</li>
    </ul>
  </div>

  <div class="footer-box">
    <h3>Contact</h3>
    <p>Email: thesweetcorner21@gmail.com</p>
    <p>Phone: 05 xx xx xx xx</p>
    <p>Address: Rue 21 xxx, Skikda</p>
  </div>

  <div class="footer-box">
    <h3>Suivez-nous</h3>
    <ul>
      <li>Facebook</li>
      <li>Instagram</li>
    </ul>
  </div>
  
  
</footer>
 <div class="footer-bottom">
    <p><b>© 2026 My Shop. The Sweet Corner.</b></p> </div>
    partie CSS


    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap');

.playfair-display {
  font-family: "Playfair Display", serif;
  font-optical-sizing: auto;
 
  font-style: normal;
}



* {
    padding: 0;
    margin: 0;
    font-family:  "Playfair Display", serif;
}
 /* PAGE 1 */

body{

    margin-top: 80px;
    background-color: rgb(116, 39, 39) ;
}
ul{
    list-style: none;
}
a{
    text-decoration: none;
}
button{
    cursor: pointer;
    border: none;
    background: none;
}
img{
    width: 100%;

}
.section-content{
    margin:  0 auto;
    padding: 0 20px;
  
}

    header {
        background-color:  rgb(116, 39, 39);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
 
z-index: 1000;
}


header .navbar{
    display: flex;
    padding: 20px;
    align-items: center;
    justify-content:space-between ;
}
.navbar .nav-logo .logo-text{
    color: black;
   
  font-size: 28px;  
  font-style: oblique; 
  


}
.navbar .nav-menu{;
   
    display:flex;
    gap: 10px;
}

.navbar .nav-menu .nav-link{
   padding: 5px 40px;
  color: rgb(12, 12, 12);
  background-color: hsl(340, 100%, 99%);
  border-radius: 20px;
  transition: 0.3s ease;

}
.navbar .nav-menu .nav-linkk{
   padding: 10px 10px;
  color: rgb(12, 12, 12);
  background-color: hsl(300, 4%, 5%);
  border-radius: 50px;
  transition: 0.3s ease;

}






.navbar .nav-menu .buy-btn:hover{
   color: rgb(6, 6, 6);
    background-color:rgb(176, 165, 166);
}
main{
        background-image: url(images/photo_2025-12-27_12-26-45.jpg);

 background-position: center;
 background-repeat: no-repeat;
 background-size: cover;
 height: 550px;
}
.hero-section .hero-details .title{
       color: black;
   
  font-size: 25px;   
  font-style: italic; 
  

}
.hero-section .hero-details .subtitle{
          color: rgb(60, 0, 0);
   
  font-size: 25px;   
  font-style: italic;

}
.hero-section .hero-details .descrption{
     color: black;
     
  font-style: oblique;
  font-size: 20px;
  line-height: 1.8;
 
  letter-spacing: 0.5px;


}
.hero-section .hero-details .button{
    
  margin-right: 30px;
  padding:2px 40px;
 border:  2px solid white;
   background:  rgb(116, 39, 39);
  color: black;
  text-decoration: none;
  border-radius: 15px;
  transition: 0.3s ease;
}
.hero-section .hero-details .button:hover{
      background-color:rgb(176, 165, 166);
}
.hero-section .hero-details .contactus{ 
    background: transparent;
  margin-right: 30px;
  padding:2px 40px;
  border-radius: 15px;
  border:  2px solid white;
  color:white;
  text-decoration: none;

}
.hero-section .hero-details .contactus:hover{
      background-color:rgb(176, 165, 166);
}
.footer {
  background-color:   rgb(116, 39, 39);
  color: #fff;
  display: flex;
  justify-content: space-around; /* يفرّقهم */
  align-items: flex-start;
  padding: 60px 80px;
  gap: 60px; /* مسافة بين البوكسات */
}

.footer-box {
  width: 25%;
}

.footer-box h3 {
  margin-bottom: 20px;
  color: black;
}

.footer-box ul {
  list-style: none;
  padding: 0;
}

.footer-box ul li {
  margin-bottom: 10px;
}

.footer-box p {
  margin-bottom: 10px;
}
.footer-bottom{
  text-align: center;
  margin-top: 10px;
  font-size: 20px;
  color:black;
}

 

    

</body>
</html>
