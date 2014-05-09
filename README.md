Front_WEB-Design-
=================

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Untitled Document</title>
<link href="style.css" rel="stylesheet" type="text/css" />

<style>
body {
	background: #E1DFE1;
}
/*----this is for the black reg on top ----*/
#blackrec{
	border: thin solid #333;
	height: 65px;
	background-color:#333;
}
/*----END of black rec style----*/
#wrap{ /*--- I used Page wrap to keep the elements, tags in place (intact) whether tries to zoom in and out---*/
	width: 1000px;
	height:1500px;
	margin:auto;
	margin-top: 20px;
}
/* header contains the "Website A, Login and Join*/
header{
	position:static;
	border: none;
	height: 63px;
	text-align:left;
	margin-bottom:5px;
	margin-top: -67px;
}
/*---END---*/
/*this is for the nav (Name of the Product)*/
nav{
	border: 1px solid #CCCCCC;
	background:#FFFFFF;
	width:1000px;
	height: 360px;
	position:absolute;
	z-index: 5px;
	}
hr.line{
	margin-left:15px;
	margin-top: -15px;
	margin-bottom: 15px;
	margin-right: 15px;}
h1.siteA{
	font-family:Arial, Helvetica, sans-serif;
	font-size: 28px;
	color:#FFF;
	text-indent: 0px;}
#log{ 
	font-family:Arial, Helvetica, sans-serif;
	font-size: 20px;
	color:#FFF;
	float:right;
	margin-top: -40px;
	margin-right:0px;}
h1.title{ 
	font-family:Arial, Helvetica, sans-serif;
	font-size: 28px;
	color:#333333;
	text-indent: -30px;}
	
#leftSquare{ 
	height:250px;
	width:360px;
	background-color:#cccccc;
	margin-left: 15px;}

#S1{
	height:30px;
	width:30px;
	background-color:#cccccc;
	margin-left: 410px;
	margin-top: -250px;}
#S2{
	height:30px;
	width:30px;
	background-color:#CCCCCC;
	margin-left:450px;
	margin-top: -30px;}
#S3{
	height:30px;
	width:30px;
	background-color:#CCCCCC;
	margin-left: 490px;
	margin-top: -30px;}
.sub{
	font-family:Arial, Helvetica, sans-serif;
	color: #CCCCCC;
	text-indent:540px;
	margin-top: -20px;}
#buy{
	background-color:#c4df9b;
	height:50px;
	width:200px;
	margin-left: 410px;
	margin-top: 20px;
	text-align:center;
	font-family:Arial, Helvetica, sans-serif;
	color: #333333;
	font-size: 36px
}

#sell{
	background-color:#f9ad81;
	height:50px;
	width:200px;
	margin-left: 640px;
	margin-top: -50px;
	text-align:center;
	font-family:Arial, Helvetica, sans-serif;
	color: #333333;
	font-size: 36px
}

/*---------END of nav style---------*/

/*-------This is for the Content 1------*/

#article{
	float:left;
	border: 1px solid #cccccc;
	background:#FFFFFF;
	width: 680px;
	height: 320px;
	margin-top: -360px;
	}
#smallbox{
	border: 1px solid #CCCCCC;
	width: 90px;
	height: 90px;
	background-color: #CCCCCC;
	margin-left: 15px;
	margin-top: 15px;
	}
p.para1{
	font-family:Arial, Helvetica, sans-serif;
	font-size:24px;
	color:#3333;
	text-indent: 120px;
	margin-top: -90px;}
p.para2{
	font-family:Arial, Helvetica, sans-serif;	
	font-size:16px;
	color: #CCCCCC;
	text-indent: 120px;
	margin-top:-15px;
}
p.main{
	font-family:Arial, Helvetica, sans-serif;
	font-size:16px;
	color: #33333;
	text-indent:15px;
	margin-top:15px;
	}
#article2{
	float:left;
	border: 1px solid #cccccc;
	background:#FFFFFF;
	width: 680px;
	height: 320px;
	margin-top: -20px;
	}
/*---- END of article style-------*/

/*------ This is for the Aside--------*/
#aside{	
	float: right;
	height:360px;
	width:300px;
	background-color:#cccccc;
	margin-left: 500px;
	margin-top:380px;
	
	}
/*----END of Aside-------/


</style>
</head>

<body>

<div id="blackrec"></div>
<div id="wrap"> 

<!--Start Header-->
<header>

<h1 class="siteA">Website A</h1>     <div id="log"> LOGIN &nbsp; &nbsp; JOIN</div>
</header>
<!--- End of Header --->

<nav>
<h1 class="title"> <blockquote> Name of Product </blockquote> </h1>

<hr class="line" /><!--- this indicates the lines below the "Name of Product" ----->

		<div id="leftSquare">  </div> <!---- this is for the gray square floated at the left side ---->

<!---the 3 small square at the right side ---->
			<div id="S1"></div>
            	<div id="S2"></div>
            		<div id="S3"></div>
<!---3 small square---->


<div class="sub">and 393 people recommend this product</div>
<div id="buy" > Buy</div> <div id="sell">Sell</div>	


</nav>

<div id="aside"></div><!---- this indicates the gray sqaure at the right side --->

<!--- Content--->
<div id="article">
	<div id="smallbox"></div>
    <p class="para1"> USERNAME</p>
    <p class="para2"> May 1, 2014</p>
    <br />
    <p class="main"> Lorem Epsum </p>
</div>

<div id="article2">
	<div id="smallbox"></div>
    <p class="para1"> USERNAME</p>
    <p class="para2"> May 1, 2014</p>
    <br />
    <p class="main"> Lorem Epsum </p>
</div>

<!--- END of Content-->
<footer></footer>

</div>
</body>
</html>

