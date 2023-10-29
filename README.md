<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Netflix smart clone</title>
  <style>
    *{
      margin: 0%;
      padding: 0%;
      box-sizing: border-box;
    }
    body{
      background-color: black;
    }
    .contain{
      background-image: url(PK-en-20231016-popsignuptwoweeks-perspective_alpha_website_medium.jpg);
      background-size: cover;
      height: 75vh;
      width: 100%;
      border-bottom: 8px solid rgba(128, 128, 128);
    }
    .bg{
      background-color: rgba(0, 0, 0, 0.445);
      height: 75vh;
      width: 100%;


    }
    .bar{
    display: flex;
 margin-left: 12%;
 margin-right: 12%;
 padding: 0px  50px;
 height: 7vh;
  margin-top: 10px;
  justify-content: space-between;
  align-items: center;
  
    }
    .bar h1{
      color: red;
      font-size: 60px;
    }
    .bar button{
      background-color: red;
      height: 2rem;
font-size: 20px;
color: white;
border: none;
border-radius:5px;
width: 80px;
    }
    .p{
      display: flex;
      height: 55%;
      justify-content:end;
      align-items: center;
      flex-direction: column;
     
      
    }
    p{
      color: white;
      text-align: center;
      font-size: 25px;
      font-weight: 500;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
      line-height: 1.5;
    }
   #p{
      font-size: 50px;
      font-weight: 700;
      color: white;
      text-align: center;
    }
    .bot{
      display: flex;
      justify-content: center;
     margin-top: 10px;
    }
    #email{
      width: 27vw;
      margin-right: 10px;
      background-color: rgba(78, 76, 76, 0.301);
      border: none;
      border: 2px solid gray;
      height: 6vh;
      border-radius: 3%;
      color: white;
      font-size: 20px;
      padding-left: 5%;
    }
    .bot button{
      background-color: red;
      font-size: 25px;
      color: white;
      font-weight: 700;
      width: 14vw;
      border-radius: 6px;
      border: none;
      margin-right: 40px;
    }
    @media (max-width:957px) {
      .bot button{
        font-size: 20px;
      }
      .bg , .contain{
        height: 65vh;
      }
    }
    @media (max-width:810px) {
     #p{
        font-size: 45px;
        margin-left: 35px;
        margin-right: 35px;
      }
    }
    @media (max-width:735px) {
      #p{
        font-size: 30px;
        margin-left: 35px;
        margin-right: 35px;
      }
      p{
        font-size: 20px
      }
      .p{
        margin-bottom: 10px
      }
     .bot button{
      width: 20vw;
     }
      
      #email{
        width: 40vw;
      }
      p{
        line-height: 1.7;
      }
    }
    @media (max-width:605px) {
      .bg ,.contain{
        height: 70vh;
      }
      .bar h1{
        font-size:40px ;
      }
      .bar{
        margin-left: 6%;
        margin-right: 6%;
        padding: 0%;
      }
      .bot{
        flex-direction: column;
        justify-content: center;
        align-items: center;
      }
      #email{
        width: 68vw;
        margin-bottom: 15px;
      }
      .bot button{
width: 25vw;
height: 6vh;
      }
      p{
        line-height: 1.8;
        margin-left: 9%;
        margin-right: 9%;
      }
    }
   
    @media (max-width:400px) {
     .bar h1{
        font-size: 35px;
      }
      p{
      line-height: 1.4;
      }
     #p{
        font-size: 32px;
      }
      .bot button{
        width: 30vw;
      }
    }
    @media (max-width:300px) {
      #p{
        font-size: 25px;
      }
      p{
        line-height: 1;
        font-size: 18px;
      }
      .bot button{
        font-size: 15px;
      }
    }
  </style>
</head>
<body>
  <div class="contain">
    <div class="bg">
      <div class="bar"><h1>Netflix</h1>
 <button>Sign In</button>     
      </div>
      <div class="p">

  <p id="p">
  Unlimited movies, TV shows, and more </p> <br>
<p>
Watch anywhere. Cancel anytime . <br> <br>

  Ready to watch? Enter your email to create or restart your membership.</p> </div>
  <div class="bot">
    <form ><input type="email" placeholder="Email adderess" name="" id="email"></form>
    <button>Get Started</button>
  </div>

    </div>
  </div>
</body>
</html>
