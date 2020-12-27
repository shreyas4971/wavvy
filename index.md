<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3pro.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">
<body>

<nav class="w3-sidebar w3-bar-block w3-card" id="mySidebar">
<div class="w3-container w3-theme">
  <span onclick="closeSidebar()" class="w3-button w3-display-topright w3">X</span>
  <br>
  <div class="w3-round-small w3-center">
    <img  src="icon.png" alt="Logo" style="width:100%">
  </div>
</div>
<h1 class="w3-bar-item">Menu</h1>
<a class="w3-bar-item w3-button" href="#">Movies</a>
<a class="w3-bar-item w3-button" href="#">Friends</a>
<a class="w3-bar-item w3-button" href="#">Messages</a>
</nav>
<a class="w3-button w3-xlarge w3-circle w3-theme-action" style="position:fixed;bottom:48px;right:24px;">+</a>
<header class="w3-bar w3-card w3-theme">
  <button class="w3-bar-item w3-button w3-xxxlarge w3-hover-theme" onclick="openSidebar()">&#9776;</button>
  <h1 class="w3-bar-item">WAVVY</h1>
</header>

<div class="w3-container">
<hr>
<button onclick="myFunction()"  class="w3-btn w3-block w3-theme-l4">Surface1_6513</button>
<div id="Demo" class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button">Projector</a>
      <a href="#" class="w3-bar-item w3-button">Keyboard</a>
</div>

<button onclick="myFunction()" class="w3-btn w3-block w3-theme-l3">Surface1_6168</button>
<div id="Demo" class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button">Projector</a>
      <a href="#" class="w3-bar-item w3-button">Keyboard</a>
</div>

<button onclick="myFunction()" class="w3-btn w3-block w3-theme-l4">Surface1_6541</button>
<div id="Demo" class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button">Projector</a>
      <a href="#" class="w3-bar-item w3-button">Keyboard</a>
</div>

<button onclick="myFunction()" class="w3-btn w3-block w3-theme-l3">Surface1_3651</button>
<div id="Demo" class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button">Projector</a>
      <a href="#" class="w3-bar-item w3-button">Keyboard</a>
</div>

<button onclick="myFunction()" class="w3-btn w3-block w3-theme-l4">Surface1_6842</button>
<div id="Demo" class="w3-dropdown-content w3-bar-block w3-border">
      <a href="#" class="w3-bar-item w3-button" style>Projector</a>
      <a href="#" class="w3-bar-item w3-button">Keyboard</a>
</div>
</div>

<script>
function myFunction() {
  var x = document.getElementById("Demo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>


<script>
closeSidebar();
function openSidebar() {
  document.getElementById("mySidebar").style.display = "block";
}

function closeSidebar() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
