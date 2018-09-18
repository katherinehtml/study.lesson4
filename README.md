# study.lesson4.html
<!DOCTYPE HTML>
<html>
<head>
  <meta  charset="utf-8">
  <title>Products</title>
<style type="text/css">
.header{
    padding: 10px 0;
    position: fixed;
    left: 0;
    top: 0;
    right: 0;
    z-index: 997;
    background: rgba(138, 144, 255, 0.9);
}
.menu-nav_item{
    list-style: none;
}
.menu-nav_link{
    text-decoration: none;
    display: inline-block;
    color: #fff;
    font-weight: 400;
    font-size: 12px;
    text-transform: uppercase;
    outline: none;
}
.section_banner{
    background: url(img/banner-bg.jpg);
    background-size: cover;
}
.container{
    max-width: 1140px;
    padding: 0 15px;
    margin: 0 auto;
}
.banner{
    margin-top: 120px;
    padding: 120px 0;
}
.banner-text_header{
    color: white;
    font-size: 48px;
    font-weight: 600;
    text-align: center; 
}
.banner-text_body{
    text-align: center;
    padding: 10px 0;
}
.banner-text_body a{
text-decoration: none;
color: white;
font-weight: 300;
font-size: 14px;
}
.banner-text_body span{
color: white;
font-weight: 300;
font-size: 14px;
padding: 0 5 px;
}
*{
    padding: 0;
    margin: 0;
}
.section_main{
padding: 120px 0;
}
.section_header{
    text-align: center;
}
h1{
    font-size: 36px;
    color: #222222;
}
.product-card-wrap{ 
    padding: 15px;
    width: 25%;
}
.product-card{
    min-width: 255px;
    text-align: center;
    border-radius: 10px;
    background-color: white;
    box-shadow: 0px 10px 30px 0px rgba(212,150,255,0.2)
}
.product-card_image-wrap{
padding: 40px;
border-bottom: 1px solid #eee;
}
.product-card_details{
    padding: 20px;
    background-color: #f9f9ff;
}
h4{
    font-size: 18px;
}
.product-card_button{
    display: inline-block;
    text-decoration: none;
    margin-top: 10px;
    background: #fff;
    color: #222 !important;
    font-weight: 600;
    line-height: 42px;
    padding-left: 30px;
    padding-right: 30px;
    border: 1px solid transparent;
    cursor: pointer;
    position: relative;
    text-transform: uppercase;
}
.footer{
    background: url(img/footer-bg.jpg);
    background-size: cover;
    padding-top: 100px;
    padding-bottom: 120px;
}
.footer-block_last{
    padding-top: 120px;
    color: white;
}
.copyright{
    padding: 0 15px;
}
.banner-container{
    display: flex;
    justify-content: center;
}
.product-card-container{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.product-card-wrap{
    padding: 15px;
    width: 25%;
}
</style>
</head>
<body>
<header class="header">
    <div class="container">
        <div class="menu">
            <div class="menu-logo"><a href="#" class="menu-logo_link"><img src="img/logo.png"></a></div>
            <div class="menu-nav-container"><div class="container">
            <ul class="menu-nav">
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">home</a></li>
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">about</a></li>
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">services</a></li>
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">products</a></li>
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">blog</a></li>
                <li class="menu-nav_item"><a href="#" class="menu-nav_link">contact</a></li>
            </ul> 
            </div></div>
        </div>
    </div>
</header>  
<main class="main">
    <section class="section section_banner">
        <div class="container">
            <div class="banner-container">
                <div class="banner">
                    <div class="banner-text">
                        <h1 class="banner-text_header">Products</h1>
                        <div class="banner-text_body">
                            <a href="#">Home</a>
                            <span>→</span>
                            <a href="#">Products</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
<section class="section section_main">
    <div class="container">
        <div class="section_header"><h1>Featured Robotics Products to Show</h1>
        <p>Who are in extremely love width eco friendly system.</p></div>
        <div class="product-card-container">
        <div class="product-card-wrap">
         <div class="product-card">
             <div class="product-card_image-wrap"><img class="product-card_image" src="img/p1.png"></div>
             <div class="product-card_details">
                 <h4 class="product-card_header">The Upper Eye</h4>
                 <p class="product-card_text">Who are in extremely love with eco friendly system</p>
                 <a class="product-card_button" href="#">View Details</a>
             </div>
         </div>  
         </div>
        </div>
        <div class="product-card-container">
            <div class="product-card-wrap">
             <div class="product-card">
                 <div class="product-card_image-wrap"><img class="product-card_image" src="img/p1.png"></div>
                 <div class="product-card_details">
                     <h4 class="product-card_header">The Upper Eye</h4>
                     <p class="product-card_text">Who are in extremely love with eco friendly system</p>
                     <a class="product-card_button" href="#">View Details</a>
                 </div>
             </div>  
             </div>
            </div>
            <div class="product-card-container">
                <div class="product-card-wrap">
                 <div class="product-card">
                     <div class="product-card_image-wrap"><img class="product-card_image" src="img/p1.png"></div>
                     <div class="product-card_details">
                         <h4 class="product-card_header">The Upper Eye</h4>
                         <p class="product-card_text">Who are in extremely love with eco friendly system</p>
                         <a class="product-card_button" href="#">View Details</a>
                     </div>
                 </div>  
                 </div>
                </div>
                <div class="product-card-container">
                    <div class="product-card-wrap">
                     <div class="product-card">
                         <div class="product-card_image-wrap"><img class="product-card_image" src="img/p1.png"></div>
                         <div class="product-card_details">
                             <h4 class="product-card_header">The Upper Eye</h4>
                             <p class="product-card_text">Who are in extremely love with eco friendly system</p>
                             <a class="product-card_button" href="#">View Details</a>
                         </div>
                     </div>  
                     </div>
                    </div>
    </div>
</section>
</main>
<footer class="footer">
    <div class="container">
        <div class="footer-block footer-block_last">
            <div class="copyright">Copyright 2018 ALL right reserved By Katherine Akhadova</div>
        </div>
    </div>
</footer>
</body>
</html>
