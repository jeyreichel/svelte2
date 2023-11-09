<script>
	import { page } from '$app/stores';
	import logo from '../assets/img/logo.png';
	import logoWhite from '../assets/img/logo-white.png';
	import circle from '../assets/img/shapes/circle.svg';
	import heroCircle from '../assets/img/shapes/hero-circle-half.svg';
	import trustPilot from '../assets/img/brands/trust-pilot.svg';
	import start5 from '../assets/img/star-5.svg';
	import heroImg from '../assets/img/hero-img.png';
	import heroRightTop from '../assets/img/shapes/hero-right-top.png';
	import heroRightBottom from '../assets/img/shapes/hero-right-bottom.svg';
	import clock from '../assets/img/clock.png';
	import perform from '../assets/img/perform.png';
	import days30 from '../assets/img/30-day.png';
	import lineRedTop from '../assets/img/shapes/line-red-top.png';
	import lineRed from '../assets/img/shapes/line-red.svg';
	import frame from '../assets/img/shapes/frame.svg';
	import mbCircleLeft from '../assets/img/shapes/mb-circle-left.png';
	import mbCircleRight from '../assets/img/shapes/mb-circle-right.png';
	import migrateShape1 from '../assets/img/shapes/migrate-shape-1.svg';
	import plusRound from '../assets/img/shapes/plus-rounded.svg';
	import migrateFrame from '../assets/img/shapes/migrate-frame.svg';
	import lineWave from '../assets/img/shapes/line-wave.svg';
	import migrate from '../assets/img/migrate.png';
	import bgShape1 from '../assets/img/bg-shape-1.jpg';
	import cpanel from '../assets/img/cpanel.png';
	import backup from '../assets/img/backup.png';
	import technology from '../assets/img/technology.png';
	import arrow from '../assets/img/shapes/arrow.svg';
	import featureImg from '../assets/img/feature-img.png';
	import consultBg from '../assets/img/consult-bg.png';
	import consultMan from '../assets/img/consult-man.png';
	import sectionCurve from '../assets/img/shapes/section-curve.png';
	import serviceShape from '../assets/img/shapes/service-shape.png';
	import wpHosting from '../assets/img/wp-hosting.png';
	import starYellow from '../assets/img/star-yellow.svg';
	import sharedHosting from '../assets/img/shared-hosting.png';
	import vpsHosting from '../assets/img/vps-hosting.png';
	import fiveStar from '../assets/img/five-star.svg';
	import google from '../assets/img/brands/google.png';
	import trustPilotLogoBlack from '../assets/img/brands/trust-pilot-logo-black.png';
	import quoteIcon from '../assets/img/shapes/quote-icon.svg';
	import twoStar from '../assets/img/two-star.svg';
	import client1 from '../assets/img/client-1.png';
	import client2 from '../assets/img/client-2.png';
	import client3 from '../assets/img/client-3.png';
	import client4 from '../assets/img/client-4.png';
	import client5 from '../assets/img/client-5.png';
	import client6 from '../assets/img/client-6.png';
	import client7 from '../assets/img/client-7.png';
	import stamps from '../assets/img/brands/stamps.png';
	import threeStar from '../assets/img/three-star.svg';
	import circleWithFrame from '../assets/img/shapes/circle-with-frame.png';
	import circleBlue from '../assets/img/shapes/circle-blue.png';
	import blog1 from '../assets/img/blog-1.jpg';
	import blog2 from '../assets/img/blog-2.jpg';
	import blog3 from '../assets/img/blog-3.jpg';
	import blog4 from '../assets/img/blog-4.jpg';
	import author1 from '../assets/img/author-1.png';
	import author2 from '../assets/img/author-2.png';
	import author3 from '../assets/img/author-3.png';
	import author4 from '../assets/img/author-4.png';
	import boxShape from '../assets/img/shapes/box-shape.svg';
	import joomula from '../assets/img/brands/joomla.png';
	import app2 from '../assets/img/brands/app-2.png';
	import app3 from '../assets/img/brands/app-3.png';
	import zendcard from '../assets/img/brands/zencart.png';
	import osticker from '../assets/img/brands/osticker.png';
	import mobile from '../assets/img/brands/mobile.png';
	import wordpress from '../assets/img/brands/wordpress.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<!--mobile menu start-->
