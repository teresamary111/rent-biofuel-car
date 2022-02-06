# rent-biofuel-car main

<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size: 16px;}
img {margin-bottom: -8px;}
.mySlides {display: none;}
</style>
<body class="w3-content w3-black" style="max-width:1500px;">

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="MyNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">BIOFUEL</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right-align">
      <a href="#about" class="w3-bar-item w3-button">INFO</a>
      <a href="#pollution" class="w3-bar-item w3-button"> POLLUTION</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#cars" class="w3-bar-item w3-button"><i class="fa fa-car"></i> CARS</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-phone"></i> CONTACT</a>
      
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">BIOFUEL</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">POLLUTION</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  
</nav>


<!-- Header with Slideshow -->
<header class="w3-display-container w3-center">
  <button class="w3-button w3-block w3-green w3-hide-large w3-hide-medium" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://media.istockphoto.com/photos/road-trip-sunset-picture-id182503347?k=20&m=182503347&s=612x612&w=0&h=p75KUE8ZRO0aKhJQ4SPG1WCShbiQjQJV5znhGq9WIqA=" alt="Image 1" width="1500" height="1000"
    object-fit: cover>
    
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge">RENT A CAR NOW!</h1>
        <hr class="w3-opacity">
        <p>Bio-fuel is the next generation</p>
        
      </div>
    </div>
  </div>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://media.istockphoto.com/photos/sigiriya-picture-id480201638?k=20&m=480201638&s=612x612&w=0&h=8jSda0hGZkvrJuOj9C-hqC4KQSxHR6RTM48ZiZj0wys=" alt="Image 2" style="min-width:500px" width="1500" height="1000">
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge w3-text-red"><b>Why biofuel? </h1>
        <hr class="w3-opacity">
        <p>Biofuels safeguard energy security by reducing the world's reliance on fossil fuels.</p>
        
      </div>
    </div>
  </div>
  <div class="mySlides w3-animate-opacity">
    <img class="w3-image" src="https://media.istockphoto.com/photos/aerial-view-of-nazca-lines-monkey-in-peru-picture-id1343691262?k=20&m=1343691262&s=612x612&w=0&h=3scePmKF0eX2kIkdOBxe4fwmwVIzKazI3yY-2RjRpS8=" alt="Image 3" style="min-width:500px" width="1500" height="1000">
    <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
      <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
        <h1 class="w3-xlarge">Numerous benefits</h1>
        <hr class="w3-opacity">
        <p>Change begins with you.</p>
        
      </div>
    </div>
  </div>
  <a class="w3-button w3-black w3-display-right w3-margin-right w3-round w3-hide-small w3-hover-light-grey" onclick="plusDivs(1)">See more <i class="fa fa-angle-right"></i></a>
  <a class="w3-button w3-block w3-black w3-hide-large w3-hide-medium" onclick="plusDivs(1)">Take Tour <i class="fa fa-angle-right"></i></a>
</header>


<!-- The App Section -->
<div class="w3-padding-64 w3-black">
  <div class="w3-row-padding" id="about">
    <div class="w3-col l8 m6">
    <br> <br>
      <h1 class="w3-xxxlarge w3-text-blue"><b>What are biofuel cars?</b></h1>
      <p><span class="w3-xlarge w3-text-white">THE FUTURE IS HERE!</span> <br> <br>Biofuel is an alternative fuel to petrol and diesel as tehy reduce the amount of carbon dioxide emitted by the cars. Every gallon of biofuel that replaces a gallon of fossil fuel helps reduce greenhouse-gas emissions. <br>The greatest advantage of a biofuel system is that the most efficient fuel for the task is always being used, so these systems are significantly more efficient to run overtime Fuel storage is also streamlined, allowing more time between diesel fill-ups or reducing the size of necessary storage tanks.</p>

    </div>
    <div class="w3-col l4 m6">
    <br> <br>  <img src="https://media.istockphoto.com/photos/car-with-mountain-and-grassland-landscape-travel-and-transport-picture-id1286143099?k=20&m=1286143099&s=612x612&w=0&h=nQPE9rtjkxzzmdvBBza0WsE5_br9R8h98Oe71wzo04I=" width="600" height="350">
      <div class="w3-center w3-hide-large w3-hide-medium">
        <button class="w3-button w3-block w3-padding-large" onclick="document.getElementById('download').style.display='block'">
          <i class="fa fa-download"></i> Download Application
        </button>
        <img src="https://www.cts.umn.edu/sites/cts.umn.edu/files/2020-05/alternative2.jpg" class="w3-image w3-margin-top" width="335" height="471">
      </div>
    </div>
  </div>
