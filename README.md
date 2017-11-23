# Menozzi
Menozzi's Homepage
<h1> This is a heading </h1> 
<p> This is a paragraph tag </p> 
<!DOCTYPE html>
<html>
<title>Menozzi Portfolio</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
</style>
<body class="w3-light-grey w3-content" style="max-width:1600px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-collapse w3-white w3-animate-left" style="z-index:3;width:300px;" id="mySidebar"><br>
  <div class="w3-container">
    <a href="#" onclick="w3_close()" class="w3-hide-large w3-right w3-jumbo w3-padding w3-hover-grey" title="close menu">
      <i class="fa fa-remove"></i>
    </a>
    <img src="/w3images/avatar_g2.jpg" style="width:45%;" class="w3-round"><br><br>
    <h4><b>PORTFOLIO</b></h4>
    <p class="w3-text-grey">Talor Menozzi</p>
  </div>
  <div class="w3-bar-block">
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-text-teal"><i class="fa fa-th-large fa-fw w3-margin-right"></i>CONTACT</a> 
    <a href="#phone" onclick="w3_close()" class="w3-bar-item w3-button w3-padding"><i class="fa fa-user fa-fw w3-margin-right"></i>7192381092</a> 
    <a href="#email" onclick="w3_close()" class="w3-bar-item w3-button w3-padding"><i class="fa fa-envelope fa-fw w3-margin-right"></i>menozzi@wisc.edu</a>
  </div>
  <div class="w3-panel w3-large">
    <i class="fa fa-facebook-official w3-hover-opacity">https://www.facebook.com/talor.menozzi</i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
</nav>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">

  <!-- Header -->
  <header id="portfolio">
    <a href="#"><img src="/w3images/avatar_g2.jpg" style="width:65px;" class="w3-circle w3-right w3-margin w3-hide-large w3-hover-opacity"></a>
    <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-grey" onclick="w3_open()"><i class="fa fa-bars"></i></span>
    <div class="w3-container">
    <h1><b>My Portfolio</b></h1>
    <div class="w3-section w3-bottombar w3-padding-16">
    </div>
    </div>
  </header>
  
  <!-- First Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="Map1.jpg" alt="Bike Routes Map" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>Bike Routes</b></p>
        <p>This map shows a route along the rockie mountains that an avid biker would take.</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="lidar.jpg" alt="LiDAR" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>LiDAR</b></p>
        <p>Using ArcMap to create different raster views of the same image you can see several different layers and attirbutes to the same photo.</p>
      </div>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="langcan.jpg" alt="Canadian Languages" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>Languages in Canada</b></p>
        <p>Languages and region in Canada.</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="Canearth.jpg" alt="Canadian Earthquakes" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>Canadian Earthquakes</b></p>
        <p>Earthquakes in Canada.</p>
      </div>
    </div>
  </div>

  <div class="w3-container w3-padding-large" style="margin-bottom:32px">
    <h4><b>RESUME</b></h4>
    <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="TalorMenozziResume_Page_1.jpg" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>Resume Page 1</b></p>
        <p>Resume Page 2.</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="TalorMenozziResume_Page_2.jpg" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b>Resume Page 2</b></p>
        <p>Resume Page 2.</p>
      </div>
    </div>
  </div>
    <h4>About Me</h4>
	<p>I currently work for the FAA creating the Visual Flight Rules maps that pilots use when flying over the United States. 
We use a CAD based software to create these maps but will be moving into ArcGIS software in the next couple years. 
My office is located in Maryland. I have a Bachelors degree from Old Dominion University in Geography and Political Science and 
I am excited to continue my education through the University of Wisconsin!.</p>
    <!-- Progress bars / Skills -->
    <p>
<div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="TalorMenozziResume_Page_1.jpg" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
      </div>
    </div>
    </p>
    <hr>
  
  <!-- Contact Section -->
  <div class="w3-container w3-padding-large w3-grey">
    <h4 id="contact"><b>Contact Me</b></h4>
    <div class="w3-row-padding w3-center w3-padding-24" style="margin:0 -16px">
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-envelope w3-xxlarge w3-text-light-grey"></i></p>
        <p>menozzi@wisc.edu</p>
      </div>
      <div class="w3-third w3-teal">
        <p><i class="fa fa-map-marker w3-xxlarge w3-text-light-grey"></i></p>
        <p>Virginia, US</p>
      </div>
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-phone w3-xxlarge w3-text-light-grey"></i></p>
        <p>7192381092</p>
      </div>
    </div>

  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-dark-grey">
  <div class="w3-row-padding">
    <div class="w3-third">
      <h3>FOOTER</h3>
      <p>This is the conclusion of my Web Portfolio. Hope you enjoyed it!</p>
    </div>
  
    <div class="w3-third">
      <h3>Referenced</h3>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="/w3images/workshop.jpg" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">https://www.w3schools.com/css/css_icons.asp</span><br>
        </li>
      </ul>
    </div>
  </div>
  </footer>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
    document.getElementById("mySidebar").style.display = "block";
    document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
    document.getElementById("myOverlay").style.display = "none";
}
</script>

</body>
</html>
