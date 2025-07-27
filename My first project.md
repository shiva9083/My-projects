<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix.com</title>
    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }
        body,html{
            width:100%;
            height:100%;
        }
        .container{
            background:linear-gradient(rgba(0,0,0,0.9),rgba(0,0,0,0.6)),url('net-bg.jpg');
            height:120%;
            width:100%;
            background-size:cover;

        }
        nav{
            display:flex;
        }
        nav img{
            height:160px;
            margin-left:30px;
            margin-top:-40px;
        }
        .buttons{
            margin-top:25px;
            margin-left:500px;
        }
        .button-1{
            margin-right:15px;
            padding:5px 40px;
            border-radius:2px;
            background-color:transparent;
            color:white;
            font-weight:bold;
        }
        .button-2{
            padding:5px;
            border-radius:2px;
            border:1px solid red;
            background-color:red;
            color:white;
            cursor:pointer;
            font-weight:bold;
        }
        .button-1 option{
            color:black;
            font-weight: bold;
            backdrop-filter: blur(10px);
        }
        .content{
            color:white;
            text-align:center;
            margin-top:75px;
            font-family:sans-serif;
        }
        .content h2{
            font-size:50px;
            height:130px; 
        }
        .content h4{
            height:40px;
        }
        .content h6{
            word-spacing:2px;
            font-weight:500;
            height:30px;
            font-size:15px;
        }
        .inputs input{
            padding:15px 70px;
            margin-right:10px;
            border-radius:3px;
            font-weight: bold;
            background-color: transparent;
            border:2px solid grey;
        }
        .inputs button{
            padding:15px 40px;
            border:1px solid red;
            background-color:red;
            color:white;
            font-weight:700;
            font-size:14px;
            border-radius:3px;
        }
        .hero {
      position: relative;
      width: 100%;
      height: 300px;
      background:#111;
      border-top-left-radius: 50% 20%;
      border-top-right-radius: 50% 20%;
      border-top: 4px solid red; /* curved red border */
      z-index: 1;
      margin-top:145px;
    }
    .hero::before{
        content:"";
        position:absolute;
        top:0;
        left:0;
        right:0;
        height:140px;
        background:radial-gradient(
            ellipse at top center,
            rgba(64,100,200,0.3)0%,
            transparent 50%
        );
        pointer-events: none;
    }
    .hero-con{
        color:white;
        margin-top:60px;
        font-family:sans-serif;
        margin-left:100px;
    }
    </style>
</head>
<body>
    <div class="container">
        <nav>
            <img src="netflix logo-2.png" alt="logo">
            <div class="buttons">
            <select class="button-1">
                <option>English</option>
                <option>Hindi</option>
            </select>
            <button class="button-2">Sign in</button>
            </div>
        </nav>
        <div class="content">
            <h2>Unlimited movies, TV <br> shows and more</h2>
            <h4>Start at &#8377 149. Cancel at any time.</h4>
            <h6>Ready to watch? Enter your email to create or register yur mambership.</h6>
            <div class="inputs">
                <input type="email" placeholder="Enter address">
                <button>Get Started </button>
            </div>
        </div>
        <div class="hero">
            <h2 class="hero-con">Trending Now</h2>
        </div>
    </div>
</body>
</html>

