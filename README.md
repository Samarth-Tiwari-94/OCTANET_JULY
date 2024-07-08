<!DOCTYPE html>
<html>
<head>
	<title>Apple iPhone</title>
	<style>
		body {
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
		}
		.header {
			background-color: #141414;
			color: white;
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 20px;
		}
		.logo {
			font-size: 30px;
			font-weight: bold;
		}
		.nav {
			display: flex;
			align-items: center;
		}
		.nav a {
			color: white;
			text-decoration: none;
			margin-left: 20px;
			font-size: 16px;
			font-weight: bold;
		}
		.hero {
			background-image: url('https://www.apple.com/v/iphone/home/ah/images/overview/hero/hero_iphone_13__f2xv8smk6q6y_large.jpg');
			background-size: cover;
			height: 600px;
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
			text-align: center;
			color: white;
		}
		.hero h1 {
			font-size: 60px;
			margin: 0;
			line-height: 1.2;
		}
		.hero p {
			font-size: 24px;
			margin-top: 20px;
			margin-bottom: 40px;
		}
		.cta {
			background-color: #0070c9;
			color: white;
			padding: 20px;
			text-align: center;
		}
		.cta h2 {
			font-size: 36px;
			margin: 0;
			margin-bottom: 20px;
		}
		.cta p {
			font-size: 18px;
			margin: 0;
			margin-bottom: 20px;
		}
		.cta a {
			background-color: white;
			color: #0070c9;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			font-size: 18px;
			font-weight: bold;
		}
		.cta a:hover {
			background-color: #0070c9;
			color: white;
		}
		.footer {
			background-color: #f5f5f5;
			padding: 20px;
			display: flex;
			justify-content: space-between;
			align-items: center;
			font-size: 14px;
			color: #666;
		}
		.footer p {
			margin: 0;
		}
		.footer a {
			color: #666;
			text-decoration: none;
		}
		.footer a:hover {
			color: #0070c9;
		}
		#main-box a{
  font-size:20px;
  color:#4e94db;
  position: relative;
  bottom: 38px;
  text-decoration: none;
  font-family:"Arial";
  display:block;
  cursor: pointer;
}

#main-box a:hover{
   text-decoration: underline;
}

#main-box img {
    position: relative;
    bottom: 30px;
    width:85%;

}

.mainbox2{
  display: inline-block;
  background-color :#35283c;
  font-family: "Arial";
  width: 100%;
  text-align: center;
}

.mainbox2 h1{
  color: #ffffff;
  font-size: 75px;
  letter-spacing: -.06em;
}

.mainbox2 p{
   position: relative;
   bottom: 38px;
   font-size: 34px;
   letter-spacing: .01em;
   color:#c999bd;
}

.mainbox2 a{
  font-size: 20px;
  color:#4e94db;
  position: relative;
  bottom: 38px;
  text-decoration: none;
  font-family:"Arial";
  display:block;
}
.mainbox2 a:hover{
   text-decoration: underline;
}

#mainbox2 img {
    position: relative;
    bottom: 30px;
    width:85%;
    margin: 100%;
}

	</style>
</head>
<body>
	<header class="header">
		<div class="logo">iPhone</div>
		<nav class="nav">
			<a href="#">Home</a>
			<a href="#">iPhone 15 Pro</a>
			<a href="#">iPhone 15</a>
			<a href="#">iPhone SE</a>
			<a href="#">Compare</a>
			<a href="#">Accessories</a>
			<a href="#">Support</a>
			<a href="#">Where to Buy</a>
		</nav>
	</header>
	<div class = "mainbox2">
  <h1> iPhone 15 </h1>
  <p> Your new superpower.<p>
  <br>
  <a href ="#"> Learn more > Buy > </a>
 <img src="https://www.apple.com/v/iphone-13/e/images/meta/iphone-13_overview__fpjuzw2ncqmy_og.png" >
</div>
	<section class="hero">
		<h1>iPhone 14</h1>
		<p>Delightfully capable. Surprisingly affordable.</p>
		<a href="#" class="button">Learn More</a>
	</section>
	<section class="cta">
		<h2>Get up to $200 off a new iPhone.</h2>
		<p>Trade in your eligible device for credit toward a new iPhone. Personal setup available. Select a model or customize your own.</p>
		<a href="#">Learn more</a>
	</section>
	<footer class="footer">
		<p>© 2023 Apple Inc. All rights reserved.</p>
		<nav>
			<a href="#">Privacy Policy</a>
			<a href="#">Terms of Use</a>
			<a href="#">Sales and Refunds</a>
			<a href="#">Site Map</a>
		</nav>
	</footer>
</body>
</html>
