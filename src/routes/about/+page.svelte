<script>
	import featureRight from '../../assets/img/home2/shape/feature-right.png';
	import featureTriangle from '../../assets/img/home2/shape/feature-triangle.svg';
	import award1 from '../../assets/img/home2/award-1.png';
	import award2 from '../../assets/img/home2/award-2.png';
	import award3 from '../../assets/img/home2/award-3.png';
	import award4 from '../../assets/img/home2/award-4.png';
	import serviceLeftCircle from '../../assets/img/home2/shape/service-left-circle.svg';
	import serviceLeft from '../../assets/img/home2/service-left.png';
	import serviceRightBottom from "../../assets/img/home2/shape/service-right-bottom.svg"
	import serverBg from '../../assets/img/shapes/server-bg.png';
	import arrow from '../../assets/img/shapes/arrow.png';
	import serverLineShape from '../../assets/img/shapes/server-line-shape.png';
	import server from '../../assets/img/home2/server.jpg';
	import server2 from '../../assets/img/home2/server-2.jpg';
	import server3 from '../../assets/img/home2/server-3.jpg';
	import server4 from '../../assets/img/home2/server-4.jpg';
	import agent from '../../assets/img/home2/agent.png';
</script>
<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<!--breadcrumb area start-->
<section class="breadcrumb-area bg-primary-gradient">
	<div class="container">
		<div class="breadcrumb-content text-center">
			<h2 class="mb-3">About</h2>
			<nav>
				<ol class="breadcrumb">
					<li class="breadcrumb-item"><a href="/">Home</a></li>
					<li class="breadcrumb-item"><a href="/about">Pages</a></li>
					<li class="breadcrumb-item active">About Us</li>
				</ol>
			</nav>
		</div>
	</div>
</section>
<!--breadcrumb area end-->

<!--about section start-->
<section class="hm2-feature-area pt-120 pb-120 position-relative zindex-1 overflow-hidden">
	<img src={featureRight} alt="triangle" class="position-absolute right-bottom">
	<div class="container position-relative">
		<div class="row justify-content-between">
			<div class="col-lg-6">
				<div class="hm2-section-title">
					<h2 class="hm2-title"><mark>Discover</mark> all Our <br>Web Hosting Features</h2>
				</div>
			</div>
			<div class="col-lg-5">
				<div class="hm2-section-desc mt-3 mt-lg-0">
					<p>Focus on your business and avoid all the web hosting hassles. Our managed hosting guarantees unmatched performance, reliability and choice with 24/7 support that acts as your extended team,</p>
					<a href="/about" class="hm2-explore-btn fw-bold position-relative">Show all Feature</a>
				</div>
			</div>
		</div>
		<div class="row g-4 mt-5 justify-content-center">
			<div class="col-xl-3 col-lg-4 col-md-6">
				<div class="hm2-feature-card deep-shadow bg-white rounded-2">
					<span class="icon-wrapper d-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-lock"></i></span>
					<h3 class="h4 mt-4">Maximum <br> Security</h3>
					<p class="mt-3">Choice for growing agencies and support that acts asyour ecommerce businesses.</p>
					<a href="/" class="mt-2 d-inline-block rounded-circle text-center position-relative overflow-hidden"><i class="fa-solid fa-arrow-right"></i></a>
				</div>
			</div>
			<div class="col-xl-3 col-lg-4 col-md-6">
				<div class="hm2-feature-card deep-shadow bg-white rounded-2">
					<span class="icon-wrapper d-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-money-check"></i></span>
					<h3 class="h4 mt-4">100% Moneyback <br>Guarantee</h3>
					<p class="mt-3">Choice for growing agencies and support that acts asyour ecommerce businesses.</p>
					<a href="/" class="mt-2 d-inline-block rounded-circle text-center position-relative overflow-hidden"><i class="fa-solid fa-arrow-right"></i></a>
				</div>
			</div>
			<div class="col-xl-3 col-lg-4 col-md-6">
				<div class="hm2-feature-card deep-shadow bg-white rounded-2">
					<span class="icon-wrapper d-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-gauge-simple-high"></i></span>
					<h3 class="h4 mt-4">Maximum <br>Performance</h3>
					<p class="mt-3">Choice for growing agencies and support that acts asyour ecommerce businesses.</p>
					<a href="/" class="mt-2 d-inline-block rounded-circle text-center position-relative overflow-hidden"><i class="fa-solid fa-arrow-right"></i></a>
				</div>
			</div>
			<div class="col-xl-3 col-lg-4 col-md-6">
				<div class="hm2-feature-card deep-shadow bg-white rounded-2">
					<span class="icon-wrapper d-flex align-items-center justify-content-center rounded-circle"><i class="fa-solid fa-cloud-arrow-down"></i></span>
					<h3 class="h4 mt-4">Maximum <br>Data Transfer</h3>
					<p class="mt-3">Choice for growing agencies and support that acts asyour ecommerce businesses.</p>
					<a href="/" class="mt-2 d-inline-block rounded-circle text-center position-relative overflow-hidden"><i class="fa-solid fa-arrow-right"></i></a>
				</div>
			</div>
		</div>
		<img src={featureTriangle} alt="triangle" class="position-absolute ft-triangle">
	</div>
	<div class="container mt-80">
		<div class="row justify-content-center">
			<div class="col-lg-6">
				<div class="hm2-award-title text-center">
					<h2 class="position-relative">Hostim Best Award</h2>
					<p>Our managed hosting guarantees unmatched performance, reliability and choice with 24/7 support that acts</p>
				</div>
			</div>
		</div>
		<div class="award-wrapper mt-20 d-flex align-items-center justify-content-center">
			<div class="item-wrapper">
				<img src={award1} alt="award" class="img-fluid">
			</div>
			<div class="item-wrapper">
				<img src={award2} alt="award" class="img-fluid">
			</div>
			<div class="item-wrapper">
				<img src={award3} alt="award" class="img-fluid">
			</div>
			<div class="item-wrapper">
				<img src={award4} alt="award" class="img-fluid">
			</div>
		</div>
	</div>
