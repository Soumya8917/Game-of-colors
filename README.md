# Game-of-colors
the project is the combination of html,css,&amp; javascript

 <!DOCTYPE html>
 <html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SIMON SAYS GAME</title>
  <link rel="stylesheet" href="style.css">
 </head>
 <body>
   <h1> SIMON SAYS GAME</h1>
    <h2> click any key to start the game</h2>
   <div class="button-container">
    <div class="line-one">
      <div class="btn yellow" type="button" id="yellow"></div>
      <div class="btn blue" type="button" id="blue"></div>
    </div>
 <div class="btn-two">
  <div class="btn red" type="button" id="red"></div>
  <div class="btn purple"type="button" id="purple"></div>
</div>
  </div>





  
  <script src="app.js"></script>
 </body>
 </html>

  body{
    text-align: center;

 }
  
 .button-container{
    display: flex;
justify-content: center;

 }
 .yellow{
    height: 200px;
    width: 200px;
    border: 4px solid black;
    border-radius: 10%;
    margin: 1rem;
    background-color: rgb(210, 210, 61);
 }
 .blue{
    height: 200px;
    width: 200px;
    border: 4px solid black;
    border-radius: 10%;
    margin: 1rem;
    background-color: rgb(99, 99, 232);
 }
 .red{
    height: 200px;
    width: 200px;
    border: 4px solid black;
    border-radius: 10%;
    margin: 1rem;
    background-color: rgb(235, 47, 47);
 }
 .purple{
    height: 200px;
    width: 200px;
    border: 4px solid black;
    border-radius: 10%;
    margin: 1rem;
    background-color: rgb(218, 30, 218);
 }
 .flash {
    background-color: white;
 }
 .userFlash{
   background-color: green;
 }