<div class="mobile-menu position-fixed bg-white deep-shadow">
	<button class="close-menu position-absolute"><i class="fa-solid fa-xmark"></i></button>
	<a href="/" class="logo-wrapper"><img src={logo} alt="logo" class="logo logo-black"></a>
	<a href="/" class="logo-wrapper"><img src={logoWhite} alt="logo" class="logo logo-white"></a>
	<nav class="mobile-menu-wrapper mt-40">
		<ul>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}><a href="/">Home</a></li>
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}><a href="/about">About</a></li>
			<li class="has-submenu"><a href="/">Hosting</a>
				<ul>
					<li aria-current={$page.url.pathname === '/shared-hosting' ? 'page' : undefined}><a href="/shared-hosting">Shared Hosting</a></li>
					<li aria-current={$page.url.pathname === '/vps-hosting' ? 'page' : undefined}><a href="/vps-hosting">VPS Hosting</a></li>
					<li aria-current={$page.url.pathname === '/dedicated-server' ? 'page' : undefined}><a href="/dedicated-server">Dedicated Server</a></li>
					<li aria-current={$page.url.pathname === '/reseller-hosting' ? 'page' : undefined}><a href="/reseller-hosting">Reseller Hosting</a></li>
				</ul>
			</li>
			<li aria-current={$page.url.pathname === '/testimonials' ? 'page' : undefined}><a href="/testimonials">Pages</a></li>
			<li aria-current={$page.url.pathname === '/contact' ? 'page' : undefined}><a href="/contact">contact</a></li>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}><a href="/">Login</a></li>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}><a href="/">Signup</a></li>
		</ul>
	</nav>

	<div class="contact-info mt-60">
		<h4 class="mb-20">Contact Info</h4>
		<p>Chicago 12, Melborne City, USA</p>
		<p>+88 01682648101</p>
		<p>info@example.com</p>
		<div class="contact-social">
			<a href="/"><i class="fab fa-facebook-f"></i></a>
			<a href="/"><i class="fab fa-twitter"></i></a>
			<a href="/"><i class="fab fa-instagram"></i></a>
			<a href="/"><i class="fab fa-linkedin"></i></a>
		</div>
	</div>
</div>
<!--mobile menu end-->

<!--offcanvus area start-->
<div class="ofcanvus-menu">
	<button class="close-canvus"><i class="fa-solid fa-xmark"></i></button>
	<div class="megamenu">
		<h6 class="mb-20">Recommended Services</h6>
		<div class="row g-3">
			<div class="col-lg-6" aria-current={$page.url.pathname === '/shared-hosting' ? 'page' : undefined}>
				<a href="/shared-hosting" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-server"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Shared Web Hosting</h6>
							<span>Flexible virtual machines</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6" aria-current={$page.url.pathname === '/vps-hosting' ? 'page' : undefined}>
				<a href="/vps-hosting" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-box"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">VPS Hosting</h6>
							<span>Start your host business</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6" aria-current={$page.url.pathname === '/dedicated-server' ? 'page' : undefined}>
				<a href="/dedicated-server" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-database"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Dedicated Server Hosting</h6>
							<span>Keep your date safe</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6">
				<a href="/" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-globe"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Web Hosting</h6>
							<span>Start hosting your website</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6">
				<a href="/shared-hosting" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-box"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Virtual Private Server</h6>
							<span>Flexible virtual machine</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6">
				<a href="/vps-hosting" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-globe"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Cloud Hosting</h6>
							<span>Powerful bare metal servers</span>
						</div>
					</div>
				</a>
			</div>
			<div class="col-lg-6">
				<a href="/shared-hosting" class="mg-item">
					<div class="mg-item-wrapper d-flex align-items-center">
						<span class="icon-wrapper"><i class="fa-solid fa-shield"></i></span>
						<div class="mg-item-content-right ms-2">
							<h6 class="mb-0">Data Security</h6>
							<span>Keep your data safe</span>
						</div>
					</div>
				</a>
			</div>
		</div>
		<h6 class="mb-20 mt-50">Supported Scripts</h6>
		<div class="row g-3">
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-wordpress"></i></span>
						<h6>WordPress</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-hubspot"></i></span>
						<h6>Hubspot</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-joomla"></i></span>
						<h6>Joomla</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-drupal"></i></span>
						<h6>Drupal</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-wix"></i></span>
						<h6>Wix</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-shopify"></i></span>
						<h6>Shopify</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-magento"></i></span>
						<h6>Magento</h6>
					</div>
				</a>
			</div>
			<div class="col-lg-3">
				<a href="/">
					<div class="script-icon">
						<span class="script-icon-wrapper"><i class="fa-brands fa-typo3"></i></span>
						<h6>Typeo3</h6>
					</div>
				</a>
			</div>
		</div>
	</div>
</div>
<!--offcanvus area end-->

