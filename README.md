html css and js repo
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0>
        <title>MOLDAYS GRANT WEBSITE</title>
        <link rel="stylesheet" href="app.css">
    </head>
    <body>
        <div class="container">
            <nav class="navbar">
                <div class="logo">
                    <a href="#">MOLDAYS</a>
                </div>
                <ul class="menu">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Skills</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
            <div class="showcase-content">
                <div class="lead-1">Hello, my name is</div>
                <div class="lead-2">Molday Fidel</div>
                <div class="lead-3">And I'm a <span class="effect"></span></div>
                <a href="#">Hire me</a>
            </div>
        </div>
        <style>
            *{
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                font-family: 'Tahoma', sans-serif;
                text-decoration: none;
            }
            .container{
                width: 100%;
                height: 100vh;
                padding: 0 80px;
                margin: auto;
                background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),url('/home/fidel/Desktop/IMG_20231107_150359_812.jpg');
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
                color: #fff;
            }
            .container .navbar{
                width: 100%;
                padding: 25px 0;
                font-family: 'Tahoma',sans-serif;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .navbar .logo a{
                color: #5f1782;
                font-size: 35px;
                font-weight: 800;

            }
            .navbar .menu li{
                list-style: none;
                display: inline-block;
            }
            .navbar .menu li a{
                display: block;
                color: #5f1782;
                font-size: 18px;
                font-weight: 800;
                margin-left: 25px;
                transition: color 0.5s ease;
            }
            .navbar .menu li a:hover{
                color: #fff;
            }
            .showcase-content{
                max-width: 700px;
                margin-top: 150px;
                margin-left: 55%;
            }
            .showcase-content .lead-1{
                font-size: 35px;
            }
            .showcase-content .lead-2{
                font-size: 60px;
                font-weight: 600;
                margin-left: -5px;
            }
            .showcase-content .lead-3{
                font-size: 45px;
                margin: 2px 0;
            }
            .showcase-content .lead-3 span{
                color: #5f1782;
                font-weight: 700;
            }
            span.showcase-content a{
                display: inline-block;
                background: #5f1782;
                color: #fff;
                font-size: 25px;
                padding: 5px 40px;
                margin-top: 15px;
                border: 3px solid #5f1782;
                border-radius: 5px;
            }
            .showcase-content a:hover{
                color: #fff;
                font-weight: bold;
                background: transparent;
            }
        </style>
        <script>
          var typed = new Typed(".effect",{
            Strings:[
            "Computer scientist","Cyber Engineer",
            "Freelancer","Graphic Designer",
            "Data administrator"
            ],
            typespeed: 60,
            backspeed:40,
            loop:true
          });
        </script>
    </body>
</html>