</div>

<!-- Modal -->
<div id="download" class="w3-modal w3-animate-opacity">
  <div class="w3-modal-content" style="padding:32px">
    <div class="w3-container w3-white">
      <i onclick="document.getElementById('download').style.display='none'" class="fa fa-remove w3-xlarge w3-button w3-transparent w3-right w3-xlarge"></i>
      <h2 class="w3-wide">Purchase confirmed.</h2>
      <p>Thank you for choosing BIOFUEL.</p>
    </div>
  </div>
</div>

<div id="sendmessage" class="w3-modal w3-animate-opacity">
  <div class="w3-modal-content" style="padding:32px">
    <div class="w3-container w3-white">
      <i onclick="document.getElementById('sendmessage').style.display='none'" class="fa fa-remove w3-xlarge w3-button w3-transparent w3-right w3-xlarge"></i>
      
      
     <h2 class="w3-wide">Message has been sent.</h2>
     
     
     
    </div>
  </div>
</div>
    </div>
  </div>
</div>



<!-- Pollution Section -->
<div class="w3-padding-64 w3-light-grey">
  <div class="w3-row-padding" id="pollution">
    <div class="w3-col l4 m6"><br><br>
      <img class="w3-image w3-round-large w3-hide-small w3-grayscale" src="https://media.istockphoto.com/photos/smoke-from-the-car-exhaust-picture-id1294597903?k=20&m=1294597903&s=612x612&w=0&h=qWuFZU5rfq4r4Re6kSi3IcoqabYcnTnlETMynajhB-U=" alt="App" width="400" height="600">
    </div>
    <div class="w3-col l8 m6"><br>
      <h1 class="w3-xxxlarge"><b>Air Pollution</b></h1>
 
      <p><span class="w3-xlarge">Be a part of the solution, not part of the pollution.</span> 
      <br> <br>
      Air pollution is a mix of hazardous substances from both human-made and natural sources. Vehicle emissions, fuel oils and natural gas to heat homes, by-products of manufacturing and power generation, particularly coal-fueled power plants, and fumes from chemical production are the primary sources of human-made air pollution.<br> Higher air pollution levels increase short-term respiratory infections.</p>
    </div>
  </div>
</div>

    


<!-- Pricing Section -->
<div class="w3-container w3-center w3-white" style= "padding:128px 16px" id="pricing">
  <h3 class="w3-jumbo"><b>Pricing</b></h3>
  <p class="w3-large">Earn biowards as you go!</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-half w3-section">
      <ul class="w3-ul w3-card w3-hover-shadow">
        <li class="w3-light-blue w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16"><b>Free</b> upgrades</li>
        <li class="w3-padding-16"><b>Additional </b> one hour</li>
        <li class="w3-padding-16"><b>Coupons</b>
        <li class="w3-padding-16"><b>+250</b> Biowards </li>
        <li class="w3-padding-16">
          <h2 class="w3-opacity">AED 200</h2>
        </li>
        
          
        
      </ul>
    </div>
    <div class="w3-half w3-section">
      <ul class="w3-ul w3-card w3-hover-shadow">
        <li class="w3-light-green w3-xlarge w3-padding-32">Premium</li>
        <li class="w3-padding-16"><b>50% off </b> next ride </li>
        <li class="w3-padding-16"><b>Additional three</b> hours</li>
        <li class="w3-padding-16"><b>Coupons</b>
        <li class="w3-padding-16"><b>+700</b> Biowards</li>
        <li class="w3-padding-16">
          <h2 class="w3-opacity">AED 550</h2>
        </li>
        
        
      </ul>
    </div>
  </div>
  <br>
</div>

