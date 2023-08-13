HTML code:

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <link rel="stylesheet" href="first.css">
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <title>Document</title>
    <script src="https://kit.fontawesome.com/c7dc5382f5.js" crossorigin="anonymous"></script>
    </head>

    <body>
    
    <div class="one">
       
      <nav>
            <div class="two">
                <a href="##">Create.co</a>
            </div>
            <ul class="three">
                <li><a href="#">Home</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="#">Team</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
            <ul class="four">
                <li><a href="#" id="three a">Login</a></li>
                <li><a href="#" class="getstart">Getting Started</a></li>
            </ul>
        </nav>
    
    
        <div class="five">   
            <div class="text">
                <p><strong class="blue"> Grow Your Business<br>
                    With</strong> <strong class="red"> Social Media <br>marketing</strong></p>
                <p class="desc">Lorem ipsum dolor sit amet,consectetur <br> adipiscing elit,sed do eiusmod tempor<br>incididunt ut labore et dolore magna alliqua.ut</p>
                <input type="text" name="" id="" placeholder="Email Address" class="Email"><button>Learn more</button><br><br><br>
                <i class="fa-brands fa-square-instagram" style="color: #5654b3;"></i>
                <i class="fa-brands fa-square-facebook" style="color: #5654b3;"></i>
                <i class="fa-brands fa-square-twitter" style="color: #5654b3"></i>
                <i class="fa-brands fa-square-youtube" style="color: #5654b3"></i>
                <i class="fa-brands fa-square-whatsapp" style="color: #5654b3"></i>
            </div>
            <img src="image.png" alt="">
        </div>

    </div>

    </body>
    </html>




#CSS code:


    body{
    background-color: #e3f0ff;
    overflow:hidden;
    }

    .one{
     margin-left: 40px;
     margin-bottom: 0px;
    }

    nav {
    color: #fff;
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 50px;

    }
  
    .two a {
    font-weight: bolder;
    font-size: 35px;
    color: #2d2c62;
    text-decoration:none;
    align-content: left;
    }
  
    .three {
    list-style:none;
    display:flex;
    justify-content:space-between;
    color: #2d2c62;
    font-size: 18px;
    }
  
    .three li {
    margin-right: 25px;
    margin-left: 50px;
    font-size: 13px;
    }
  
    .three li a {
    color: #2d2c62;
    text-decoration: none;
    }
  
    .four {
    list-style: none;
    display: flex;
    font-size: 13px;
    }
  
    .four li {
    margin-right: 40px;
    }
  
    .four li a {
    color: 2d2c62;
    text-decoration: none;
    }

    .getstart{
    background:#5654b3 ;
    padding: 15px 25px;
    color: white;
    border-radius: 10px;
   
    }

    img{
    flex: 1;
    width:65%;
    float: right;
    padding-top: 40px;
    justify-content: left;
    position:relative;
    }

    .five{
    display: flex;
    justify-content: right;

    }

    .text{
    flex: 1;
    font-size: 40px;
    padding-top: 65px;
    margin-left: 51px;
    }

    .blue{
    color:#2d2c62;
    }

    .red{
    color: #fa676d;
    }

    .desc{
    font-size:large;
    color:#a091da;
    font-weight: lighter;
    }

    input{
    
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
    border: 0;
    padding: 20px;
    }

    button{
    border: 0;
    background-color: #5654b3;
    color: white;
    padding: 20px 45px;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
    }

    i{
    font-size: 30px;
    }

    html *{
    font-family:"Montserrat";
    }
