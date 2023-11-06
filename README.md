# weatherapphtml
<!DOCTYPE html>
<html>
<head>
    <meta charset ="UTF-8">
    <meta http-equiv="X-UA-Compatabile">
    <meta name="viewport" content = "width=device-width", initial-scale="1.0">
    <title>CLOCK</title>
    <link rel="stylesheet" href="weatherapp.css">
    <script src="weatherapp.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
</head>    
<body>
    <div class="container-fluid">
      <section class="main">
        <section class="inputs">
          <input type="text" placeholder="Enter any city..." id="cityinput">
          <input type="submit" value="Submit" id="add">
          <button placeholder="submit" id="add"></button>
        </section>
  
        <section class="display">
          <div class="wrapper">
            <h2 id="cityoutput"></h2>
            <p id="description"></p>
            <p id="temp"></p>
            <p id="wind"></p>
          </div>
        </section>
      </section>
  
    </div>
  </body>
  
  </html>