<!-- !PAGE CONTENT! -->
<div class="w3-container w3-center w3-white" style="max-width:1500px;margin-top:100px"id="cars">
<br> <br> <h3 class="w3-jumbo"><b>OUR OPTIONS:</b></h3>

  
  <!-- First Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVONkcdC2Aj1Y30DPuu0TpIcNgc3jJnqxbQg6XconSsv1nDJJs5ewfrxJX-93GYtTaF3w&usqp=CAU" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>TWO-SEATER</b></p>
        <p>A passenger car with four doors and a separate trunk.</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://www.motorverso.com/wp-content/uploads/2016/06/BMW-F87-M2-Coupe-N55-3.0i-4-1200x630.jpg" alt="Norway" style="width:102%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>FOUR-SEATER</b></p>
        <p>A fixed-roof car with a sloping rear roofline with multiple rows of seats.</p>
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="https://cdn.motor1.com/images/mgl/MQwj6/s1/most-expensive-to-maintain-and-repair.jpg" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>MINI-VAN</b></p>
        <p>A shared interior volume for passengers and a rear door that is hinged at roof level.</p>
      </div>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://www.motortrend.com/uploads/2021/10/2022-Ford-Transit.jpg" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>FORD CARGO VAN</b></p>
        <p>Ford Cargo Van is highly versatile and offers many modern conveniences, a fuel-efficient engine lineup and decent road manners.</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://cdn.motor1.com/images/mgl/Bj946/s1/2021-toyota-prius-front-quarter-wide.jpg" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>TOYOTA PRIUS</b></p>
        <p>Toyota Prius boasts ample, comfortable seating space and a long list of features, powered by biofuel.</p>
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="data:image/jpeg;base64,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" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>JAGUAR XE 20D</b></p>
        <p>Jaguar's greener side ranging from its lightweight construction to high-performance engines that could get more than 50 mpg.</p>
      </div>
    </div>
  </div>


  
<!-- Contact/Area Container -->

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  font-family: Arial;
  font-size: 17px;
  padding: 8px;
}

* {
  box-sizing: border-box;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  margin: 0 -16px;
}

.col-25 {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
}

.col-50 {
  -ms-flex: 50%; /* IE10 */
  flex: 50%;
}

.col-75 {
  -ms-flex: 75%; /* IE10 */
  flex: 75%;
}

.col-25,
.col-50,
.col-75 {
  padding: 0 16px;
}

.container {
  background-color: #f2f2f2;
  padding: 5px 20px 15px 20px;
  border: 1px solid lightgrey;
  border-radius: 3px;
}

input[type=text] {
  width: 100%;
  margin-bottom: 20px;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

label {
  margin-bottom: 10px;
  display: block;
}

.icon-container {
  margin-bottom: 20px;
  padding: 7px 0;
  font-size: 24px;
}

.btn {
  background-color: #04AA6D;
  color: white;
  padding: 12px;
  margin: 10px 0;
  border: none;
  width: 100%;
  border-radius: 3px;
  cursor: pointer;
  font-size: 17px;
}

.btn:hover {
  background-color: #45a049;
}

a {
  color: #2196F3;
}

hr {
  border: 1px solid lightgrey;
}

span.price {
  float: right;
  color: grey;
}


@media (max-width: 800px) {
  .row {
    flex-direction: column-reverse;
  }
  .col-25 {
    margin-bottom: 20px;
  }
}
</style>
</head>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  font-family: Arial;
  font-size: 17px;
  padding: 8px;
}

* {
  box-sizing: border-box;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  margin: 0 -16px;
}

.col-25 {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
}

.col-50 {
  -ms-flex: 50%; /* IE10 */
  flex: 50%;
}

.col-75 {
  -ms-flex: 75%; /* IE10 */
  flex: 75%;
}

.col-25,
.col-50,
.col-75 {
  padding: 0 16px;
}

.container {
  background-color: #f2f2f2;
  padding: 5px 20px 15px 20px;
  border: 1px solid lightgrey;
  border-radius: 3px;
}

