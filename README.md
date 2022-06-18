# CSS-Flexbox-and-Grid-Layout
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>SEDAN</title>
    <link rel="stylesheet" type="text/css" href="style.css.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="box-container">
        <div class="box box1">
         <div class="content">
         <img src="images/icon-luxury.svg" width="=70px">
         <h1>Sedans</h1>   
         <p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising  in the city or on your next raod trip.
         </p>
         <button class="btn btn1">Learn More</button>
        </div>
    </div>
        <div class="box box2">
         <div class="content">
         <img src="images/icon-luxury.svg" width="=70px">
         <h1>Suvs</h1>   
         <p>Take an SUV for its spacious interior, power and versatility. Perfect for your next family vacation and off-road adventures.
         </p>
         <button class="btn btn2">Learn More</button>
        </div>
    </div>
         <div class="box box3">
         <div class="content">
         <img src="images/icon-luxury.svg" width="=70px">
         <h1>Luxury</h1>   
         <p>Cruise in the best car brand without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style..
         </p>
         <button class="btn btn3">Learn More</button>
        </div>
    </div>
            
        </div>
    </div>
    
   
</body>
</html>

body{
    width:100% ;
    min-height: 100vh;
    display: flex;
  justify-content: center;
  align-content: center;
}
.box-container{
    width: 100%;
    max-width: 1440px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-flow: wrap;
}
.box{
    width: 269px;
    padding: 15px;
    min-height: 430px;
}
.box1{
    background-color: hsl(31, 77%, 52%);
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
}
.box2{
    background-color: hsl(184, 100%, 22%);
}
.box3{
    background-color: hsl(179, 100%, 13%);
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}
h1{
    color: hsl(0, 0%, 95%);
    text-transform: uppercase;
    font-family: 'Lexend Deca', sans-serif;
    margin: 20px 0;
}
p{
    color: hsla(0,0%, 100%, 0.75);
    font-family: 'Big Shoulders Display', cursive;
}
.btn{
    margin: 60px 0;
    padding: 15px 40px;
    border: 0;
    border-radius: 30px;
    outline: none;
    background-color: #FFF;
    font-size: 15px;
    cursor: pointer;
}