</section>
<!--about section end-->

<!--service section start-->
<section class="hm2-service-section pt-80 pb-80 overflow-hidden position-relative zindex-1 bg-primary-gradient">
	<img src={serviceLeftCircle} alt="circle" class="position-absolute left-top opacity-25">
	<div class="container">
		<div class="row g-5 align-items-center">
			<div class="col-lg-6">
				<div class="service-left">
					<img src={serviceLeft} alt="server" class="img-fluid">
				</div>
			</div>
			<div class="col-lg-6">
				<div class="service-right">
					<h2 class="hm2-title">We're Provide Web Hosting Solutions Agency.</h2>
					<p class="mt-3">Focus on your business and avoid all the web hosting managed hosting guarantees unmatched performance, reliability and choice with 24/7 support that acts as your extended team guarantees unmatched performance.</p>
					<div class="hm2-service-tab mt-30 mb-40">
						<ul class="nav nav-tabs">
							<li><button class="active" data-bs-toggle="tab" data-bs-target="/domain_service" type="button"><i class="fa-solid fa-globe"></i>Domain Services</button></li>
							<li><button data-bs-toggle="tab" data-bs-target="/hosting_service" type="button"><i class="fa-solid fa-earth-asia"></i>Web Hosting Services</button></li>
						</ul>
						<div class="tab-content mt-4">
							<div class="tab-pane fade show active" id="domain_service">
								<p>Focus on your business and avoid all the web hosting hassles. Our managed hosting guarantees unmatched performance, reliability and agencies hosting guarantees unmatched and e-commerce businesses all the web hosting hassles.</p>
							</div>
							<div class="tab-pane fade" id="hosting_service">
								<p>Focus on your business and avoid all the web hosting hassles. Our managed hosting guarantees unmatched performance, reliability and agencies hosting guarantees unmatched and e-commerce businesses all the web hosting hassles.</p>
							</div>
						</div>
					</div>
					<a href="/about" class="template-btn hm2-primary-btn rounded-pill">Explore More</a>
				</div>
			</div>
		</div>
	</div>
	<img src={serviceRightBottom} alt="wave" class="position-absolute right-bottom">
</section>
<!--service section end-->

