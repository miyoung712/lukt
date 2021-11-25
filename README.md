<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lukt</title>
    
    <link rel="stylesheet" href="css/common.css">
    <link rel="stylesheet" href="css/index.css">

    <style>



    </style>

    <script src="https://code.jquery.com/jquery-2.2.3.min.js"></script>

    <script>
       function openNav (){
           document.getElementById("myNav").style.width="100%";
       }
        function closeNav() {
            document.getElementById("myNav").style.width="0%";
       }

    </script>


</head>

<header>


    <div class="small">
        <img src="img/menubar.png" id="b" onclick="openNav()">
        <img src="img/logo.png" alt="" class="logo">
            <div id="a">
            <a href="#">HOME</a>
            <a href="#">PRODUCTS</a>
            <a href="#">ABOUT US</a>
            <a href="#">CONTACT</a>
        </div>
    </div>


    <div id="myNav" class="overlay">
      <a href="javascript:void(0)" class="closebtn"  onclick="closeNav()">&times;</a>
      <div class="overlay-content">
        <a href="#">HOME</a>
        <a href="#">PRODUCTS</a>
        <a href="#">ABOUT US</a>
        <a href="#">CONTACT</a>
      </div>
   </div>


</header>

<body>
    <div id="slider">
        <div class="slide_wrap">
            <div class="main_slide">
                <h1>Peanut Butter<br>Raspberry Mild</h1>
                <h2>Yogurt ball, a gourmet combination that shows PB&J<br>
                    with American flavor,<br>
                    based on Look2's interpretation</h2>
    
                <button class="main_btn_s">VIEW PRODUCT</button>
    
                <div class="main_slide_box">
                    <a href="#"><img src="img/raspberry_r.png" alt=""></a>
                    <img src="img/flower.png" alt="">
                    <img src="img/main/main_raspberry.png" alt="">
                    <img src="img/raspberry_l.png" alt="">
                </div>
            </div>
        </div>
    </div>


    <section>
    <div class="two_box">
    <div class="two_yogurtbox">
        <div class="two_y_box">
            <h1>Lukt<br>Yogurt<br>Bowl</h1>
            <p>I recommend this to those who want to<br>start a look that doesn't fail</p>
            <button class="two_y_button">VIEW PRODUCT</button>
        </div>

       <div class="two_y_box">
           <h2>Honey<br>& Soboro Mild</h2>
           <h3>￦5,900<span>won</span></h3>    
           <img src="img/two_yogurt.png" alt="">

           <h2>Earl Grey<br>& Honeytique</h2>
           <h3>￦5,900<span>won</span></h3>    
           <img src="img/two_yogurt_2.png" alt="">
       </div>
     </div>
    </div>

    <div class="slide_two">
        <div class="slide_two_box">


        </div>



    </div>

 










    </section>
</body>

</html>
