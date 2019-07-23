# specific-images
web development project
<!DOCTYPE html>
<html>
<link href="Specific Images.css" type="text/css" rel="stylesheet"->
<head>
	<!-- metadata here -->
	<title>Specific Images.com</title>
</head>
<body>
	<div class="nav">
		<ul>
			<li><a href="second page.htm" type="html">Categories</a></li>
			<li><a href="#">Help </a></li>
			<li><a href="#">About</a></li>
		</ul>
	</div>
	<h1>Specific Images</h1>
	<center>
  <input type="text" class="search-bar" placeholder="What are you looking for..">
  <button class="search-button" type="button">
  	Search
  </button>
  </center>
<!-- content here -->
</body>
</html>
<!--transparent background: rgba(255,255,255,.2);
background: url(images/sp.jpg);
text-shadow: 10px 10px 100px #00E5FF,
	10px 10px 100px #00E5FF;

	background:url(images/l.jpg);

	--->
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
body{
	background:url(images/gb.jpg);
	background-repeat:no-repeat;  
	background-size: cover;
	background-attachment: fixed;
	padding: 0;
	margin: 0;
}
h1{
	color:white;
	text-align: center;
	font-family: Myanmar Text;
	font-weight: bold;
	font-size: 400%;
	
}
.nav ul{
	list-style: none;
	text-align: right;
	padding: 0;
	margin: 0;
}
.nav li{
	display: inline-block;
}
.nav a{
	text-decoration: none;
	color: #F2ffffff;
	width: cover;
	display: block;
	padding: 13px;
	font-size: 20px;
	font-family: Myanmar Text;
	font-weight: bold;
}
.nav a:hover{
	background: rgba(255,255,255,.2);
}
.search-bar{
	font-family: Myanmar Text;
	font-weight: bold;
	font-size: 15px;
	height: 25px;
	width: 400px;
	padding: 10px;
	border: none;
	border-radius: 5px;
	outline: none;
	

	
}
.search-button{
	font-family: Myanmar Text;
	font-weight: bold;
	font-size: 18px;
	height: 43px;
	width: 100px;
	border: none;
	border-radius: 5px;
	outline: none;
	color:#222222;
	text-align:center;
	background: #ffffff;

}
.search-button:hover{
	background: rgba(255,255,255,.5);
}
::-webkit-input-placeholder{
	color:#222222;

