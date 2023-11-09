<script>
    import giftBox from '../assets/img/shapes/gift-box.png';
    import giftBox2 from '../assets/img/shapes/gift-box-2.png';
    import blackCircleRight from '../assets/img/shapes/black-circle-right.png';
    import blackCircleLeft from '../assets/img/shapes/black-circle-left.png';
    import bfLine from '../assets/img/shapes/bf-line.png';
    import bfLine2 from '../assets/img/shapes/bf-line-2.png';
    import bfDotsWhite from '../assets/img/shapes/bf-dots-white.png';
    import superSale from '../assets/img/black-friday/super-sale.png';
    import offerBadge from '../assets/img/black-friday/offer-badge.png';
</script>
<div class="notice-bar-area">
    <div class="notice-bar">
        <div class="container">
            <div class="row align-items-center g-4 justify-content-center">
                <div class="col-xl-4 col-md-7">
                    <div class="nt-sale d-flex align-items-center justify-content-center justify-content-md-start">
                        <h5 class="mb-0 text-white me-3 me-md-4">Black Friday Sale</h5>
                        <ul class="countdown-timer nt-downcount d-flex align-items-center" data-date="12/30/2022 23:59:59">
                            <li>
                                <span class="hours box">12</span>
                                <span class="subtitle d-block">Hour</span>
                            </li>
                            <li>
                                <span class="minutes box">54</span>
                                <span class="subtitle d-block">Minutes</span>
                            </li>
                            <li>
                                <span class="seconds box">32</span>
                                <span class="subtitle d-block">Sec</span>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-5 d-none d-xl-block">
                    <div class="notice-info">
                        <p class="mb-0 text-white">Get 80% off Hosting plans + free Domain & SSL!</p>
                    </div>
                </div>
                <div class="col-xl-3 col-md-5">
                    <div class="text-center text-md-end">
                        <button type="button" class="notice-toggle notice-btn fs-sm fw-bold">View Details<span class="ms-1"><i class="fa-solid fa-angle-down"></i></span></button>
                        <button type="button" class="notice-close notice-btn fs-sm fw-bold ms-5"><i class="fa-solid fa-xmark"></i></button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="notice-wrapper w-100">
    <section class="friday-hero position-relative overflow-hidden zindex-1">
        <img src={giftBox} alt="gift box" class="position-absolute start-0 top-0 zindex--1">
        <img src={giftBox2} alt="gift box" class="position-absolute gift-box-right zindex--1">
        <img src={blackCircleRight} alt="circle" class="position-absolute bottom-0 end-0 zindex--1">
        <img src={blackCircleLeft} alt="circle" class="position-absolute bottom-0 start-0 zindex--1">
        <img src={bfLine} alt="not found" class="position-absolute bf-line-left">
        <img src={bfLine2} alt="not found" class="position-absolute bf-line-top zindex--1">
        <img src={giftBox2} alt="gift box" class="position-absolute gift-box-sm start-50 zindex--1">
        <img src={bfDotsWhite} alt="dots shape" class="position-absolute dots-shape-white zindex--1">
        <div class="container">
            <div class="row align-items-center justify-content-center g-4">
                <div class="col-xl-4 col-md-6">
                    <div class="super-sale-countdown">
                        <img src={superSale} alt="not found" class="img-fluid">
                        <ul class="countdown-timer sp-downcount-timer d-flex align-items-center mt-4 mb-5" data-date="12/30/2022 23:59:59">
                            <li>
                                <span class="days box">24</span>
                                <span class="subtitle">Days</span>
                            </li>
                            <li>
                                <span class="hours box">10</span>
                                <span class="subtitle">Hour</span>
                            </li>
                            <li>
                                <span class="minutes box">45</span>
                                <span class="subtitle">Minutes</span>
                            </li>
                            <li>
                                <span class="seconds box">10</span>
                                <span class="subtitle">Sec</span>
                            </li>
                        </ul>
                        <a href="/" class="template-btn primary-btn">Get Started Now</a>
                    </div>
                </div>
                <div class="col-xl-5 col-lg-6 col-md-6">
                    <div class="offer-badge">
                        <img src={offerBadge} alt="not found" class="img-fluid">
                    </div>
                </div>
                <div class="col-xl-3 col-lg-6 col-md-10">
                    <div class="friday-offer-packages">
                        <div class="friday-hosting-offer position-relative rounded">
                            <span class="title-badge">Shared Hosting</span>
                            <span class="angle-shape"></span>
                            <span class="sale-price">From $8.54</span>
                            <h3 class="price mt-2 mb-20">$1.35 <span>USD/MO</span></h3>
                            <a href="/" class="template-btn primary-btn py-2 text-uppercase">Save Now</a>
                        </div>
                        <div class="friday-hosting-offer position-relative rounded mt-40">
                            <span class="title-badge">Web Hosting</span>
                            <span class="angle-shape"></span>
                            <span class="sale-price">From $8.54</span>
                            <h3 class="price mt-2 mb-20">$3.25 <span>USD/MO</span></h3>
                            <a href="/" class="template-btn primary-btn py-2 text-uppercase">Save Now</a>
                        </div>
                        <div class="friday-hosting-offer position-relative rounded mt-40">
                            <span class="title-badge">Email Hosting</span>
                            <span class="angle-shape"></span>
                            <span class="sale-price">From $8.54</span>
                            <h3 class="price mt-2 mb-20">$4.35 <span>USD/MO</span></h3>
                            <a href="/" class="template-btn primary-btn py-2 text-uppercase">Save Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>