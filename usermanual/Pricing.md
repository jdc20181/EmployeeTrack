<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
    box-sizing: border-box;
}

.columns {
    float: left;
    width: 33.3%;
    padding: 8px;
}

.price {
    list-style-type: none;
    border: 1px solid #eee;
    margin: 0;
    padding: 0;
    -webkit-transition: 0.3s;
    transition: 0.3s;
}

.price:hover {
    box-shadow: 0 8px 12px 0 rgba(0,0,0,0.2)
}

.price .header {
    background-color: #111;
    color: white;
    font-size: 25px;
}

.price li {
    border-bottom: 1px solid #eee;
    padding: 20px;
    text-align: center;
}

.price .grey {
    background-color: #eee;
    font-size: 20px;
}

.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 10px 25px;
    text-align: center;
    text-decoration: none;
    font-size: 18px;
}

@media only screen and (max-width: 600px) {
    .columns {
        width: 100%;
    }
}
</style>
</head>
<body>

<h2 style="text-align:center">Responsive Pricing Tables</h2>
<p style="text-align:center">Resize the browser window to see the effect.</p>

<div class="columns">
  <ul class="price">
    <li class="header">Basic</li>
    <li class="grey">FREE</li>
    <li>Basic Clock in and out functions</li>
    <li>Basic Log support (requires a program like excel for full tracking) - Requires daily log </li>
    <li>Basic Ticket Github Support</li>
    <li>WaterMark is shown. </li>
    <li class="grey"><a href="#" class="button">Sign Up</a></li>
  </ul>
</div>

<div class="columns">
  <ul class="price">
    <li class="header" style="background-color:#4CAF50">Pro</li>
    <li class="grey">$ 299 / PC </li>
    <li>Clock in and out functions</li>
    <li>Date Clocked in Date Clocked out is shown. (Still need excel but more data is provided)</li>
    <li>Ticket, Email, And Free Techinical Support included</li>
    <li>WaterMark is only shown in the About Section (For product Support)</li>
    <li class="grey"><a href="#" class="button">Sign Up</a></li>
  </ul>
</div>



</body>
</html>