input[type=text] {
  width: 100%;
  margin-bottom: 20px;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

label {
  margin-bottom: 10px;
  display: block;
}

.icon-container {
  margin-bottom: 20px;
  padding: 7px 0;
  font-size: 24px;
}

.btn {
  background-color: #04AA6D;
  color: white;
  padding: 12px;
  margin: 10px 0;
  border: none;
  width: 100%;
  border-radius: 3px;
  cursor: pointer;
  font-size: 17px;
}

.btn:hover {
  background-color: #45a049;
}

a {
  color: #2196F3;
}

hr {
  border: 1px solid lightgrey;
}

span.price {
  float: right;
  color: grey;
}


@media (max-width: 800px) {
  .row {
    flex-direction: column-reverse;
  }
  .col-25 {
    margin-bottom: 20px;
  }
}
</style>
</head>
<body>

<div class="row">
          <div class="col-50" id="contact">
            <h3>Contact Details</h3>
            <label for="fname"><i class="fa fa-user"></i> Full Name</label>
            <input type="text" id="fname" name="firstname" placeholder="John M. Doe">
            <label for="email"><i class="fa fa-envelope"></i> Email</label>
            <input type="text" id="email" name="email" placeholder="john@example.com">
            <label for="adr"><i class="fa fa-id-card-o"></i> Driver's License Number</label>
            <input type="text" id="adr" name="address" placeholder="8726531">
            <label for="city"><i class="fa fa-phone"></i> Contact Number</label>
            <input type="text" id="city" name="city" placeholder="+971523456789">

            <div class="row">
              <div class="col-50">
                <label for="state"><i class="fa fa-clock-o"></i> Time out</label>
                <input type="text" id="state" name="state" placeholder="5:10 pm">
              </div>
              <div class="col-50">
                <label for="time"><i class="fa fa-clock-o"></i> Time in </label>
                <input type="text" id="zip" name="zip" placeholder="1:30 pm">
              </div>
            </div>
          </div>


</div>

<div class="col-50">
  <h3>Payment</h3>
  <label for="fname">Accepted Cards</label>
  <div class="icon-container">
     <i class="fa fa-cc-visa" style="color:navy;"></i>
     <i class="fa fa-cc-amex" style="color:blue;"></i>
     <i class="fa fa-cc-mastercard" style="color:red;"></i>
     <i class="fa fa-cc-discover" style="color:orange;"></i>
  </div>
     <label for="cname">Name on Card</label>
     <input type="text" id="cname" name="cardname" placeholder="John More Doe">
            <label for="ccnum">Credit card number</label>
            <input type="text" id="ccnum" name="cardnumber" placeholder="1111-2222-3333-4444">
            <label for="expmonth">Exp Month</label>
            <input type="text" id="expmonth" name="expmonth" placeholder="September">
            <div class="row">
              <div class="col-50">
                <label for="expyear">Exp Year</label>
                <input type="text" id="expyear" name="expyear" placeholder="2022">
              </div>
              <div class="col-50">
                <label for="cvv">CVV</label>
                <input type="text" id="cvv" name="cvv" placeholder="352">
              </div>
            </div>
          </div>
         
           </div>
        <label>
          <input type="checkbox" checked="checked" name="sameadr"> I agree with the Terms and Conditions
        </label>
        
          <button class="w3-button w3-green w3-padding-jumbo" onclick="document.getElementById('download').style.display='block'"> Confirm</button>
        
        
       
      </form>
    </div>
  </div>

</body>
</html>


<!-- End page content -->
</div>


<!-- Footer -->
<footer class="w3-container w3-padding-32 w3-light-grey w3-center w3-xlarge">
  <div class="w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
 
</footer>

<script>
// Slideshow
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

</body>
</html>

#Login

<DOCTYPE html>
<html>
<body style="background-color:powderblue;">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Trajan, serif;}
form {border: 3px solid #000000;}

input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

button {
  background-color:green;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

img.avatar {
  width: 60%;
  border-radius: 50%;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}
</style>
</head>
<body>

<h2>Login Form</h2>

<form action="/action_page.php" method="post">
  <div class="imgcontainer">
    <img src="https://www.kindpng.com/picc/m/78-785975_icon-profile-bio-avatar-person-symbol-chat-icon.png" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
    <html>    
  <body> 
    
    <a href="https://rentbiofuelcars.w3spaces.com/main.html">
      <input type="submit"/>
    </a>
    
  </body>    
</html>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:#000000"> 
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw"<p style="color:white">Forgot <a href="#"<p style="color:white">password?</a></span>
  </div>
</form>

</body>
</html>
