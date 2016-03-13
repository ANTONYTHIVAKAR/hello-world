# hello-world
Just for a new repository
<!DOCTYPE html>
<html lang="en">
<head>
<title></title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;">
<link rel="stylesheet" href="css/prettyPhoto.css" type="text/css">
<link rel="stylesheet" href="css/flexslider.css" type="text/css">
<link rel="stylesheet" href="css/style.css" type="text/css">
<!--[if lt IE 9]>
<script src="js/html5.js"></script>
<script src="js/selectivizr-min.js"></script>
<link rel="stylesheet" href="css/ie.css" type="text/css">
<![endif]-->
<script src="js/jquery.min.js"></script>
<script src="js/jquery.easing.1.3.js"></script>
<script src="js/jquery-ui-1.8.16.custom.min.js"></script>
<script src="js/all-in-one-min.js"></script>
<script src="js/setup.js"></script>
<script>
$(window).load(function () {
    $('.flexslider').flexslider();
});

$(function () {
    $('#work').carouFredSel({
        width: '100%',
        scroll: 1,
        auto: false,
        pagination: false,
        prev: '.prev_item',
        next: '.next_item'
    });

    $("#work").touchwipe({
        wipeLeft: function () { $('.next_item').trigger('click'); },
        wipeRight: function () { $('.prev_item').trigger('click'); }
    });
});

$(window).load(function(){
	$('#demo-side-bar').removeAttr('style');
});
</script>
<style type="text/css">
.demobar {
	display:none;
}
#demo-side-bar {
	top:53px!important;
	left:90%!important;
	display:block!important;
}
</style>
</head>
<body>


 
<!-- Social -->
	 
<p class="right" align="top"> <a href="#" class="socials facebook" ><img src="images\facebook.png"/></a> <a href="#" class="socials rss" title="Rss"><img src="images\diverso-footer-rss.png"/></a>  <a href="#" class="socials mail" title="Mail"><img src="images\email.png"/></a><header class="header_bg clearfix">	</p>
	<!-- /Social -->
    <!-- Logo -->
	<div class="logo"> <a href="index.html"><img src="images/logo.png" alt=""></a> </div>
    <!-- /Logo -->
    <!-- Master Nav -->
	<div class="menuwrapper1">
    <div nav class="main-menu">
	
      <ul>
        <li><a href="index.html">Home</a></li>
		 <li class="current"> <a href="services.html">Services </a>
          <ul>
		    <li class="current"> <a href="websiteservices.html">Website services</a>
			<ul>
                <li class="current"><a href="static website.html">Static websites</a></li>
                <li><a href="dynamic website.html">Dynamic Website</a></li>
                <li><a href="request responce.html">Response Website </a></li>
                <li><a href="website redisign.html">Website Redesign</a></li>
              </ul>
            </li>
			<li class="current"> <a href="#">E-Commerce</a>
			<ul>
                <li class="current"><a href="E-commerce.html">Basic E-Commerce </a></li>
                <li><a href="Complete E-commerce.html">Complete E-Commerce</a></li>
                <li><a href="EBS Payment Gateway.html">EBS Payment Gateway</a></li>
              </ul>
            </li>
           <li class="current"> <a href="BPO Services.html">BPO Services</a>
			<ul>
                <li class="current"><a href="Android.html">Android</a></li>
                <li><a href="Iphone.html">IPhone</a></li>
                <li><a href="BlackBerry.html">BlackBerry</a></li>
                <li><a href="Windows.html">Windows</a></li>
              </ul>
            </li>
            <li class="current"> <a href="Internet Marketing.html">Internet Marketing</a>
			<ul>
                <li class="current"><a href="SEO Marketing.html">SEO Marketing</a></li>
                <li><a href="email marketing.html">E-Mail Marketing</a></li>
            </ul>
            </li>
          </ul>
     </li>
        <li><a href="portfolio.html">Portfolio</a>
        <ul>
          <li><a href="Website Portfolio.html">Website Portfolio</a></li>
          <li><a href="Logo Portfolio.html">Logo Portfolio</a></li>
		  <li><a href="Media Work Portfolio.html">Media Work Portfolio</a></li>
          <li><a href="Mobile App Porrtfolio.html"> Mobile Apps Portfolio</a></li>
          <li><a href="Media Work Portfolio.html">MediaWork Portfolio </a></li>
        </ul>
      </li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
	</div>
	</div>
    <!-- /Master Nav -->
  </div>
