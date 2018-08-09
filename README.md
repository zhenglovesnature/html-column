# html-column
How to make the two images horizontally aligned

Here we go:


<!DOCTYPE html>
<html lang="en">
<head>

  <!-- Basic Page Needs
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta charset="utf-8">
  <title>Your page title here :)</title>
  <meta name="description" content="">
  <meta name="author" content="">

  <!-- Mobile Specific Metas
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- FONT
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link href="//fonts.googleapis.com/css?family=Raleway:400,300,600" rel="stylesheet" type="text/css">

  <!-- CSS
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="stylesheet" href="css/normalize.css">
  <link rel="stylesheet" href="css/skeleton.css">
  <link rel="stylesheet" href="css/mycss.css">

  <!-- Favicon
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="icon" type="image/png" href="images/favicon.png">

</head>
<body class="haha">


<div class="grid">
<div class="i1"><img src="images/1.jpg"></div>
<div class="i2"><img src="images/2.jpg"></div>



</class>






</body>
</html>






CSS: 

.haha{
  width:100vw;
  height:100vh;
background-repeat:no-repeat;
background-size: 100vw 1200vw;


position: absolute;




}


.grid{
display: grid;
grid-template-columns: auto auto auto auto;
border:2px solid;
grid-gap: 100px;

}



.i1{

  grid-column: 2;
border: 2px solid;

}

.i2{
border: 2px solid;



}

img{

width:50%;
display: block;
margin-left: auto;
margin-right: auto;

}



