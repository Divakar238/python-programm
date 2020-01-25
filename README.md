<!DOCTYPE html>
<html>
<head>
<style>
	
	a{ color:white;
		text-decoration: none;
	}
	

	body{
		  background-image:url(http://www.thehumanchain.com/wp-content/uploads/2015/11/cloud.png);
		  background-repeat: no-repeat;
		  background-size: cover;
		background-color: red;
		margin-left: 250px;
		margin-top: 20px;
	}
	#container ul{
		list-style: none;
	}
	#container ul li{
       background-color: powderblue;
       width:200px;
       border:1px solid white;
       border-radius:26px;
       height:50px;
       line-height: 50px;
       text-align: center;
       float:left;
       color: white;
       font-size: 19px;
       position: relative;
	}
	#container ul li:hover{
		background-color: purple;

	}
	#container ul ul{
		display: none;
	}	
	#container ul li:hover>ul{
		display: block;
	}
	#container ul ul ul{
             margin-left:200px;
             top:0px;
             position: absolute;
	}

</style>
	<title>amar serivces</title>
</head>
<body>
<div id="container">
<ul>
	<li><a href="#home"></a> home</li>
	<li>services
		<ul>
			<li>appliances & electronics repair 
				<ul>
					<li>geyser service and repair</li>
					<li>microwaverepair</li>
					<li>washing machine services and repair</li>
					<li>refrigerator repair</li>
					<li>ac service and repair</li>
					<li>ro or water purifier repair</li>
					<li>tv repair and installation</li>
					<li>mixer and grinder repair</li>
					<li>chimney cleaning & repair</li>
				</ul></li>
			<li>plumber
				<ul>
					<li>basin & sink</li>
					<li>bath fitting</li>
					<li>blockage</li>
					<li>tap & mixer</li>
					<li>toilet</li>
					<li>water tank</li>
					<li>motor</li>
					<li>minor installtion</li>
				</ul></li>
			<li>cooler reparing</li>
			<li>carpentery</li>
			<li>flooring</li>
			<li>web design</li>
		</ul></li>
	<li>blog</li>
	<li>about</li>
	<li><a href="#work">want to work </a></li>
</ul>
</div>
<form id="work" >
	<div>
	<input type="text" name="front name" >
	<input type="text" name="last name" >
	<input type="number" name="age" >
	<input type="occuption" name="occuption" >
	<input type="location" name="location" >
   </div>
</form>
</body>
</html>