</header>
<!-- /Header -->
<div class="clear"></div>
<!-- Slider -->
<div class="full-width-slider-wrapper clearfix">
		<div class="full-width-slider flexslider">
				
<div class="bannerbg">
  <div class="container clearfix">
      <ul class="slides">
        <li> <img src="images/fslide01.jpg" alt="">
          <p class="flex-caption">I am Caption!</p>
        </li>
        <li> <a href="#"><img src="images/fslide02.jpg" alt=""></a> </li>
        <li> <img src="images/fslide03.jpg" alt="">
          <p class="flex-caption">I am Caption!</p>
        </li>
        <li> <img src="images/fslide04.jpg" alt=""> </li>
        <li> <img src="images/fslide05.jpg" alt=""> </li>
        <li> <img src="images/fslide06.jpg" alt=""> </li>
      </ul>
  </div>
</div>
</div>
<!-- /Slider -->
<div class="clear padding40"></div>
<!-- Content -->
<section class="container clearfix">
  <!-- START FEATURED COLUMNS -->
  <div class="col_1_3">
    <div class="features">
      <div class="title clearfix"> <img src="images/code-icon1.png" alt="" class="alignleft">
        <h3>Website Apllication Development</h3>
      </div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque id ligula in ipsum vulputate volutpat at ut nisi. Aliquam erat volutpat. Maecenas pretium dolor vitae lectus fermentum convallis bibendum in erat. Donec vitae risus non lorem volutpat fringilla in in metus. Aenean quis eros diam. Proin porta quam at neque congue iaculis. <br />
        <a href="#">more info</a></p>
    </div>
  </div>
  <div class="col_1_3">
    <div class="features">
      <div class="title clearfix"> <img src="images/mobile-app-1.png" alt="" class="alignleft">
        <h3>Mobile Application Development</h3>
      </div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque id ligula in ipsum vulputate volutpat at ut nisi. Aliquam erat volutpat. Maecenas pretium dolor vitae lectus fermentum convallis bibendum in erat. Donec vitae risus non lorem volutpat fringilla in in metus. Aenean quis eros diam. Proin porta quam at neque congue iaculis. <br />
        <a href="#">more info</a></p>
    </div>
  </div>
  <div class="col_1_3 last">
    <div class="features">
      <div class="title clearfix"> <img src="images/cms.png" alt="" class="alignleft">
        <h3>CMS Development Service</h3>
      </div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque id ligula in ipsum vulputate volutpat at ut nisi. Aliquam erat volutpat. Maecenas pretium dolor vitae lectus fermentum convallis bibendum in erat. Donec vitae risus non lorem volutpat fringilla in in metus. Aenean quis eros diam. Proin porta quam at neque congue iaculis. <br />
        <a href="#">more info</a></p>
    </div>
  </div>
  
  <!-- END FEATURED COLUMNS -->
  <div class="clear padding10"></div>
  <div class="recent_works_left">
    <h2 class="red">Recent Work </h2>
  </div>
   <div class="recent_works_arrows"> <a href="#" class="prev_item"></a><a href="#" class="next_item"></a> </div>
  <div class="clear"></div>
  <div class="line"></div>
  <div class="clear padding30"></div>
  <div class="recent_works">
    <ul id="work">
      <li id="id-1" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/featured_work_1.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Web Design and Development</a></span> <span class="clear padding15"></span> </li>
      <li id="id-2" class="util"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto"  class="img-thumb"><img class="portfolio_image" src="images/featured_work_2.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Website Maintenance</a></span> <span class="clear padding15"></span> </li>
      <li id="id-3" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/featured_work_3.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">e-Business Applications</a></span> <span class="clear padding15"></span> </li>
      <li id="id-4" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/portfolio_image_4.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Multimedia Presentation</a></span> <span class="clear padding15"></span> </li>
      <li id="id-5" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/portfolio_image_5.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Digital Marketing</a></span> <span class="clear padding15"></span> </li>
      <li id="id-6" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/portfolio_image_6.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Mobile Application development</a></span> <span class="clear padding15"></span> </li>
      <li id="id-7" class="app"> <span class="recent_image"> <a href="images/portfolio_large.jpg" data-rel="prettyPhoto" class="img-thumb"><img class="portfolio_image" src="images/portfolio_image_7.jpg" alt=""></a> </span> <span class="title"><a href="portfolio-details.html">Clean Business HTML Template</a></span> <span class="clear padding15"></span> </li>
    </ul>
  </div>
