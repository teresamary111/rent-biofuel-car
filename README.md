# rent-biofuel-car
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
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">BIOFUEL</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">BIOFUEL</a>
      <a href="#pollution" class="w3-bar-item w3-button"><i class="fa fa-user"></i> POLLUTION</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
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
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
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
      <h1 class="w3-xxxlarge w3-text-blue"><b>What are biofuel cars?</b></h1>
      <p><span class="w3-xlarge w3-text-white">THE FUTURE IS HERE!</span> <br> <br>Biofuel is an alternative fuel to petrol and diesel as tehy reduce the amount of carbon dioxide emitted by the cars. Every gallon of biofuel that replaces a gallon of fossil fuel helps reduce greenhouse-gas emissions. <br>The greatest advantage of a biofuel system is that the most efficient fuel for the task is always being used, so these systems are significantly more efficient to run overtime Fuel storage is also streamlined, allowing more time between diesel fill-ups or reducing the size of necessary storage tanks.</p>

    </div>
    <div class="w3-col l4 m6">
      <img src="https://media.istockphoto.com/photos/car-with-mountain-and-grassland-landscape-travel-and-transport-picture-id1286143099?k=20&m=1286143099&s=612x612&w=0&h=nQPE9rtjkxzzmdvBBza0WsE5_br9R8h98Oe71wzo04I=" width="335" height="600">
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
      <h2 class="w3-wide">Confirm purchase</h2>
      <p>This is a non-refundable transaction.</p>
     
      <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail"></p>
      <button type="button" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('download').style.display='none'">CONFIRM</button>
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
    <div class="w3-col l4 m6">
      <img class="w3-image w3-round-large w3-hide-small w3-grayscale" src="/w3images/app5.jpg" alt="App" width="300" height="471">
    </div>
    <div class="w3-col l8 m6">
      <h1 class="w3-xxxlarge"><b>Air Pollution</b></h1>
 
      <p><span class="w3-xlarge">Be a part of the solution, not part of the pollution.</span> 
      <br> <br>
      Vehicle pollutants harm our health and contain greenhouse gases that cause climate change. Higher air pollution levels increase short-term respiratory infections.</p>
    </div>
  </div>
</div>

    


<!-- Pricing Section -->
<div class="w3-container w3-center w3-white" style= "padding:128px 16px" id="pricing">
  <h3 class="w3-jumbo"><b>Offers</b></h3>
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
          <h2 class="w3-opacity">$ 45</h2>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large" onclick="document.getElementById('download').style.display='block'">Confirm</button>
        </li>
      </ul>
    </div>
    <div class="w3-half w3-section">
      <ul class="w3-ul w3-card w3-hover-shadow">
        <li class="w3-light-green w3-xlarge w3-padding-32">Premium</li>
        <li class="w3-padding-16"><b>Free</b> upgrades</li>
        <li class="w3-padding-16"><b>Additional</b> three hours</li>
        <li class="w3-padding-16"><b>Coupons</b>
        <li class="w3-padding-16"><b>+700</b> Biowards</li>
        <li class="w3-padding-16">
          <h2 class="w3-opacity">$ 99</h2>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-black w3-padding-large" onclick="document.getElementById('download').style.display='block'"> Confirm</button>
        </li>
      </ul>
    </div>
  </div>
  <br>
</div>


<!-- Contact/Area Container -->
<div class="w3-container" id="contact" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us at Street 27, Al Nahda,  at Square Plaza.</p>
    <img src="/w3images/map.jpg" class="w3-image" style="width:100%">
    
    <p><strong>Rent</strong> a car today, fill in your details below to make a booking. <br> Let's progress towards a sustainable environment!<br> 
    </p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="Duration (in hours)" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2022-01-05T08:00"></p>
      
  <h2>Dropdown Button</h2>
  <p>Move the mouse over the button to open the dropdown content.</p>
  <div class="w3-dropdown-hover">
    <button class="w3-button w3-black">Hover Over Me!</button>
    <div class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button">Link 1</a>
      <a href="#" class="w3-bar-item w3-button">Link 2</a>
      <a href="#" class="w3-bar-item w3-button">Link 3</a>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message/Special requirements" required name="Message"></p>
      
      <button class="w3-button w3-black w3-padding-large" onclick="document.getElementById('sendmessage').style.display='block'"> Send message</button>
      
    </form>
  </div>
</div>

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
