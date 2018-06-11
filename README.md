
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 2000px;
  position: relative;
  margin: auto;
  max-height:800px;
  bottom: 20px;
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
  position:relative;
  bottom:30px;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
.slideshow-container {
	width: 100% !important;
}

.lor {
	background-image: url("https://i.ytimg.com/vi/03v7p_q04pA/maxresdefault.jpg");
	height: 400px;
	width: 100%;
	 background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
	text-align: center;
	color:white;
	position:relative;
	bottom: 50px;
	margin:14px;
}

.display {
	display: block;
	
}
.menu{
	position:fixed;
	  top: 0;
	  z-index:100;
	  width: 100%;
	  opacity: 0.6;
}

#myBtn {
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: grey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
  opacity: 0.5;
}
#myBtn:hover {
  background-color: #555;
}

.lor:hover {
	transition: 2s;
	background-image: url("https://screenshots.gamer-info.com/the-witcher-3-wild-hunt/100142.jpg");
}

.accordion {
    background-color: #eee;
    color: #444;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;

}

.active, .accordion:hover {
    background-color: #ccc;
}

.panel {
    padding-top:15px;
	
    background-color: white;
    max-height: 0;
    display:none;

}



