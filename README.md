<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facials</title>
</head>
<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .body{
            width: 100%;
            height: 100vh;
            position: relative;
            background-color: rgb(247, 242, 242);
            color: rgb(124, 228, 247);
    }
    
    .sec1{
        width: 1250px;
        color: rgb(78, 21, 211);
        text-align: left;
        padding: 0px 0 0 20px;
    }
    .background{
        width: 1350px;
        height: 100vh;
        background-image: url(../Stick.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    }
    nav{
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 8px;
        
    }
    
    .logo{
        width: 100px;
        position: fixed;
    }
    nav ul li{
        display: inline-block;
        
    }
    nav ul li a{
        text-decoration: none;
        color: rgb(245, 234, 234);
        font-weight: 200;
        margin-left: 150px;
        font-size: smaller;
    }
    .login{
        text-decoration: none;
        color: crimson;
        margin-right: 35px;
    }
    .btn{
        display: inline-block;
        text-decoration: none;
        padding: 14px 50px;
        color: rgb(205, 240, 240);
        background-image: linear-gradient(55deg, purple, rgb(219, 22, 186));
        font-size: 10px;
        border-radius: 30px;
        border-bottom-right-radius: 0;
    }
    .text{
        padding: 100px 60px;
    }
    .text h1{
        color: rgb(219, 22, 186);
        margin: 10px 0;
        font-size: 50px;
    }
    .text p{
        color: rgb(245, 236, 236);
        margin: 10px 0;
        width: 640px;
    }
    .btn1{
        width: 150px;
        height: 40px;
        margin-top: 20px;
        background-color: rgb(78, 21, 211);
        color: rgb(236, 225, 225);
        border-radius: 7px;
        text-decoration: none;
    }
    /* Section2 */
    .sec2{
        width: 80%;
        height: 65vh;
        padding: 0 50px 0 50px;
        overflow: scroll;
        margin-top: 50px;
        display: flex;
        color: black;
        gap: 80px;
        margin-left: 120px;
        
    }
    .btn2{
        width: 120px;
        height: 30px;
        background-color: brown;
        color: white;
        border: none;
        font-size: small;
        margin-bottom: 10px;
        
    }
    .text2{
        margin-top: 10px;
        color: brown;
        
    }
    .text2 h6{
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: smaller;
        
    }.text2 p{
        width: 350px;
        font-size: smaller;font-family: 'Times New Roman', Times, serif;
        color: rgb(2, 66, 82);
     
    }
    .img{
        width: 1340px;
        height:100vh;
        margin-top: 70px;
        overflow: hidden;
        backdrop-filter: -20px;
    }
    /* Section3 */
    .text3{
        text-align: center;
        margin-top: 50px;
        color: rgb(78, 21, 211);
    }
    .sec3{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        margin-top: 20px;
    }
    .sec3 img{
        width: 300px;
        height: 300px;
        border: 2px solid greenyellow;
        border-radius: 13px;
        box-shadow: 4px 7px 7px 0 rgb(12, 12, 12);
        cursor: pointer;
        margin: 10px;
        transition: 400ms;
    }
    .sec3 img hover{
        filter: grayscale(1);
        transform: scale(1.03);

    }
    .sec3 a{
        margin: 0 70px 0 120px;
        justify-items: center;
        padding-right: 40px;
    }
    .designer{
        margin: 0 70px 0 120px;
        justify-items: center;
        padding-right: 85px;
    }
    .price{
        display: flex;
        justify-content: space-evenly;
        margin: 5px 1px 20px 0;
    }
     /* Section4 */
     .sec4{
        width: 1660;
        height: 80vh;
        padding: 0 200px 0 70px;
        background-color: black;
        margin-top: 50px;
        display: flex;
        color: rgb(245, 229, 7);
        gap: -20px;
    
    }
    .sec4 img{
        width: 500px;
        margin-left: 100px;
        border-radius: 40px;
        border: 2px solid brown;
    }
    .text4{
        place-content: center;

    }
     /* Section5 */
     .tools{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        border: 2px solid rgb(235, 164, 12);
        border-radius: 13px;
        box-shadow: 4px 7px 7px 0 rgb(12, 12, 12);
        cursor: pointer;
       
     }
     .sec5i{
        margin: 20px;
     }
     .sec5{
        width: 100px;
        height: 100vh;
       margin: 50px 100px;
     }

     /* Section6  */
     .allsec6{
            width: 100%;
            height: 35vh;
            padding: 20px;
            background-color: rgb(243, 233, 233);
            color: rgb(50, 6, 92);
        }
        .enquiries1{
            display: flex;
            gap: 13rem;
            place-content: center;
            cursor: pointer;            
            font-size: 15px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            
        }
        .icon{
            margin-top: 15px;            
            
            border-radius: 5px;
        }
        .h3{
            color: rgb(15, 15, 14);
            cursor: pointer;            
            font-size: 25px;
            font-weight: 600;
            border-bottom: 0.1px solid rgb(48, 2, 2);
            transition: .4s;
            margin-top: 30px;

        }


</style>
<body>
    <!-- section1 -->
     <div class="sec1">
        <div class="background">
        <nav>
            <img src="Chillateq1.png" alt="" class="logo">
            <ul>
                <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Why Choose Us</a></li>
                    <li><a href="#">Contact</a></li>
            </ul>
            <div>
                <a href="#" class="login">Log In</a>
                <a href="#" class="btn">Download</a>
            </div>
        </nav>
    
        <div class="text">
        <h1>CHILLA MAKEUP STUDIO</h1>
        <h3>Your Glamour Stop Shop</h3>
        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo qui veritatis asperiores magnam itaque repudiandae, quidem illum rem corrupti, exercitationem beatae soluta accusantium eius magni non. Temporibus reprehenderit eligendi dignissimos, quia, a, eaque earum ab autem vitae nulla corporis. Sit dicta beatae non omnis alias recusandae suscipit culpa, quos rem.</P>
        <button class="btn1">BOOK A SESSION ---></button>
    </div>
</div>
</div>
 <!-- section2 -->
 <div class="sec2">
    <div class="text">
    <button class="btn2">ABOUT CHILLATEQ</button>
   
        <h3>SLEEK TREATMENT <br>HEALTHY OUTCOME</br></h3>
        <div class="text2"><h6>QUALITY SERVICE</h6>
        <p>The wise man therefore always holds indies matters this <br>principle information</p></div>
        <div class="text2"><h6>ALWAYS A SATISFACTORY EXPERIENCE</h6>
        <p>The wise man therefore always holds indies matters this <br>principle information</p></div>

        <button class="btn1">CLICK HERE ---></button>
    </div>
    <div class="img"><img src="/Github/Lipstick3.jpg" alt=""></div>
 </div>


     
    <!-- section3 -->
     <div class="text3">
        <h2>FOUNDATION TYPES</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reiciendis consectetur possimus blanditiis impedit ipsum repudiandae eos vel quos eaque sapiente.</p>
     </div>
    
     <div class="sec3">
            <img src="/Github/Facial/Dior Foundation.jpg" alt="">
            <img src="/Github/Facial/Chanel Foundation.jpg" alt="">
            <img src="/Github/Facial/L'Oreal Foundation.jpg" alt="">
            <img src="/Github/Facial/Water Blend Foundation.jpg" alt="">
        </div>
        <div>
            <a href="#" class="designer">DIOR</a>
            <a href="#" class="designer">CHANEL</a>
            <a href="#" class="designer">L'OREAL</a>
            <a href="#" class="designer">FOREVER</a>
        </div>
        <div class="price">
            <h4>$72</h4>
            <h4>$35</h4>
            <h4>$66</h4>
            <h4>$29</h4>
            
        </div>

        <!-- section4 -->
        <div class="sec4">
            <div class="img">
                <img src="/Github/Facial/black-background.avif" alt="img">
        </div>
            <div class="text4">
            <button class="btn2">ABOUT CHILLATEQ</button>
           
                <h3>SLEEK TREATMENT <br>HEALTHY OUTCOME</br></h3>
                <div class="text2"><h6>QUALITY SERVICE</h6>
                <p>The wise man therefore always holds indies matters this <br>principle information</p></div>
                <div class="text2"><h6>ALWAYS A SATISFACTORY EXPERIENCE</h6>
                <p>The wise man therefore always holds indies matters this <br>principle information</p></div>
        
                <button class="btn1">CLICK HERE ---></button>
            </div>
        </div>

           

        <!-- section5 -->
         <div class="tools">
            <img src="/Github/Facial/Foundation.jpg" alt="">
            <img src="/Github/Facial/Primer.jpg" alt="">
            <img src="/Github/Facial/Powder2.jpg" alt="">
            <img src="/Github/Facial/Lipstick5.jpg" alt="">
            <img src="/Github/Facial/Foam2.jpg" alt="">
         </div>
        <div class="sec5i">
            <a href="#" class="sec5">Foundation</a>
            <a href="#" class="sec5">Primer</a>
            <a href="#" class="sec5">Powder</a>
            <a href="#" class="sec5">Lipstick</a>
            <a href="#" class="sec5">Blender</a>
        </div>

        <!-- Section6 -->
    <div class="allsec6">
        <div class="enquiries1">
        
            
        <div><h3 class="h3">Company</h3>
        <li>About Us</li>
        <li>Our Services</li>
        <li>Privacy Policy</li>
        <li>Affiliate Program</li>
        
    </div>
    <div>
        <h3 class="h3">Get Help</h3>
        <li>FAQ</li>
        <li>Shopping</li>
        <li>Returns</li>
        <li>Order Status</li>
        <li>Payment option</li>
    </div>
    <div>
        <h3 class="h3">Online Shop</h3>
        <li>Watches</li>
        <li>Bags</li>
        <li>Shoes</li>
        <li>Denim</li>
        <li>Dresses</li>
    </div>
    <div>
        <h3 class="h3">Follow Us</h3>
        <li>info@lamoria.com</li>
        <li>+2348098765432</li>
        <li>@l'amoria</li>
        <div class="icon">
        <img src="/SOCIAL ICONS/bxl-facebook.svg" alt="">
        <img src="/SOCIAL ICONS/bxl-twitter.svg" alt="">
        <img src="/SOCIAL ICONS/bxl-linkedin.svg" alt="">
        <img src="/SOCIAL ICONS/bxl-instagram.svg" alt="">
    </div>
    </div>
</div>
     
    
</body>
</html>
