<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Microsoft Clone </title>
	<link  rel="icon" type="image/x-icon" href="microsoftlogo.png">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js" 
	integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g==" 
	crossorigin="anonymous" referrerpolicy="no-referrer"></script>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" 
	integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" 
	crossorigin="anonymous" referrerpolicy="no-referrer" />
     <style type="text/css">
     	*{
			box-sizing: border-box;
			margin: 0;
			padding: 0;

		}
		body{
			font-family: "Segoe UI" Tahoma, Geneva;
			background-color: #fff;
			color: #000;
			font-size: 15px;
			line-break: 1.5;
		}
		a{
			color: #262626;
			text-decoration: none;

		}
		ul{
			list-style: none;
		}
		.container{
         width: 90%;
		 max-width: 110%;
		 margin: auto;
		}
          .main-nav{
			display: flex;
    align-items: center;
    justify-content: space-between;
    height: 60px;
    padding: 20px 0;
    font-size: 13px;
		  }
		  .main-nav .logo{
			width: 110px;
		  }
		  .main-nav ul {
    display: flex;
}

.main-nav ul li {
    padding: 0 10px;
}



		  .main-nav ul li a:hover{
			border-bottom: 2px solid #262626;
		  }
		 
		  
		  .showcase{
		background-image: url(card2.png);
		align-items: center;
		text-align: center;	
		justify-content: flex-end;
		height: 150px;
		animation:anim 10s infinite ;

		  }
		  @keyframes anim{
             0%{
				background-image: url(card2.png);
				
			 }
			 25%{
				background-image: url(card3.png);
				
			 }
			 50%{
				background-image: url(card4.png);
				
			 }
			 75%{
				background-image: url(card5.png);
				
			 }
			 100%{
				background-image: url(card6.jpg);
				
			 }
		  }
		  .showcase h2{
			margin-top: 20px;
		  }
		  .showcase p{
			margin-top: 25px;
		  }
			
		  
		 .btn{
			background-color: #f16a6a;
          color: #fff;
		  font-size: 18px;
		  }
		  .btn:hover{
			color: rgb(23, 231, 40);
		  }
		  .home-cards{
			display:flex;
			justify-content: space-between;
		  }
		  .home-cards p{
			width: 200px;
		  }
		  .home-cards a{
			color: blue;
		  }
		  /*.home-cards:hover{
			transform: translatex(30%);
		  }*/
		  .content{
			color: #fff;
			background-image: url(card8.png);
			width: 100%;
			height: 350px;
		
		  }
		  .content h2{
			margin-top: 30px;
		  }
		   .content p{
			width: 300px;
		   margin-top: 50px;
		  }
		  .links-inner{
			display: grid;
			grid-template-columns: repeat(6, 1fr);
			grid-gap: 10px;
			line-height: 30px;
		  }
		  .footer-inner{
			display: flex;
		  }
		  footer-inner li{
			display: flex;
			flex-wrap: wrap;
		  }
		@media screen and(min-width :767px){
		main-nav{
			background-color: #f16a6a;
		}
		}
     </style>
</head>
<body>
<div class="menu-btn">
<div class="container"
        <nav></nav>
<nav class="main-nav">
	<img src="microsoftlogo.png" alt="microsoft" class="logo"/>
	<ul class="main-menu">
		<li><a href="#">Office</a></li>
		<li><a href="#">Windows</a></li>
		<li><a href="#">Surface</a></li>
		<li><a href="#">Xbox</a></li>
		<li><a href="#">Deals</a></li>
		<li><a href="#">Support</a></li>

	</ul>
	<ul class="right-menu">
		<li><a href="#"><i class="fa fa-search" aria-hidden="true"></i>
		</a></li>
		<li><a href=""><i class="fa fa-shopping-cart" aria-hidden="true"></i></a></li>
	</ul>
</nav>
<header class="showcase">
	<h2> Surface Deals</h2>
	<p> Select Surfaces are on sale now - save while supplies last</p>
	<a href="#" class="btn"> Shop Now <i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	Sharma Shab
</header>	<br><br>
<div class="home-cards">
	<div>
		<img src="card1.png">
		<h3>New Surface Pro 7</h3>
		<p>           Express yourself powerfully with a thin, light, and elegant design, 
			faster performance, and up to 11.5 hours battery life.</p>
			<div id="javasc"><a href="#" id="learn">Learn More<i class="fa fa-chevron-right" aria-hidden="true"></i></a></div>
	</div>
	<div>
		<img src="card2.png">
		<h3> New Surface Laptop 3</h3>
		<p> Express yourself powerfully with a thin, light, and elegant design, faster
			performance, and up to 11.5 hours battery life.</p>
			<a href="#">Learn More<i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>
	<div>
		<img src="card3.png">
		<h3>Save $150 + free controller</h3>
		<p>Buy an Xbox One X console and double your fun with a free select extra controller
			. Starting at $349.</p>
			<a href="#">Learn More<i class="fa fa-chevron-right" aria-hidden="true"></i> </a>
	</div>
	<div>
		<img src="card4.png">
		<h3> The new Microsoft Edge</h3>
		<p>
			Expect more. World class performance, with more privacy, more productivity, and more value.
		</p>
		<a href="#">Learn More <i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>
