# team-page

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>team page</title>
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

<h1>team page</h1>

<div class="container">
<!-- First Item -->
<div class="item">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjEy/siberian-husky-107212.jpg?arena_f_auto/100" alt="Image 1" />
<div class="text">dave is our product manager. he loves to walk and jog. dave is 23 and has woked here for 3 years. before joining our team he was a ski instructer.</div>
</div>
<!-- Second Item -->
<div class="item">
<img src="[auto](https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjI1/black-lab-in-fall-leaves-107225.jpg?arena_f_auto/100" alt="Image 1" /><div class="text">this is suzan our receptionest. suzan has workd with us for one year but has alredy proven herself as a would class receptionest she loves to garden and before joining our team she worked at a green house.</div>
</div>
<!-- Third Item -->
<div class="item">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3Mjg1/kuvasz-107285.jpg?arena_f_auto/100" alt="Image 3" />
<div class="text">this is fred our top forman. he has served two tours in iraq and receved a puple heart. he has been a valued membe for 10 years and he is 40 years old. fred leads a expirenced crew who carry out the majority of the companys labor.</div>
</div>
<!-- Fourth Item -->
<div class="item">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjE5/german-shepherd-laying-in-grass-107219.jpg?arena_f_auto/100" alt="Image 4" />
<div class="text">this is jimmy our newest full time employee. although he has woked summers for the last two years he was just hiered full time last week. he is 18 and has an incredibal drive to become a forman one day.</div>
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
