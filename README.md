#team page
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>team page</title>
<style>
/* Navigation styles */
nav {
background-color: #333;
padding: 10px;
text-align: center;
}
nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}

/* Container for all images */
.gallery {
width: 100%;
overflow: hidden; /* Clear floats */
padding: 20px;
box-sizing: border-box;
}

/* Style for each box containing image and text */
.box {
float: left; /* float images */
width: 23%; /* four items evenly spaced with some margin */
margin: 1%;
border: 2px solid #000; /* box around image+text */
padding: 10px;
box-sizing: border-box;
position: relative; /* apply position property */
}

/* Style for images */
.box img {
width: 100%;
height: auto;
display: block;
position: relative; /* position property example */
}

/* Style for caption text */
.caption {
text-align: center;
margin-top: 10px;
}
</style>
</head>
<body>

<!-- Navigation Section -->
<nav>
<a href="#">Home</a>
<a href="#">Gallery</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

<!-- Gallery of images -->
<div class="gallery">
<div class="box">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjEy/siberian-husky-107212.jpg?arena_f_auto" alt="Image 1" />
<div class="this is bruce and he is the companys owner. bruce founded this company thirty years ago in his appartment</div>
</div>
<div class="box">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjE5/german-shepherd-laying-in-grass-107219.jpg?arena_f_auto" alt="Image 2" />
<div class="caption">this is hank. hank served two tours in iraq were he recied the purple heart. he is now the companys forman and he is irreplceable.</div>
</div>
<div class="box">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjI1/black-lab-in-fall-leaves-107225.jpg?arena_f_auto" alt="Image 3" />
<div class="caption">this is jim the acountant. this is his second year and he dose an amazeing job.</div>
</div>
<div class="box">
<img src="https://pethelpful.com/.image/w_750,q_auto:good,c_limit/NDowMDAwMDAwMDAwMTA3MjY2/ready-to-play-107266.jpg?arena_f_auto" alt="Image 4" />
<div class="caption">this is dave and he is our sales rep. he has been in the buisness for 25 years and is almost as inested into this companys sucess as bruce is.</div>
</div>
</div>

</body>
</html>
