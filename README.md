# team-page
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Images with Text and Navigation</title>
<style>
/* Container for all items */
.container {
width: 100%;
overflow: hidden; /* Clear floats */
position: relative;
}

/* Individual item style */
.item {
width: 45%;
margin: 2%;
padding: 10px;
border: 1px solid #ccc;
/* Set position for further positioning if needed */
position: relative;
/* Float to align side by side */
float: left;
}

/* Image style with float and position */
.item img {
float: left;
position: relative;
width: 100px;
height: auto;
margin-right: 10px;
}

/* Text next to image with absolute positioning */
.text {
position: absolute;
top: 10px;
left: 120px; /* Position it next to the image */
right: 10px;
}

/* Navigation section styling */
nav {
clear: both;
margin-top: 20px;
padding: 10px;
background-color: #f0f0f0;
position: relative;
}

nav a {
margin: 0 15px;
text-decoration: none;
color: #333;
position: relative;
}
</style>
</head>
<body>

<h1>Gallery with Text and Navigation</h1>

<div class="container">
<!-- First Item -->
<div class="item">
<img src="https://via.placeholder.com/100" alt="Image 1" />
<div class="text">This is the description for image 1.</div>
</div>
<!-- Second Item -->
<div class="item">
<img src="https://via.placeholder.com/100" alt="Image 2" />
<div class="text">This is the description for image 2.</div>
</div>
<!-- Third Item -->
<div class="item">
<img src="https://via.placeholder.com/100" alt="Image 3" />
<div class="text">This is the description for image 3.</div>
</div>
<!-- Fourth Item -->
<div class="item">
<img src="https://via.placeholder.com/100" alt="Image 4" />
<div class="text">This is the description for image 4.</div>
</div>
</div>

<!-- Navigation Section -->
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</nav>

</body>
</html>