</section>


<section class="clients">
			<div class="container">
				<div class="row sub_content">
					<div class="col-lg-12 col-md-12 col-sm-12">
						<div class="dividerHeading">
							<h4><span>Our Clients</span></h4>
						</div>
						
						<div class="our_clients">
						<marquee behavior="scroll" direction="left" onmouseover="this.stop();" onmouseout="this.start();">
						
						 
     
      <a href="#"><img src="images/portfolio_image_1.jpg" height="250px" width="250px" alt="new5"></a> 
	   
	  <a href="#"><img src="images/portfolio_image_2.jpg" height="250px" width="250px" alt="new8" ></a> 
      <a href="#"><img src="images/portfolio_image_3.jpg"  height="250px" width="250px" alt="new9"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
     
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#"><img src="images/portfolio_image_4.jpg" alt="new12" ></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#"><img src="images/portfolio_image_2.jpg" alt="new13"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#"><img src="images/portfolio_image_2.jpg" alt="new14" ></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#"><img src="images/portfolio_image_2.jpg" alt="new15" ></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#"><img src="images/portfolio_image_2.jpg" alt="new16" ></a>
</marquee>
							<!--<ul class="client_items clearfix">
							<marquee behavior="scroll" direction="left" onmouseover="this.stop();" onmouseout="this.start();">
								<li class="col-sm-3 col-md-3 col-lg-3"><a href="#"  data-placement="bottom" data-toggle="tooltip" title="isupermarket" ><img src="images/clients/new12.jpg" alt="" /></a></li>
								<li class="col-sm-3 col-md-3 col-lg-3"><a href="#" data-placement="bottom" data-toggle="tooltip" title="Zeemrah"><img src="images/clients/new16.png" alt="" /></a></li>
								<li class="col-sm-3 col-md-3 col-lg-3"><a href="#" data-placement="bottom" data-toggle="tooltip" title="Thangamgroup" ><img src="images/clients/new15.png" alt="" /></a></li>
								<li class="col-sm-3 col-md-3 col-lg-3"><a href="#" data-placement="bottom" data-toggle="tooltip" title="Roshan" ><img src="images/clients/new9.png" alt="" /></a></li>
								</marquee>
							</ul>-->
							<!--/ .client_items-->
						</div>
					</div>
				</div>
			</div>
		</section>
		<!-- /Content -->
<section class="homepage_widgets_bg clearfix">
  <div class="container clearfix">
    <div class="padding20"></div>
    <!-- START COL 1/2 -->
    <div class="col_1_2 ">
      <h1 class="regular white bottom_line">About Us</h1>
      <h2><p>

We are a team of self driven and creative professionals and software consultant who are committed to providing you with the most effective and efficient web design solutions.

We give shape to your dreams by combining the most appropriate typography, images, graphics and colors to attract potential clients and turn them into loyal customers.
</p></h2>
    </div>
    <!-- END COL 1/2 -->
    <!-- START COL 1/2 -->
    <div class="col_1_2 last" id="why-section">
      <h1 class="regular white bottom_line">Contact us</h1>
<h2><pre>ELBISSOP SOFTWARE SOLUTIONS 
5/3 Thiruvengadam 2nd street
Porur
Chennai-16</pre></h2>
    </div>
    <div class="clear padding10"></div>
    <!-- end col 1/2 -->
    <!-- start col -->
    <!-- emd col -->
    <div class="clear padding80"></div>
  </div>
</section>
<!-- footer -->
<footer class="footer_bg_bottom clearfix">
  <div class="footer_bottom container">
    <div class="col_2_3">
      <div class="menu">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="elements.html">Elements</a></li>
          <li><a href="portfolio-4-cols.html">Portfolio</a></li>
          <li><a href="pricing-5-cols.html">Pricing</a></li>
          <li><a href="blog.html">Blog</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </div>
      <div class="clear padding20"></div>
      <p>&copy; Copyright 2012 <a href="#">Company Name</a> - All Rights Reserved. | Website Template By <a target="_blank" href="http://www.egrappler.com/">EGrappler</a></p>
    </div>
    <div class="clear padding20"></div>
  </div>
</footer>
<!-- /footer -->
<div id="demo-side-bar"> </div>
<!--wrapper end-->
</body>
</html>
