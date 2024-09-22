# DEVELOPPEMENT WEB

**Date of Birth:** 03/07/1991  
**Location:** Marrakech  
**Email:** hartit00@gmail.com  
**Phone:** +212775355711

## Summary
- Strong skills in web development using WordPress, PHP, HTML, JavaScript, and JQuery.
- Experience with project management and database management (MySQL).
- Familiar with statistical analysis and IT tools (MS Office, UML, Merise).

## Skills
- **Languages:** Arabic (Native), French (Fluent), English (Reading, Writing)
- **Technical Skills:** Symfony, WordPress, PHP, HTML, JavaScript, JQuery, MySQL, Project Management
- **Software:** MS Word, Excel, PowerPoint, Access

## Experience
**06/2024-Present:** Charge clientele chez wafasalaf<br>
**02/2024-Present:** Create site web <a href="travelxcursion.com">travelxcursion.com</a><br>
**02/2024-Present:** Create site web <a href="giftsmorocco.com">giftsmorocco.com</a><br>
**08/2018-Present:** Manager, Phone Accessories Store<br>
**17/11/2015 – 08/2018:** Mailer, Operating Media (Tanger)<br>
**06/04 – 16/05/2015:** Intern, RADEEL (Larache)<br>
**16/07 – 09/09/2011:** Intern, Marjane Holding (Marrakech)<br>
**01/09 – 30/09/2010:** Intern, Caisse Régionale de Crédit Agricole (Larache)<br> 
**01/08 – 31/08/2010:** Intern, Compagnie Industrielle de LUKUS (Larache)<br>

## Education
- **2013-2015:** Specialist Diploma in Software Development, ISTA Larache
- **2012-2013:** Bachelor's in Economics and Management, Abdelmalek Essaadi University
- **2011-2012:** DEUG in Economics, Abdelmalek Essaadi University
- **2008-2009:** High School Diploma in Life and Earth Sciences, Moulay Mohamed Ben Abdallah High School

## Interests
- Traveling, Internet browsing, Swimming
- Driving License (Category B)

## Diplomas

<table>
  <tr>
    <th><img src="./BACR.jpeg" width="500" height="100"/></th>
    <th><img src="./BACV.jpeg" width="500" height="100"/></th>
    <th><img src="./DEUG.jpeg" width="500" height="100"/></th>
        <th><img src="./LICENCE.jpeg" width="500" height="100"/></th>
    <th><img src="./DIPLOME.jpeg" width="500" height="100"/></th>
        <th><img src="./TELE.jpeg" width="500" height="100"/></th>
    <th><img src="./ATTIHS.jpeg" width="500" height="100"/></th>
  </tr>
</table>

<SCRIPT>
let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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
}
Automatic Slideshow
To display an automatic slideshow, use the following code:

Example
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</SCRIPT>
<STYLE>
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
</STYLE>
<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="./BACR.jpeg" style="width:100%">
    <div class="text">Caption Text</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="./BACV.jpeg" style="width:100%">
    <div class="text">Caption Two</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="./DEUG.jpeg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
</div>