</div><hr><hr><br>
<section class="home-cards">
	<div>
		<img src="card5.png">
		<h3>Microsoft Team</h3>
		<p>Unleash the power of your team.</p>
		<a href="#">SHOP NOW<i class="fa fa-chevron-right" aria-hidden="true"></i> </a>
	</div>
	<div>
     <img src="card6.jpg">
	 <h3>Unlock the power of learning </h3>
	 <p> Get students future-ready with Windows 10 devices. Starting at $219.</p>
	 <a href="#">SHOP NOW<i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>
	<div>
    <img src="card7.png">
	<h3>Windows 10 Enterprise </h3>
	<p> Download the free 90-day evaluation for IT professionals.</p>
	<a href="#">DOWNLOAD NOW<i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>
	<div>
      <img src="card8.png">
	  <h3> Explore Kubernetes</h3>
	  <p>Learn how Kubernetes works and get started with cloud native app development today.</p>
	  <a href="#">GET STARTED<i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>
</section>
<section class="carbon-dark">
	<div class="content">
		<h2>Commiting To Carbon Negative</h2>
		<p>Microsoft will be carbon negative by 2030 and by 2050 we will remove all carbon the
			 company has emitted since it was founded in 1975</p>
          <a href="#"class="btn">Learn More<i class="fa fa-chevron-right" aria-hidden="true"></i></a>
	</div>

</section><br><br>
<section class="follow">
	<p>Follow Microsoft</p>
<a href="https://facebook.c om">
	<img src="OIP.jpeg" alt="facebook"width="30px" height="30px">
</a>
<a href="https://twitter.com">
	<img src="twitter.jpeg" alt="twitter"width="30px" height="30px">
</a>
<a href="https://linkedin.com">
	<img src="linkedin-icon-png.png" alt="linkedin" width="30px" height="30px">
</a>
</section><br><br>
<section class="links">
	<div class="links-inner">
		<ul>
			<li>
				<h3>What's New</h3>
			</li>
			<li><a href="#"> Pro X</a></li>
			<li><a href="#"> Surface Laptop 3</a></li>
			<li><a href="#"> Surface Pro 7</a></li>
			<li><a href="#"> window 10 apps</a></li>
			<li><a href="#"> Office Apps</a></li>
		
		</ul>
		<ul>
			<h3>Microsoft Store   </h3>
			<li><a href="#">Account Profile</a>  </li>
			<li><a href="#">Dowload center</a> </li>
			<li> <a href="#">Microsoft Store support</a></li>
			<li><a href="#">Return</a> </li>
			<li><a href="#">Older tracking</a> </li>
		</ul>
		<ul>
             <li><h3> Education </h3></li>
             <li><a href="#"> Microsoft in education </a> </li>
            <li><a href="#">Office for student</a></li>
            <li><a href="#">Office 365 for schools</a></li>
            <li><a href="#">Deals for students</a></li>
              <li><a href="#">Microsfot Azure</a> </li>
		</ul>
		<ul>
          <li><h3> Enterprises </h3></li>
		  <li> <a href="#">Azure</a></li>
		  <li> <a href="#">AppSource</a></li>
		  <li><a href="#"> AutoMotive</a> </li>
		  <li><a href="#">Goverment</a> </li>
		  <li><a href="#">Healthcare</a> </li>
		</ul>
		<ul>
           <li><h3> Developer</h3></li>
		   <li><a href="#">Visual Studio</a></li>
		   <li><a href="#">Windowszs Dev Center</a></li>
		   <li><a href="#">Developer Network</a></li>
		   <li><a href="#">techNet</a></li>
		   <li><a href="#">Microsoft Developer</a></li>
		</ul>
		<ul>
          <li><h3> Company </h3></li>
		  <li> <a href="#">Careers</a></li>
		  <li><a href="#">About Microsfot</a></li>
		  <li><a href="#">Company News</a></li>
		  <li><a href="#">Privacy at Microsfot</a></li>
		  <li><a href="#">Investors</a></li>
		</ul>

	</div>

</section><br><br>
<footer class="footer">
<div class="footer-inner">
	<ul>
		<li><a href="#">Contact Microsfot</a></li>
		<li><a href="#">Privacy & Cookies</a></li>
		<li><a href="#">Terms of use</a></li>
	</ul>

</div>

</footer><br>
<div class="history">
<button value="click" onclick="msg()"><a href="#">View History</a>

</button><hr><hr><br><br><br>
</div>
</div>
<script>
	alert("Are you sure enter this website")

	$ (document).ready(function (){
     $("#javasc").click(function(){
            $(this).hide('slow')
          });
		});
		$("#javasc").click(function(){
            $(this).show('slow')
          });
		
	function msg(){
		open("microsofthistory.html")
	};
</script>
</body>
</html>
