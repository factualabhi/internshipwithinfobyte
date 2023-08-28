<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TEMPERATURE CONVERTOR SITE:</title>
    <link rel="shortcut icon" href="hepi.jpg" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <span id="element"></span>
    <div class="container">
        <div class="title">
    <h1>Temperature Converter</h1>
        </div>
        <div id="celsius">
            <input type="number" name="" placeholder="Celsius">
            <span class="icon">&#x2103;</span>
        </div>
        <div id="fahrenheit">
            <input type="number" name="" placeholder="Fahrenheit">
            <span class="icon">&#x2109;</span>
        </div>
        <div id="kelvin">
            <input type="number" name="" placeholder="Kelvin">
            <span class="icon">&#x212A;</span>
        </div>
        <div class="button">
            <button>All Clear</button>
        </div>
    </div>
    <script src="script.js"></script>
    <!-- linking the typedjs file here-->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!--animation here-->
    <script>
        var typed = new Typed('#element',{
        strings:['USE MY CONVERTOR:-']
        ,typespeed:50,});
      </script>
</body>
</html>