<!--hero section start-->
<section class="hero-style-1">
	<div class="hero-area overflow-hidden position-relative zindex-1 bg-primary-gradient pt-110">
		<img src={circle} alt="circle shape" class="circle-shape position-absolute">
		<img src={heroCircle} alt="circle" class="left-bottom-circle position-absolute">
		<div class="container">
			<div class="row align-items-center">
				<div class="col-lg-6">
					<div class="hero1-content-wrap">
						<div class="review-area">
							<img src={trustPilot} class="brand-logo" alt="trust pilot">
							<img src={start5} alt="star" class="star-rating mt-3 d-block">
						</div>
						<h1 class="display-font mt-4">Fastest <mark class="position-relative">Performance</mark> Web Hosting.</h1>
						<p class="lead mt-4">Touch the success! Domain and Secure Web Hosting <br class="d-none d-sm-inline-block"/> from <mark class="text-warning">$4.99 per month</mark></p>
						<div class="hero-btns mt-5">
							<a href="/" class="template-btn primary-btn me-4">Get Started</a>
							<a href="/" class="template-btn outline-btn">Explore More</a>
						</div>
					</div>
				</div>
				<div class="col-lg-6">
					<div class="hero-right">
						<img src={heroImg} alt="hero image" />
					</div>
				</div>
			</div>
		</div>
		<img src={heroRightTop} alt="rectangle shape" class="right-top position-absolute">
		<img src={heroRightBottom} alt="rectangle shape" class="right-bottom position-absolute">
	</div>
	<div class="promo-area light-bg">
		<div class="container">
			<div class="row g-4 justify-content-center">
				<div class="col-lg-4 col-md-6">
					<div class="promo-item bg-white rounded primary-shadow">
						<div class="promo-top d-flex align-items-center mb-3">
							<img src={clock} alt="clock" class="img-fluid">
							<h5 class="ms-3 mb-0">Professional Support 24/7</h5>
						</div>
						<p class="mb-0">Expert technical support available all day everyday by phone or live chat.</p>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="promo-item bg-white rounded primary-shadow">
						<div class="promo-top d-flex align-items-center mb-3">
							<img src={perform} alt="perform" class="img-fluid">
							<h5 class="ms-3 mb-0">Free Site Builder</h5>
						</div>
						<p class="mb-0">Moving to eukhost is easy, we'll take care of the migration for you for FREE</p>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="promo-item bg-white rounded primary-shadow">
						<div class="promo-top d-flex align-items-center mb-3">
							<img src={days30} alt="30 Day" class="img-fluid">
							<h5 class="ms-3 mb-0">30 Day Money Back</h5>
						</div>
						<p class="mb-0">Your money back if you change your mind. No quibble, just simple and fair.</p>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
<!--hero section end-->

