# Section-B
HTML & CSS coding of my businesss 
The puporse of this project was to creat an online platform that would sell things online.

Home Page

<html>
<head>
<tittle></tittle>
<meta charset="UTF-8">
<link rel="stylesheet" href="home.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
<ul>
<a href='home.html'><h1>IceForSale</h1></a>
<li><a href='register.html'>Bookings</a></li>
<li><a href='About.html'>About Us</a></li>
<li><a href="#">Advertisements</a></li>
<li><a href="Contact.html">contact</a></li>
</ul>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<a href='home.html'><h1>WeCOnNecT</h1></a>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="UTF-8">
<link rel="stylesheet" href="About.css">
</head>
<body style="font-family:Verdana;">

<div style="background-color:#f1f1f1;padding:15px;">
  <h1>Makhado Invest Group</h1>
 <p> Investments saves the day</p>
</div>

<div style="overflow:auto">
  <div class="menu">
    <div class="menuitem">Our team</div>
    <div class="menuitem">Mission</div>
    <div class="menuitem">History</div>
  </div>

  <div class="main">
    <h2>The Company</h2>
    <p>This company was started by Ittani Maemo, raised & born in rural villages of limpopo. When i started this company, i was just a dreamer like everybody else. Today we invest in medium Cap companies and start-ups. Join us if you are pationate about investments.</p>
    
  </div>

  <div class="right">
    <h2>What is our Purpose?</h2>
    <p>Our purpose is to invest, create jobs, and new opportunities both in local & international market.</p>
    <h2>Where?</h2>
    <p>We are based in South Africa, in a small town called Makhado.</p>
    <h2>Price?</h2>
    <p>The Walk is free!</p>
  </div>
</div>
<html>
<head>
<a href='home.html'><h1>WeCOnNecT</h1></a>
<link rel="stylesheet" href="Contact.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href='home.html'>Home</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">About</a>
</div>

<div id="main">
  <h2>How can we help you?</h2>
  <span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776; open</span>
</div>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
  document.getElementById("main").style.marginLeft = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
  document.getElementById("main").style.marginLeft= "0";
}
</script>
<h1>Feel free to contact Us</h1>
<p> Our whatsapp service is available 24hr's</p>

<div class="container">
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="Email">Email</label>
  <input type="text" id="Email" name="Email" placeholder="Your Email..">

    <label for="subject">Message</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>
<h2>Contact Details</h2>

<button class="accordion">Phone Number</button>
<div class="panel">
  <p>You can give us a call on +27612906409 or +27768400640</p>
</div>

<button class="accordion">Email address</button>
<div class="panel">
  <p>email us on Ittanim@gmail.com </p>
</div>

<button class="accordion">Physical address</button>
<div class="panel">
  <p>Our postal address is P.O. BOX 642 MASHAMBA 0942. we are located at limpopo, in a town called Makhado. No physical address is available at the moment. </p>
</div>



</body>
</html>


<div style="background-color:#f1f1f1;text-align:center;padding:10px;margin-top:7px;font-size:12px;"> This web page is created by Makhado Invest Group 2022.</div>

</body>
</html>
