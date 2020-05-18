+++
# Gallery section using the Blank widget and Gallery element (shortcode).
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 100  # Order that this section will appear.


title = "Gallery"
subtitle = ""
+++

<script src="http://code.jquery.com/jquery-1.4.2.min.js"></script>
<button style=display:none; onclick="myFunction1()">Try it</button>

<script>
function myFunction1() {
  alert("I am an alert box!");
}
</script>
<style>
body {
  font-family: Verdana, sans-serif;
  margin: 0;
}

* {
  box-sizing: border-box;
}

.row > .column {
  padding: 0 1px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.column {
  float: left;
  width: 25%;
}

/* The Modal (background) */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: black;
}

/* Modal Content */
.modal-content {
  position: relative;
  background-color: #fefefe;
  margin: auto;
  padding: 0;
  width: 100%;
  max-width: 786px;
}

/* The Close Button */
.close {
  color: red;
  position: absolute;
  top: 75px;
  right: 25px;
  font-size: 35px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #999;
  text-decoration: none;
  cursor: pointer;
}

.mySlides {
  display: none;
}

.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 12%;
  width: auto;
  padding: 16px;
  margin-top: -210px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 5px 0 0 5px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

img {
  margin-bottom: -10px;
}

.caption-container {
  text-align: center;
  background-color: blue;
  padding: 2px 16px;
  color: white;
}

.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}

img.hover-shadow {
  transition: 0.3s;
}

.hover-shadow:hover {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>
<body>
<h2 style="text-align:left">Click to Slide-View</h2>
<div class="row">
  <div class="column">
    <img src="ANC ARE-SCREENING PATIENTS.JPG" style="width:100%;height:262px" onclick="openModal();currentSlide(1)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="Funda height.jpg" style="width:100%" onclick="openModal();currentSlide(2)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="Tracker escorting participant to room 14.JPG" style="width:100%" onclick="openModal();currentSlide(3)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="Abdominal Measurement.jpg" style="width:100%" onclick="openModal();currentSlide(4)" class="hover-shadow cursor">
  </div>
   <div class="column">
    <img src="Height & Weight measurements.jpg" style="width:100%;height:262px" onclick="openModal();currentSlide(5)" class="hover-shadow cursor">
  </div>
   <div class="column">
    <img src="CDC IN ROOM 14.JPG" style="width:100%" onclick="openModal();currentSlide(6)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="CDC -ROOM 14.jpg" style="width:100%;height:252px" onclick="openModal();currentSlide(7)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="ROOM 14 SCHEDULER.jpg" style="width:100%;height:252px" onclick="openModal();currentSlide(8)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="TELECALLERS AND TCDC.jpg" style="width:100%;height:252px" onclick="openModal();currentSlide(9)" class="hover-shadow cursor">
  </div>
</div>

<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">

<div class="mySlides">
      <div class="numbertext">1 / 9</div>
      <img src="ANC ARE-SCREENING PATIENTS.JPG" style="width:100%">
</div>

<div class="mySlides">
      <div class="numbertext">2 / 9</div>
      <img src="Funda height.jpg" style="width:100%">
</div>

<div class="mySlides">
      <div class="numbertext">3 / 9</div>
      <img src="Tracker escorting participant to room 14.JPG" style="width:100%">
</div>
    
<div class="mySlides">
      <div class="numbertext">4 / 9</div>
      <img src="Abdominal Measurement.jpg" style="width:100%">
</div>
 
<div class="mySlides">
      <div class="numbertext">5 / 9</div>
      <img src="Height & Weight measurements.jpg" style="width:100%">
</div> 

<div class="mySlides">
      <div class="numbertext">6 / 9</div>
      <img src="CDC IN ROOM 14.JPG" style="width:100%">
</div> 

<div class="mySlides">
      <div class="numbertext">7 / 9</div>
      <img src="CDC -ROOM 14.jpg" style="width:100%">
</div> 

<div class="mySlides">
      <div class="numbertext">8 / 9</div>
      <img src="ROOM 14 SCHEDULER.jpg" style="width:100%">
</div> 

<div class="mySlides">
      <div class="numbertext">9 / 9</div>
      <img src="TELECALLERS AND TCDC.jpg" style="width:100%">
</div> 
<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

<div class="caption-container">
     <p id="caption"></p>
</div>


<div class="column">
      <img class="demo cursor" src="ANC ARE-SCREENING PATIENTS.JPG" style="width:100%" onclick="currentSlide(1)" alt="ANC ARE-SCREENING PATIENTS">
    </div>
    <div class="column">
      <img class="demo cursor" src="Funda height.jpg" style="width:100%" onclick="currentSlide(2)" alt="Funda height">
    </div>
    <div class="column">
      <img class="demo cursor" src="Tracker escorting participant to room 14.JPG" style="width:100%" onclick="currentSlide(3)" alt="Tracker escorting participant to room 14">
    </div>
    <div class="column">
      <img class="demo cursor" src="Abdominal Measurement.jpg" style="width:100%" onclick="currentSlide(4)" alt="Abdominal Measurement">
    </div>
	<div class="column">
      <img class="demo cursor" src="Height & Weight measurements.jpg" style="width:100%" onclick="currentSlide(5)" alt="Height & Weight measurements">
    </div>
	<div class="column">
      <img class="demo cursor" src="CDC IN ROOM 14.JPG" style="width:100%" onclick="currentSlide(6)" alt="CDC IN ROOM 14.">
    </div>
	<div class="column">
      <img class="demo cursor" src="CDC -ROOM 14.jpg" style="width:100%" onclick="currentSlide(7)" alt="CDC -ROOM 14.">
    </div>
	<div class="column">
      <img class="demo cursor" src="ROOM 14 SCHEDULER.jpg" style="width:100%" onclick="currentSlide(8)" alt="ROOM 14 SCHEDULER">
    </div>
	<div class="column">
      <img class="demo cursor" src="TELECALLERS AND TCDC.jpg" style="width:100%" onclick="currentSlide(9)" alt="TELECALLERS AND TCDC">
    </div>
  </div>
</div>

<script>
function openModal() {
  document.getElementById("myModal").style.display = "block";
}

function closeModal() {
  document.getElementById("myModal").style.display = "none";
}

var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
}
</script>