<!--hosting server-->
<section class="hosting-server ptb-120 position-relative overflow-hidden light-bg zindex-1">
	<img src={serverBg} alt="server-bg" class="position-absolute right-top">
	<img src={serverLineShape} alt="line shape" class="position-absolute left-bottom">
	<div class="container">
		<div class="row justify-content-center">
			<div class="col-lg-5">
				<div class="section-title text-center">
					<h2>The Latest Web Hosting Server Service</h2>
				</div>
			</div>
		</div>
		<div class="server-tab mt-50">
			<div class="row">
				<div class="col-lg-4">
					<div class="tab-left">
						<ul class="hm2-server-tab-control nav nav-tabs border-0">
							<li><button class="active" data-bs-toggle="tab" data-bs-target="/wp-hosting"><i class="fa-brands fa-wordpress"></i><span class="ms-3">WordPress Hosting</span></button></li>
							<li><button data-bs-toggle="tab" data-bs-target="/shared-hosting"><i class="fa-solid fa-server"></i><span class="ms-3">Shared Hosting</span></button></li>
							<li><button data-bs-toggle="tab" data-bs-target="/database"><i class="fa-solid fa-database"></i><span class="ms-3">Game Server</span></button></li>
							<li><button data-bs-toggle="tab" data-bs-target="/cloud-hosting"><i class="fa-solid fa-cloud-meatball"></i><span class="ms-3">VPS  Hosting</span></button></li>
						</ul>
						<div class="explore-btn mt-30 d-none d-lg-block">
							<span class="icon-wrapper me-3"><img src={arrow} alt="arrow" class="img-fluid"></span>
							<a href="/about" class="template-btn secondary-btn rounded-pill">More Services</a>
						</div>
					</div>
				</div>
				<div class="col-lg-8">
					<div class="tab-content mt-5 mt-lg-0">
						<div class="tab-pane fade show active" id="wp-hosting">
							<div class="hm2-server-content">
								<img src={server} alt="server" class="img-fluid rounded-2">
								<div class="server-info rounded-2 bg-white deep-shadow position-relative">
									<h3>Best WordPress Hosting at <br class="d-none d-sm-block">Affordable Price.</h3>
									<p class="mb-0 mt-3">Hostim is a WordPress Hosting, whether you use the Website Builder or build and launch truly impressive WordPress websites.</p>
									<a href="/about" class="explore-btn position-absolute rounded-circle text-center text-white"><i class="fa-solid fa-plus"></i></a>
								</div>
							</div>
						</div>
						<div class="tab-pane fade" id="shared-hosting">
							<div class="hm2-server-content">
								<img src={server2} alt="server" class="img-fluid rounded-2">
								<div class="server-info rounded-2 bg-white deep-shadow position-relative">
									<h3>Best Shared Hosting at <br class="d-none d-sm-block">Affordable Price.</h3>
									<p class="mb-0 mt-3">Hostim is a Shared Hosting, whether you use the Website Builder or build and launch truly impressive WordPress websites.</p>
									<a href="/shared-hosting" class="explore-btn position-absolute rounded-circle text-center text-white"><i class="fa-solid fa-plus"></i></a>
								</div>
							</div>
						</div>
						<div class="tab-pane fade" id="database">
							<div class="hm2-server-content">
								<img src={server3} alt="server" class="img-fluid rounded-2">
								<div class="server-info rounded-2 bg-white deep-shadow position-relative">
									<h3>Best Game Server at <br class="d-none d-sm-block">Affordable Price.</h3>
									<p class="mb-0 mt-3">Hostim is a Game Sever, whether you use the Website Builder or build and launch truly impressive WordPress websites.</p>
									<a href="/" class="explore-btn position-absolute rounded-circle text-center text-white"><i class="fa-solid fa-plus"></i></a>
								</div>
							</div>
						</div>
						<div class="tab-pane fade" id="cloud-hosting">
							<div class="hm2-server-content">
								<img src={server4} alt="server" class="img-fluid rounded-2">
								<div class="server-info rounded-2 bg-white deep-shadow position-relative">
									<h3>Best Dedicated Hosting at <br class="d-none d-sm-block">Affordable Price.</h3>
									<p class="mb-0 mt-3">Hostim is a Shared Hosting, whether you use the Website Builder or build and launch truly impressive WordPress websites.</p>
									<a href="/vps-hosting" class="explore-btn position-absolute rounded-circle text-center text-white"><i class="fa-solid fa-plus"></i></a>
								</div>
							</div>
						</div>
					</div>
					<div class="explore-btn mt-50 d-block d-lg-none">
						<span class="icon-wrapper me-3"><img src={arrow} alt="arrow" class="img-fluid"></span>
						<a href="/about" class="template-btn secondary-btn rounded-pill">More Services</a>
					</div>
				</div>
			</div>
		</div>
		<div class="question-box bg-white deep-shadow rounded-2 mt-100">
			<div class="row align-items-center">
				<div class="col-lg-6 order-2 order-lg-1">
					<div class="question-box-content">
						<h3 class="h2">Questions about Hosting</h3>
						<p>Contact one of our technical experts now. Our team is available chat and is ready to answer any questions you may have.</p>
						<span class="phone fw-bold d-block mb-30">+90 178 985 478</span>
						<a href="mailto:someone@example.com" class="template-btn primary-btn btn-small"><i class="fa-solid fa-comments"></i>Live Chat With Experts</a>
					</div>
				</div>
				<div class="col-lg-6 order-1 order-lg-2">
					<div class="agent-thumb mb-4 mb-lg-0">
						<img src={agent} alt="agent" class="img-fluid">
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
<!--hosting server end-->
