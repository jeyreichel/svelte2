<script>
    import { page } from '$app/stores';
    import logoWhite from '../assets/img/logo-white.png';
    import visa from '../assets/img/visa.png';
    import mastercard from '../assets/img/mastercard.png';
    import payoneer from '../assets/img/payoneer.png';
    import paypal from '../assets/img/paypal.png';
</script>

<footer class="footer pt-100">
    <div class="footer-top pb-60">
        <div class="container">
            <div class="row">
                <div class="col-lg-4 col-md-6">
                    <div class="footer-widget footer-widget-1">
                        <a href="/" class="footer-logo"><img src={logoWhite} class="logo" alt="logo"></a>
                        <p class="text-white mt-30">My service is not something I even think about because it is always there as we agreed. The customer service is responsive and knowledge needs for</p>
                        <div class="footer-social mt-5">
                            <h5 class="ft-subtitle text-white position-relative d-inline-block">Follow us on</h5>
                            <ul class="social-nav mt-3">
                                <li><a href="/" class="rounded-circle overflow-hidden position-relative d-flex align-items-center justify-content-center text-white"><i class="fab fa-facebook-f"></i></a></li>
                                <li><a href="/" class="rounded-circle overflow-hidden position-relative d-flex align-items-center justify-content-center text-white"><i class="fab fa-twitter"></i></a></li>
                                <li><a href="/" class="rounded-circle overflow-hidden position-relative d-flex align-items-center justify-content-center text-white"><i class="fab fa-instagram"></i></a></li>
                                <li><a href="/" class="rounded-circle overflow-hidden position-relative d-flex align-items-center justify-content-center text-white"><i class="fab fa-linkedin"></i></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-2 col-md-3 col-sm-6">
                    <div class="footer-widget footer-widget-2 mt-2">
                        <h5 class="text-white position-relative mb-5 widget-title">Quick Links</h5>
                        <ul class="footer-nav">
                            <li aria-current={$page.url.pathname === '/contact' ? 'page' : undefined}><a href="/contact">Support Center</a></li>
                            <li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}><a href="/about">About Us</a></li>
                            <li aria-current={$page.url.pathname === '/' ? 'page' : undefined}><a href="/">My Account</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-3 col-sm-6">
                    <div class="footer-widget footer-widget-3 mt-2">
                        <h5 class="text-white position-relative mb-5 widget-title">Services</h5>
                        <ul class="footer-nav">
                            <li aria-current={$page.url.pathname === '/shared-hosting' ? 'page' : undefined}><a href="/shared-hosting">Shared Hosting</a></li>
                            <li aria-current={$page.url.pathname === '/vps-hosting' ? 'page' : undefined}><a href="/vps-hosting">VPS Hosting</a></li>
                            <li aria-current={$page.url.pathname === '/dedicated-server' ? 'page' : undefined}><a href="/dedicated-server">Dedicated Hosting</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-4 col-md-8">
                    <div class="footer-widget footer-sb-widget mt-2">
                        <h5 class="text-white position-relative mb-5 widget-title">Get In Touch</h5>
                        <form action="#" class="footer-sb-form position-relative">
                            <input type="email" placeholder="Type Your Mail">
                            <button type="submit" class="template-btn primary-btn btn-small">Subscribe</button>
                        </form>
                        <div class="ft-payment-method mt-40">
                            <h5 class="text-white position-relative ft-subtitle d-inline-block">We Accepted</h5>
                            <ul class="payment-list d-flex align-items-center mt-3">
                                <li class="d-inline-flex align-items-center justify-content-center"><img src={visa} alt="visa" class="img-fluid"></li>
                                <li class="d-inline-flex align-items-center justify-content-center"><img src={mastercard} alt="mastercard" class="img-fluid"></li>
                                <li class="d-inline-flex align-items-center justify-content-center"><img src={payoneer} alt="payoneer" class="img-fluid"></li>
                                <li class="d-inline-flex align-items-center justify-content-center"><img src={paypal} alt="paypal" class="img-fluid"></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="footer-copyright">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="copyright-txt text-white">
                        <p class="mb-0">Copyright 2022 Hostim. All Rights Reserved</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="copyright-links mt-2 mt-md-0 text-start text-md-end">
                        <a href="/">Terms & Conditions</a>
                        <a href="/" class="ml-20">Privacy Policy</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>