<!--pricing section-->
<section class="pricing-tab-section light-bg pb-120 position-relative zindex-1 overflow-hidden">
	<img src={lineRedTop} alt="line shape" class="position-absolute right-top d-none d-lg-block">
	<img src={lineRed} alt="line shape" class="position-absolute left-bottom">
	<div class="container">
		<div class="row justify-content-center">
			<div class="col-lg-6">
				<div class="section-heading text-center">
					<h2>We Have Perfect Web Hosting Package for You</h2>
					<div class="tab-switch-btn d-inline-flex align-items-center justify-content-center position-relative mt-4">
						<span class="monthly fw-bold">Monthly Plan</span>
						<input type="checkbox" class="switch-input position-absolute">
						<span class="toggle-switch-btn rounded-pill position-relative"></span>
						<span class="yearly fw-bold">Yearly Plan</span>
					</div>
				</div>
			</div>
		</div>
		<div class="pricing-wrapper position-relative zindex-1">
			<img src={frame} alt="frame" class="position-absolute frame-shape">
			<div class="row g-4 justify-content-center mt-4">
				<div class="col-lg-4 col-md-6">
					<div class="pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow">
						<h3 class="h5">Premium <br>Web Hosting</h3>
						<span class="pricing-badge position-absolute rounded"><span class="gradient-txt">Save 40%</span></span>
						<span class="pricing-label d-block mt-4">Form only</span>
						<h4 class="h2 mt-2 monthly-price">$4.25<span>/mo</span></h4>
						<h4 class="h2 mt-2 yearly-price">$30<span>/yr</span></h4>
						<p class="mt-4">Packed with great features, such as oneclick software installs,24/7 support</p>
						<ul class="feature-list mt-4">
							<li><span class="me-2"><i class="fa-solid fa-rocket"></i></span>10 GB SSD Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-database"></i></span>10 MySQL Database</li>
							<li><span class="me-2"><i class="fa-solid fa-globe"></i></span>Unlimited Website</li>
							<li><span class="me-2"><i class="fa-solid fa-gears"></i></span>cPanel Control Panel</li>
							<li><span class="me-2"><i class="fa-solid fa-briefcase"></i></span>Auto Backup & Cloud Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-network-wired"></i></span>Free Supersonic CDN</li>
							<li><span class="me-2"><i class="fa-solid fa-window-maximize"></i></span>24 Hours Website Migration</li>
							<li><span class="me-2"><i class="fa-solid fa-lock"></i></span>Automatic SSL installation</li>
						</ul>
						<button class="expand-btn mt-4"><i class="fa-solid fa-angle-down"></i>Expand Feature</button>
						<a href="/" class="template-btn secondary-btn w-100 text-center mt-40">Purchase Plan</a>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow">
						<h3 class="h5">VPS <br>Web Hosting</h3>
						<span class="popular-badge position-absolute text-center fw-bold">Most Popular</span>
						<span class="pricing-label d-block mt-4">Form only</span>
						<h4 class="h2 mt-2 monthly-price">$5.25<span>/mo</span></h4>
						<h4 class="h2 mt-2 yearly-price">$35<span>/yr</span></h4>
						<p class="mt-4">Packed with great features, such as oneclick software installs,24/7 support</p>
						<ul class="feature-list mt-4">
							<li><span class="me-2"><i class="fa-solid fa-rocket"></i></span>10 GB SSD Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-database"></i></span>10 MySQL Database</li>
							<li><span class="me-2"><i class="fa-solid fa-globe"></i></span>Unlimited Website</li>
							<li><span class="me-2"><i class="fa-solid fa-gears"></i></span>cPanel Control Panel</li>
							<li><span class="me-2"><i class="fa-solid fa-briefcase"></i></span>Auto Backup & Cloud Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-network-wired"></i></span>Free Supersonic CDN</li>
							<li><span class="me-2"><i class="fa-solid fa-window-maximize"></i></span>24 Hours Website Migration</li>
							<li><span class="me-2"><i class="fa-solid fa-lock"></i></span>Automatic SSL installation</li>
						</ul>
						<button class="expand-btn mt-4"><i class="fa-solid fa-angle-down"></i>Expand Feature</button>
						<a href="/" class="template-btn primary-btn w-100 mt-40 text-center">Purchase Plan</a>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow">
						<h3 class="h5">Manage <br>Dedicated Server</h3>
						<span class="pricing-badge position-absolute rounded"><span class="gradient-txt">Save 60%</span></span>
						<span class="pricing-label d-block mt-4">Form only</span>
						<h4 class="h2 mt-2 monthly-price">$7.25<span>/mo</span></h4>
						<h4 class="h2 mt-2 yearly-price">$46<span>/yr</span></h4>
						<p class="mt-4">Packed with great features, such as oneclick software installs,24/7 support</p>
						<ul class="feature-list mt-4">
							<li><span class="me-2"><i class="fa-solid fa-rocket"></i></span>10 GB SSD Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-database"></i></span>10 MySQL Database</li>
							<li><span class="me-2"><i class="fa-solid fa-globe"></i></span>Unlimited Website</li>
							<li><span class="me-2"><i class="fa-solid fa-gears"></i></span>cPanel Control Panel</li>
							<li><span class="me-2"><i class="fa-solid fa-briefcase"></i></span>Auto Backup & Cloud Storage</li>
							<li><span class="me-2"><i class="fa-solid fa-network-wired"></i></span>Free Supersonic CDN</li>
							<li><span class="me-2"><i class="fa-solid fa-window-maximize"></i></span>24 Hours Website Migration</li>
							<li><span class="me-2"><i class="fa-solid fa-lock"></i></span>Automatic SSL installation</li>
						</ul>
						<button class="expand-btn mt-4"><i class="fa-solid fa-angle-down"></i>Expand Feature</button>
						<a href="/" class="template-btn secondary-btn w-100 mt-40 text-center">Purchase Plan</a>
					</div>
				</div>
			</div>
		</div>
		<div class="money-back-area text-center bg-white rounded-10 mt-4 position-relative zindex-1 overflow-hidden">
			<img src={mbCircleLeft} class="position-absolute left-top" alt="circle">
			<img src={mbCircleRight} class="position-absolute right-bottom" alt="circle">
			<h3>30 day Money-back Guarantee.</h3>
			<p>Packed with great features, such as one-click software installs,24/7 support .</p>
			<ul class="money-back_ft-list d-flex align-items-center justify-content-start justify-content-md-center mt-30">
				<li><i class="fa-solid fa-down-left-and-up-right-to-center"></i><span class="ms-2">Easily Upgrade or Downgrade</span></li>
				<li><i class="fa-solid fa-calendar-check"></i><span class="ms-2">2 months free if paid yearly</span></li>
				<li><i class="fa-solid fa-clock-rotate-left"></i><span class="ms-2">Instant prorated refund</span></li>
			</ul>
		</div>
	</div>
</section>
<!--pricing section end-->

<!--migrate hosting start-->
<section class="migrate-hosting bg-primary-gradient position-relative zindex-1">
	<img src={migrateShape1} alt="circle" class="position-absolute left-bottom soft-light">
	<img src={plusRound} alt="plus" class="position-absolute rounded-plus">
	<img src={migrateFrame} alt="frame" class="position-absolute migrate-frame">
	<img src={lineWave} alt="frame" class="position-absolute line-wave soft-light">
	<div class="container">
		<div class="row justify-content-between align-items-center">
			<div class="col-xl-5 col-lg-6 order-2 order-lg-1">
				<div class="migrate-content">
					<h2 class="mb-4">Migrating from another web hosting?</h2>
					<p class="mb-50">Compare our plans and find the right solution for your company. Or get in touch for a custom solution. Whatever you need, we can tailor your infrastructure and service based on your needs.</p>
					<div class="migrate-btns">
						<a href="/" class="template-btn primary-btn me-4">Book a Demo</a>
						<a href="/contact" class="template-btn outline-btn">Contact Us</a>
					</div>
				</div>
			</div>
			<div class="col-lg-5 order-1 order-lg-2">
				<div class="migrate-feature-img mb-5 mb-lg-0">
					<img src={migrate} alt="migrate" class="img-fluid">
				</div>
			</div>
		</div>
	</div>
