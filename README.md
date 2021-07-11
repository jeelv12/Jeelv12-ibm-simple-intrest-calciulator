<!DOCTYPE html>
<html>
<head>
	<title>SIMPLE INTREST CALCULATOR</title>
	<script type="text/javascript" src="path-to-script.js"></script>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	
</head>
<body>
     <div class="abc">
        <h1>Simple Interest Calculator</h1>

        Amount <input type="number"  id="principal" onchange="validateAmount()">  <br/>
        Rate <input type="range" id="rate" min="1" max="20" step="0.25" value="10.25" onchange="getSliderValue()"><span id="rateSpan">10.50%</span>  <br/>
        No. of Years  
        <select name="years" id="years">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
            <option value="11">11</option>
            <option value="12">12</option>
            <option value="13">13</option>
            <option value="14">14</option>
            <option value="15">15</option>
          </select><br/>

        <button onclick="compute()">Compute Interest</button><br/>
        <span id="result"></span><br>
        <span id="result"></span>

        <footer >Thank You.</footer>
  </div>
  
    </body>
</html>
