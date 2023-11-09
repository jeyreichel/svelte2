<script>
	import { page } from '$app/stores';
	import logo from '../assets/img/logo.png';
	import logoWhite from '../assets/img/logo-white.png';
</script>

<header class="header-section header-gradient">
	<div class="topbar">
		<div class="container">
			<div class="row align-item-center">
				<div class="col-md-6">
					<div class="topbar-left">
						<p class="mb-0">Get 50% Discount Offer <mark>26 Days</mark></p>
					</div>
				</div>
				<div class="col-md-6">
					<div class="topbar-right text-end">
						<a href="/">Login</a>
						<a href="/">Sign up</a>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="header-nav">
		<div class="container">
			<div class="nav-menu bg-white">
				<div class="row align-items-center">
					<div class="col-lg-2 col-6">
						<div class="logo-wrapper">
							<a href="/" class="logo-black"><img src={logo} alt="logo" class="logo"></a>
							<a href="/" class="logo-white"><img src={logoWhite} alt="logo" class="logo"></a>
						</div>
					</div>
					<div class="col-xl-8 col-lg-7 d-none d-lg-block">
						<div class="nav-wrapper">
							<nav>
								<ul>
									<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
										<a href="/">Home</a>
									</li>
									<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
										<a href="/about">About</a>
									</li>
									<li class="has-submenu">
										<a href="/">Hosting</a>
										<div class="submenu-wrapper menu-list theme-megamenu">
											<div class="row">
												<div class="col-md-6">
													<div class="megamenu-item" aria-current={$page.url.pathname === '/shared-hosting' ? 'page' : undefined}>
														<a href="/shared-hosting">
															<div class="menu-list-wrapper d-flex align-items-center">
																<span class="icon-wrapper"><i class="fa-solid fa-server"></i></span>
																<div class="menu-list-content-right ms-3">
																	<h6>Shared Hosting</h6>
																	<span>Powerful bare metal server</span>
																</div>
															</div>
														</a>
													</div>
													<div class="megamenu-item" aria-current={$page.url.pathname === '/vps-hosting' ? 'page' : undefined}>
														<a href="/vps-hosting">
															<div class="menu-list-wrapper d-flex align-items-center">
																<span class="icon-wrapper"><i class="fa-solid fa-cloud"></i></span>
																<div class="menu-list-content-right ms-3">
																	<h6>VPS Hosting</h6>
																	<span>Powerful bare metal server</span>
																</div>
															</div>
														</a>
													</div>
												</div>
												<div class="col-md-6">
													<div class="megamenu-item" aria-current={$page.url.pathname === '/dedicated-server' ? 'page' : undefined}>
														<a href="/dedicated-server">
															<div class="menu-list-wrapper d-flex align-items-center">
																<span class="icon-wrapper"><i class="fa-solid fa-shield"></i></span>
																<div class="menu-list-content-right ms-3">
																	<h6>Dedicated Server</h6>
																	<span>Powerful dedicated server</span>
																</div>
															</div>
														</a>
													</div>
													<div class="megamenu-item" aria-current={$page.url.pathname === '/reseller-hosting' ? 'page' : undefined}>
														<a href="/reseller-hosting">
															<div class="menu-list-wrapper d-flex align-items-center">
																<span class="icon-wrapper"><i class="fa-brands fa-audible"></i></span>
																<div class="menu-list-content-right ms-3">
																	<h6>Reseller Hosting</h6>
																	<span>Reseller Hosting server</span>
																</div>
															</div>
														</a>
													</div>
												</div>
											</div>
										</div>
									</li>
									<li aria-current={$page.url.pathname === '/testimonials' ? 'page' : undefined}>
										<a href="/testimonials">Testimonials</a>
									</li>
									<li aria-current={$page.url.pathname === '/contact' ? 'page' : undefined}>
										<a href="/contact">Contact</a>
									</li>
								</ul>
							</nav>
						</div>
					</div>
					<div class="col-xl-2 col-lg-3 col-6">
						<div class="header-right d-flex align-items-center justify-content-end">
							<button class="dark-light-switcher me-2" id="theme-switch">
								<span class="light-sun"><i class="fa-solid fa-sun"></i></span>
								<span class="dark-moon"><i class="fa-solid fa-moon"></i></span>
							</button>
							<div class="lang-switcher d-none d-sm-block dropdown">
								<a href="/" data-bs-toggle="dropdown"><span class="me-1"><i class="fa-solid fa-globe"></i></span>En</a>
								<div class="dropdown-menu dropdown-menu-end">
									<ul>
										<li><a href="/">Dutch</a></li>
										<li><a href="/">Bangla</a></li>
										<li><a href="/">Chinese</a></li>
										<li><a href="/">Italian</a></li>
										<li><a href="/">French</a></li>
										<li><a href="/">German</a></li>
										<li><a href="/">Bangla</a></li>
										<li><a href="/">English</a></li>
										<li><a href="/">Malay</a></li>
										<li><a href="/">Arabic</a></li>
									</ul>
								</div>
							</div>
							<div class="product-cart next">
								<a href="/">
									<svg width="16" height="16" viewBox="0 0 17 21" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M4.07733 4.65414C3.98625 3.23381 4.3886 2.02388 5.4331 1.07162C6.20782 0.364915 7.13126 0.00406905 8.17979 3.40346e-05C9.41854 -0.00457742 10.4636 0.45945 11.2943 1.3777C12.1272 2.29827 12.4269 3.40386 12.3445 4.65356C12.6154 4.65356 12.8644 4.64895 13.1135 4.65472C13.472 4.66279 13.8369 4.63973 14.1879 4.69853C15.1045 4.85243 15.7944 5.61159 15.8509 6.53676C15.9374 7.95767 15.9956 9.37972 16.0636 10.8018C16.1605 12.8268 16.2556 14.8518 16.3507 16.8774C16.3772 17.4377 16.4083 17.9979 16.421 18.5582C16.4493 19.7734 15.5449 20.7054 14.3257 20.7072C10.2486 20.7118 6.17151 20.7118 2.09441 20.7072C0.868914 20.706 -0.0481878 19.7595 0.00196173 18.5352C0.0901557 16.3943 0.199101 14.2546 0.298824 12.1149C0.376642 10.449 0.452155 8.78254 0.532279 7.11665C0.545536 6.83709 0.551877 6.5529 0.608944 6.28141C0.809542 5.32741 1.62634 4.6674 2.59821 4.65645C3.07953 4.64953 3.5597 4.65414 4.07733 4.65414ZM8.19997 19.3272C10.2279 19.3272 12.2557 19.3278 14.2836 19.3266C14.7794 19.326 15.056 19.0367 15.0393 18.5409C15.0318 18.3109 15.0238 18.081 15.0128 17.851C14.9033 15.5314 14.7932 13.2113 14.6837 10.8917C14.6185 9.51288 14.5586 8.13348 14.4871 6.75523C14.4606 6.24221 14.1885 6.00357 13.683 6.00587C12.6402 6.01106 11.5975 6.01567 10.5553 6.01855C7.93769 6.02547 5.32069 6.03123 2.70312 6.03757C2.23217 6.03873 1.96759 6.2791 1.93819 6.75408C1.90303 7.32071 1.88459 7.8885 1.85807 8.45628C1.70128 11.7961 1.54334 15.1354 1.38713 18.4752C1.36003 19.0592 1.61943 19.3266 2.20278 19.3266C4.20126 19.3272 6.2009 19.3272 8.19997 19.3272ZM10.9611 4.64376C11.0608 3.42 10.6936 2.41528 9.62606 1.77717C8.63748 1.18575 7.61604 1.21919 6.66032 1.86421C5.68384 2.5225 5.36104 3.49263 5.46365 4.64376C7.29612 4.64376 9.11822 4.64376 10.9611 4.64376Z" fill="/001042" />
										<path d="M8.217 11.6064C6.28135 11.6052 4.62584 10.3008 4.17334 8.4216C4.10013 8.11782 4.13991 7.8469 4.39411 7.64227C4.61546 7.46357 4.86852 7.44513 5.12503 7.55292C5.37174 7.65668 5.47377 7.8688 5.54006 8.1184C5.83346 9.22226 6.53325 9.92839 7.64922 10.1866C9.06551 10.5146 10.5089 9.63038 10.8859 8.22619C10.9084 8.14318 10.9262 8.05845 10.9533 7.97717C11.0709 7.61748 11.4139 7.42553 11.7886 7.50738C12.1321 7.58232 12.3685 7.92356 12.3027 8.29075C12.2624 8.51498 12.1944 8.73748 12.1125 8.95076C11.4952 10.5653 9.96244 11.6075 8.217 11.6064Z" fill="/001042" />
									</svg>
								</a>
							</div>
							<div class="header-search position-relative dropdown next">
								<button class="border-0" data-bs-toggle="dropdown">
									<svg width="16" height="16" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M0.421875 7.58979C0.421875 7.27212 0.421875 6.95874 0.421875 6.64107C0.451875 6.43501 0.473304 6.22466 0.507589 6.0186C0.794732 4.31433 1.5833 2.8891 2.88188 1.75149C3.82902 0.918674 4.93045 0.382065 6.16473 0.137372C6.46045 0.0772716 6.76473 0.0429287 7.06473 0C7.38188 0 7.69902 0 8.01188 0C8.2133 0.0257572 8.41902 0.0472216 8.61616 0.0815645C10.279 0.360601 11.6976 1.09897 12.8204 2.36537C14.3376 4.06964 14.9162 6.06582 14.5604 8.31958C14.3847 9.43573 13.939 10.4488 13.2619 11.3546C13.2019 11.4319 13.1462 11.5135 13.0519 11.638C13.1162 11.6809 13.1847 11.7109 13.2319 11.7582C14.8176 13.3379 16.399 14.9177 17.9762 16.5061C18.1433 16.6778 18.2676 16.8881 18.4133 17.0856C18.4133 17.1929 18.4133 17.296 18.4133 17.4033C18.3062 17.5578 18.2247 17.7467 18.079 17.8583C17.7704 18.1073 17.3847 18.0343 17.059 17.7081C15.4304 16.0811 13.8019 14.4541 12.1776 12.8271C12.1262 12.7756 12.0962 12.6983 12.0533 12.6339C11.9933 12.6854 11.9804 12.6897 11.9719 12.694C11.9119 12.7369 11.8519 12.7842 11.7876 12.8271C9.71759 14.2995 7.46759 14.6773 5.08473 13.793C2.68902 12.9044 1.20616 11.1572 0.589018 8.68018C0.511875 8.32387 0.481875 7.95469 0.421875 7.58979ZM13.1719 7.13475C13.159 4.04388 10.6862 1.52826 7.57473 1.5068C4.51473 1.48533 1.95616 3.95373 1.92188 7.09611C1.88759 10.1655 4.41188 12.7369 7.53616 12.7412C10.6176 12.7498 13.1376 10.2943 13.1719 7.13475Z" fill="/001042" />
									</svg>
								</button>
								<div class="dropdown-menu dropdown-menu-end bg-transparent border-0">
									<form class="header-search-form" action="/">
										<input type="text" placeholder="Search....">
										<input type="submit" value="Go">
									</form>
								</div>
							</div>
							<div class="ofcanvus-btns next">
								<a href="/" class="ofcanvus-btn d-none d-lg-block"><i class="fa-solid fa-bars-staggered"></i></a>
								<a href="/" class="mobile-menu-toggle d-lg-none"><i class="fa-solid fa-bars-staggered"></i></a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</header>

<style>
</style>