</section>
<!--migrate hosting end-->

<!--feature section start-->
<section class="feature-area pt-120 pb-80" data-background={bgShape1}>
	<div class="container">
		<div class="row justify-content-between">
			<div class="col-lg-5">
				<div class="feature-left">
					<h2>World Class Best Hosting <br>Feature For You.</h2>
					<img src={featureImg} alt="feature image" class="img-fluid" />
				</div>
			</div>
			<div class="col-lg-6">
				<div class="feature-right">
					<div class="feature-item d-flex align-items-center bg-white rounded-2 deep-shadow">
						<div class="promo-top flex-shrink-0">
							<img src={cpanel} alt="capnel" class="img-fluid">
						</div>
						<div class="promo-right ms-4">
							<h4>cPanel Control Panel</h4>
							<p class="mb-0">We strive to provide top rare reliability and affordability that most shared hosting will bring quality.</p>
						</div>
					</div>
					<div class="feature-item d-flex align-items-center bg-white rounded-2 deep-shadow">
						<div class="promo-top flex-shrink-0">
							<img src={backup} alt="backup" class="img-fluid">
						</div>
						<div class="promo-right ms-4">
							<h4>Daily Offsite Backups</h4>
							<p class="mb-0">We strive to provide top rare reliability and affordability that most shared hosting will bring quality.</p>
						</div>
					</div>
					<div class="feature-item d-flex align-items-center bg-white rounded-2 deep-shadow">
						<div class="promo-top flex-shrink-0">
							<img src={technology} alt="technology" class="img-fluid">
						</div>
						<div class="promo-right ms-4">
							<h4>Latest Technology</h4>
							<p class="mb-0">We strive to provide top rare reliability and affordability that most shared hosting will bring quality.</p>
						</div>
					</div>
					<div class="feature-bottom mt-5">
						<img src={arrow} class="img-fluid" alt="arrow">
						<a href="/" class="template-btn primary-btn ms-3">More Featured</a>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--feature section end-->

<!--consult section start-->
<section class="consult-area position-relative zindex-1 overflow-hidden" data-background={consultBg}>
	<img src={sectionCurve} alt="curve" class="position-absolute curve w-100">
	<div class="consult-overlay bg-secondary-gradient pt-120">
		<div class="container">
			<div class="row justify-content-between">
				<div class="col-lg-7 col-xl-6">
					<div class="consult-left">
						<h2>Reason For Choosing Our Strike Hosting Consultancy.</h2>
						<ul class="consult-list mt-5">
							<li class="d-flex">
								<span class="icon-box position-relative d-inline-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-check"></i></span>
								<div class="list-content ms-4">
									<h4 class="mb-3 mt-1">15+ Years Web Hosting Company</h4>
									<p>Traditional WordPress, you get all the features, tools, and guidance you need to build and launch.</p>
								</div>
							</li>
							<li class="d-flex">
								<span class="icon-box position-relative d-inline-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-check"></i></span>
								<div class="list-content ms-4">
									<h4 class="mb-3 mt-1">Safe and Secured</h4>
									<p>Worried you won't get help when you most need it? You shouldn't be. Our professional and hands-on support</p>
								</div>
							</li>
							<li class="d-flex">
								<span class="icon-box position-relative d-inline-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-check"></i></span>
								<div class="list-content ms-4">
									<h4 class="mb-3 mt-1">24/7 Technical Support</h4>
									<p>Don't just take our word for it. We're the web hosting provider of choice for thousands of happy customers.</p>
								</div>
							</li>
						</ul>
					</div>
				</div>
				<div class="col-lg-5 align-self-end">
					<div class="consult-right">
						<img src={consultMan} alt="man" class="img-fluid">
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--consult section end-->

<!--domain search-->
<section class="domain-area light-bg">
	<div class="container">
		<div class="row">
			<div class="col-lg-12">
				<div class="domain-search-box bg-white position-relative zindex-2 primary-shadow rounded-10">
					<div class="row justify-content-center">
						<div class="col-xl-7 col-lg-10">
							<h2 class="h3 text-center">Looking for a Perfect Domain Name?</h2>
							<form action="/" class="mt-4 domain-search-form position-relative d-flex align-items-center justify-content-between">
								<input type="text" placeholder="Search Domain Name">
								<select class="form-select flex-shrink-0">
									<option value="1">.com</option>
									<option value="1">.info</option>
									<option value="1">.org</option>
									<option value="1">.biz</option>
									<option value="1">.xyz</option>
								</select>
								<button type="submit" class="template-btn primary-btn btn-small flex-shrink-0 border-0">Search Now</button>
							</form>
							<div class="domain-info mt-4 d-flex justify-content-center align-items-center">
								<div class="info-box rounded-3 text-center">
									<h5 class="primary-text mb-0">.com</h5>
									<span>$2.44/Year</span>
								</div>
								<div class="info-box rounded-3 text-center">
									<h5 class="danger-text mb-0">.info</h5>
									<span>$3.44/Year</span>
								</div>
								<div class="info-box rounded-3 text-center">
									<h5 class="success-text mb-0">.org</h5>
									<span>$2.55/Year</span>
								</div>
								<div class="info-box rounded-3 text-center">
									<h5 class="blue-text mb-0">.biz</h5>
									<span>$1.90/Year</span>
								</div>
								<div class="info-box rounded-3 text-center">
									<h5 class="info-text mb-0">.xyz</h5>
									<span>$0.99/Year</span>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--domain search end-->

