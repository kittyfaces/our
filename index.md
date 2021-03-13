<!DOCTYPE html>
<html lang="en">
<title>faces</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="icon" sizes="300x300" type="image/ico" href="icon.jpeg" />
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    body {
        font-family: "Lato", sans-serif
    }

    .mySlides {
        display: none
    }
</style>
<body>

    <!-- Navbar -->
    <div class="w3-top">
        <div class="w3-bar w3-black w3-card">
            <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
            <a href="index.html" class="w3-bar-item w3-button w3-padding-large">Cattie</a>
            <a href="iletisim.html" class="w3-bar-item w3-button w3-padding-large w3-hide-small">We're here</a>
        </div>
    </div>

    <!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
    <div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
        <a href="index.html" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Main</a>
        <a href="iletisim.html" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">We're here</a>

    </div>
    <!-- Page content -->
    <div class="w3-content" style="max-width:2000px;margin-top:46px">

        <!-- Automatic Slideshow Images -->


    </div>
    

    <!-- The about Section -->
    <div class="w3-black" id="tour">
        <div class="w3-container w3-content w3-padding-64" style="max-width:800px">
            <h2 class="w3-wide w3-center">Hello everyone!</h2>
           



            <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
                <div class="w3-third w3-margin-bottom">
                    <img src="ph1.jpeg" alt="1" style="width:100%" class="w3-hover-opacity">
                    <div class="w3-container w3-white">
                 </div>
                </div>
                <div class="w3-third w3-margin-bottom">
                    <img src="ph2.jpeg" alt="2" style="width:100%" class="w3-hover-opacity">
                    <div class="w3-container w3-white">
                        
                    </div>
                </div>
                <div class="w3-third w3-margin-bottom">
                    <img src="ph3.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                    <div class="w3-container w3-white">

                    <div class="w3-third w3-margin-bottom">
                    <img src="ph4.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph5.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph6.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph7.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph8.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph9.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph10.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph11.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                <div class="w3-third w3-margin-bottom">
                    <img src="ph12.jpeg" alt="3" style="width:100%" class="w3-hover-opacity">
                </div>

                    </div>
                </div>
            </div>
        </div>
    </div>




    <!-- Ticket Modal -->
    <!-- The Contact Section -->
    <div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
        <h2 class="w3-wide w3-center">You can contact us!</h2>
        <p class="w3-opacity w3-center"><i></i></p>
        <div class="w3-row w3-padding-32">
            <div class="w3-col m6 w3-large w3-margin-bottom">
                <i class="fa fa-map-marker" style="width:30px"></i>Istanbul,TR<br>

                <i class="fa fa-envelope" style="width:30px"> </i> Email: gkysari@gmail.com<br>


            </div>

        </div>
    </div>

    <!-- End Page Content -->
    </div>

    <!-- Image of location/map -->
    <!-- Footer -->
    <footer class="w3-container w3-padding-20 w3-center w3-opacity w3-light-grey w3-xlarge">
        <a href="https://www.instagram.com/gizemthegizem/"><i class="fa fa-instagram w3-hover-opacity"></i></a>
        <a href="https://www.instagram.com/gokaaysari/"><i class="fa fa-instagram w3-hover-opacity"></i></a>

        

        <p class="w3-medium">©2020|Tüm Hakları Saklıdır|Tarafımdan</p>
    </footer>

    <script>
// Automatic Slideshow - change image every 4 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 4000);
}

// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else {
    x.className = x.className.replace(" w3-show", "");
  }
}

// When the user clicks anywhere outside of the modal, close it
var modal = document.getElementById('ticketModal');
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
    </script>

</body>
</html>