<!--services section start-->
<section class="service-section light-bg pt-120 pb-120 overflow-hidden position-relative zindex-1">
	<img src={serviceShape} alt="not found" class="position-absolute right-bottom">
	<div class="container">
		<div class="row justify-content-between align-items-center">
			<div class="col-xl-5 col-lg-6">
				<div class="section-title text-center text-lg-start">
					<h2>We Provide you World Hosting Services.</h2>
				</div>
			</div>
			<div class="col-lg-3">
				<div class="explore-btn text-center text-lg-end mt-3 mt-lg-0">
					<a href="/" class="template-btn primary-btn">All Service
						<span>
						  <svg width="13" height="8" viewBox="0 0 13 8" fill="none" xmlns="http://www.w3.org/2000/svg">
							  <path fill-rule="evenodd" clip-rule="evenodd" d="M8.24451 0.234639C8.39471 0.0844779 8.59841 0.00012207 8.8108 0.00012207C9.02319 0.00012207 9.22689 0.0844779 9.3771 0.234639L12.581 3.43857C12.7312 3.58877 12.8155 3.79247 12.8155 4.00486C12.8155 4.21725 12.7312 4.42095 12.581 4.57116L9.3771 7.77508C9.22603 7.92099 9.0237 8.00172 8.81368 7.9999C8.60367 7.99807 8.40277 7.91383 8.25426 7.76533C8.10576 7.61682 8.02152 7.41592 8.01969 7.20591C8.01787 6.99589 8.0986 6.79356 8.24451 6.64249L10.0812 4.80584H0.800982C0.588548 4.80584 0.384815 4.72145 0.234602 4.57124C0.0843889 4.42103 0 4.21729 0 4.00486C0 3.79243 0.0843889 3.58869 0.234602 3.43848C0.384815 3.28827 0.588548 3.20388 0.800982 3.20388H10.0812L8.24451 1.36723C8.09435 1.21702 8.00999 1.01332 8.00999 0.800933C8.00999 0.588541 8.09435 0.384845 8.24451 0.234639Z" fill="white"/>
						  </svg>
					  </span>
					</a>
				</div>
			</div>
		</div>
		<div class="services-bottom mt-40">
			<div class="row g-4 justify-content-center">
				<div class="col-lg-4 col-md-6">
					<div class="service-card bg-white deep-shadow rounded-2">
						<div class="icon-wrapper">
							<img src={wpHosting} alt="hosting" class="img-fluid">
						</div>
						<div class="card-content">
							<a href="/vps-hosting">
								<h3 class="h4 mb-4">WordPress Hosting</h3>
							</a>
							<p class="mb-4">Seamlessly transform dynamic testing my procedures rather than distributed process Compellingly myocardinate cost.</p>
							<a href="/vps-hosting">Starting at:$1.99/mo<i class="fa-solid fa-arrow-right"></i></a>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="service-card bg-white deep-shadow rounded-2">
						<div class="icon-wrapper">
							<img src={sharedHosting} alt="hosting" class="img-fluid">
						</div>
						<div class="card-content">
							<a href="/shared-hosting">
								<h3 class="h4 mb-4">Shared Hosting</h3>
							</a>
							<p class="mb-4">Collaboratively harness timely collaboration and idea-sharing after collaborative services. maximizing Best service.</p>
							<a href="/shared-hosting">Starting at:$1.99/mo<i class="fa-solid fa-arrow-right"></i></a>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="service-card bg-white deep-shadow rounded-2">
						<div class="icon-wrapper">
							<img src={vpsHosting} alt="hosting" class="img-fluid">
						</div>
						<div class="card-content">
							<a href="/vps-hosting">
								<h3 class="h4 mb-4">VPS Hosting</h3>
							</a>
							<p class="mb-4">Seamlessly transform dynamic testing my procedures rather than distributed process Compellingly myocardinate cost.</p>
							<a href="/vps-hosting">Starting at:$1.99/mo<i class="fa-solid fa-arrow-right"></i></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="service-rating mt-4">
			<div class="row g-4 justify-content-center">
				<div class="col-lg-4 col-md-6">
					<div class="service-rating-box deep-shadow bg-white rounded-2 d-flex align-items-center justify-content-between">
						<div class="box-left">
							<img src={google} alt="google" class="img-fluid d-block">
							<img src={starYellow} alt="rating" class="img-fluid d-block mt-3">
						</div>
						<div class="box-right position-relative">
							<h5 class="mb-0 h3">4.5/5</h5>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="service-rating-box deep-shadow bg-white rounded-2 d-flex align-items-center justify-content-between">
						<div class="box-left">
							<img src={trustPilotLogoBlack} alt="google" class="img-fluid d-block">
							<img src={fiveStar} alt="rating" class="img-fluid d-block mt-3">
						</div>
						<div class="box-right position-relative">
							<h5 class="mb-0 h3">4.5/5</h5>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="service-rating-box deep-shadow bg-white rounded-2 d-flex align-items-center justify-content-between">
						<div class="box-left">
							<img src={google} alt="google" class="img-fluid d-block">
							<img src={starYellow} alt="rating" class="img-fluid d-block mt-3">
						</div>
						<div class="box-right position-relative">
							<h5 class="mb-0 h3">4.5/5</h5>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--services section end-->

<!--feedback section start-->
<section class="feedback-section bg-primary-gradient pt-120 position-relative overflow-hidden">
	<div class="container">
		<div class="row justify-content-center">
			<div class="col-lg-8">
				<div class="feedbackt-top text-center">
					<h2>Hundreds of five-star Ratings. Every day!</h2>
					<p>We truly cannot say enough about the level of customer service that Kinsta provides - it's always a great experience, with very personable and helpful support.</p>
				</div>
			</div>
		</div>
		<div class="feedback-wrapper mt-30">
			<div class="row g-4 feedback-massonry">
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client1} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Floyd Miles</h5>
								<img src={twoStar} alt="3 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client2} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Herman Parks</h5>
								<img src={threeStar} alt="2 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"We unexpectedly lost login access problem ourselves. and efficiency despite made it difficult to communicate details such as IP addresses.”</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client3} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Darrel Steward</h5>
								<img src={fiveStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data Appropriately target maintainable quality vectors via ethical benefitsIntrinsiclyectors via ethical benefitsIntrinsicly incentivize models before stand-alone technologies top-line data with empo meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client4} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Albert Flores</h5>
								<img src={twoStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client5} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Leslie Alexander</h5>
								<img src={threeStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client6} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Herman Parks</h5>
								<img src={twoStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client1} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Albert Flores</h5>
								<img src={fiveStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="feedback-single bg-white rounded-2 position-relative">
						<img src={quoteIcon} alt="quote" class="position-absolute quote-icon">
						<div class="feedback-top d-flex align-items-center">
							<img src={client7} alt="client" class="img-fluid rounded-circle flex-shrink-0">
							<div class="feedback-top-content ms-3">
								<h5>Herman Parks</h5>
								<img src={threeStar} alt="1 star" class="img-fluid">
							</div>
						</div>
						<p class="feedback-comment mt-30 mb-30">"Appropriately target maintainable quality vectors via ethical benefits. Globally empowered meta-services. Authoritatively web-enabled functionalities and emerging results. Intrinsicly incentivize models before stand-alone technologies top-line data with empowered meservices."</p>
						<img src={stamps} alt="not found" class="img-fluid">
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="explore-btn position-absolute">
		<a href="/testimonials" class="template-btn hm2-primary-btn">More Feedback</a>
	</div>
</section>
<!--feedback section end-->

<!--blog section start-->
<section class="blog-section light-bg pt-120 pb-120 overflow-hidden">
	<div class="container">
		<div class="row align-items-center justify-content-center">
			<div class="col-xxl-5 col-xl-6 col-lg-9">
				<div class="section-title text-center text-xl-start">
					<h2>Our Latest News & Blogs</h2>
					<p>We are committed to offering customers the most professional and reliable web on UK-based servers, at prices.</p>
				</div>
			</div>
			<div class="col-xxl-7 col-xl-6">
				<div class="explore-btn text-center text-xl-end mt-3 mt-xl-0">
					<a href="/" class="template-btn secondary-btn">See All Stories</a>
				</div>
			</div>
		</div>
		<div class="blog-bottom mt-5 position-relative zindex-1">
			<img src={circleWithFrame} alt="frame" class="position-absolute circle-frame">
			<img src={circleBlue} alt="frame" class="position-absolute circle-blue">
			<div class="row g-4 justify-content-center">
				<div class="col-xl-6 col-lg-10">
					<div class="blog-card bg-white deep-shadow rounded">
						<div class="feature-thumb rounded-2 overflow-hidden position-relative">
							<a href="/"><img src={blog1} alt="feature" class="img-fluid"></a>
							<span class="position-absolute category-btn">Shared Hosting</span>
						</div>
						<div class="blog-content-wrapper mt-4">
							<a href="/">
								<h3>WordPress security in 2020 - what we do to protect our users</h3>
							</a>
							<p class="mt-3">Enthusiastically negotiate sticky intellectual capital through integrated Professionally tactical alignments. </p>
							<div class="blog-author mt-4 d-flex align-items-start align-items-sm-center justify-content-between">
								<div class="author-left d-flex align-items-center">
									<img src={author1} alt="author" class="img-fluid rounded-circle flex-shrink-0">
									<div class="author-info ms-3">
										<h6 class="mb-0">Raymond Harris</h6>
										<span>03 May 2022</span>
									</div>
								</div>
								<div class="blog-meta">
									<a href="/"><i class="fa-solid fa-heart"></i>4.6k likes</a>
									<a href="/"><i class="fa-solid fa-comment"></i>19 comments</a>
								</div>
							</div>
						</div>
					</div>
				</div>
				<div class="col-xl-6 col-lg-10">
					<div class="row g-4">
						<div class="col-xl-12">
							<div class="blog-card d-flex align-items-center bg-white deep-shadow p-25 rounded-2">
								<div class="feature-thumb position-relative">
									<a href="/"><img src={blog2} alt="feature" class="img-fluid rounded-left"></a>
									<span class="position-absolute category-btn">technology</span>
								</div>
								<div class="blog-content ms-0 ms-sm-4 mt-3 mt-sm-0">
									<a href="/">
										<h4>WordPress 6.0 release candidate why you should test it</h4>
									</a>
									<div class="blog-author mt-4 d-flex align-items-start align-items-sm-center justify-content-between">
										<div class="author-left d-flex align-items-center">
											<img src={author2} alt="author" class="img-fluid rounded-circle flex-shrink-0">
											<div class="author-info ms-3">
												<h6 class="mb-0">Mark Vasquez</h6>
												<span>03 May 2022</span>
											</div>
										</div>
										<div class="blog-meta">
											<a href="/"><i class="fa-solid fa-heart"></i>4.6k likes</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="col-xl-12">
							<div class="blog-card d-flex align-items-center bg-white deep-shadow p-25 rounded-2">
								<div class="feature-thumb position-relative">
									<a href="/"><img src={blog3} alt="feature" class="img-fluid rounded-left"></a>
									<span class="position-absolute category-btn">technology</span>
								</div>
								<div class="blog-content ms-0 ms-sm-4 mt-3 mt-sm-0">
									<a href="/">
										<h4>WordPress 6.0 release candidate why you should test it</h4>
									</a>
									<div class="blog-author mt-4 d-flex align-items-start align-items-sm-center justify-content-between">
										<div class="author-left d-flex align-items-center">
											<img src={author3} alt="author" class="img-fluid rounded-circle flex-shrink-0">
											<div class="author-info ms-3">
												<h6 class="mb-0">Francisco Murphy</h6>
												<span>03 May 2022</span>
											</div>
										</div>
										<div class="blog-meta">
											<a href="/"><i class="fa-solid fa-heart"></i>4.6k likes</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="col-xl-12">
							<div class="blog-card d-flex align-items-center bg-white deep-shadow p-25 rounded-2">
								<div class="feature-thumb position-relative">
									<a href="/"><img src={blog4} alt="feature" class="img-fluid rounded-left"></a>
									<span class="position-absolute category-btn">Technology</span>
								</div>
								<div class="blog-content ms-0 ms-sm-4 mt-3 mt-sm-0">
									<a href="/">
										<h4>WordPress 6.0 release candidate why you should test it</h4>
									</a>
									<div class="blog-author mt-4 d-flex align-items-start align-items-sm-center justify-content-between">
										<div class="author-left d-flex align-items-center">
											<img src={author4} alt="author" class="img-fluid rounded-circle flex-shrink-0">
											<div class="author-info ms-3">
												<h6 class="mb-0">Victor Sheridan</h6>
												<span>03 May 2022</span>
											</div>
										</div>
										<div class="blog-meta">
											<a href="/"><i class="fa-solid fa-heart"></i>4.6k likes</a>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--blog section end-->

<!--applications area start-->
<section class="application-area light-bg pb-120 position-relative zindex-1 overflow-hidden">
	<img src={boxShape} alt="box-shape" class="position-absolute left-bottom">
	<div class="container">
		<div class="row justify-content-center">
			<div class="col-lg-7">
				<div class="section-title text-center">
					<h2>Integrated with more than 100+ applications you love.</h2>
				</div>
			</div>
		</div>
		<div class="app_lists mt-5">
			<div class="row g-4 justify-content-center">
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={joomula} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Joomla Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={app2} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Drupal Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={osticker} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Osticker Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={zendcard} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Zencart Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={mobile} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Mobile Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={wordpress} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">WordPress Hosting</h3>
					</div>
				</div>
				<div class="col-xl-3 col-lg-4 col-md-6 col-sm-10">
					<div class="app_list_item bg-white deep-shadow rounded-2 d-flex align-items-center">
						<img src={app3} alt="joomla" class="img-fluid flex-shrink-0 rounded-circle">
						<h3 class="h6 ms-3 mb-0">Joomla Hosting</h3>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style>

</style>
