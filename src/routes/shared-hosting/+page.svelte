<script>
  import shHeroBg from "../../assets/img/shapes/sh-hero-bg.png";
  import shHero from "../../assets/img/shared-hosting/sh-hero.svg";
  import handphone from "../../assets/img/shared-hosting/headphone.png";
  import handphoneWhite from "../../assets/img/shared-hosting/headphone-white.png";
  import server from "../../assets/img/shared-hosting/server.png";
  import serverWhite from "../../assets/img/shared-hosting/server-white.png";
  import ssd from "../../assets/img/shared-hosting/ssd.png";
  import ssdWhite from "../../assets/img/shared-hosting/ssd-white.png";
  import shPricingBg from "../../assets/img/shapes/sh-pricing-bg.png";
  import cpanelBuilding from "../../assets/img/shapes/cpanel-building.png";
  import shCpanelCircle from "../../assets/img/shapes/sh-cpanel-circle.png";
  import cpanelCurve from "../../assets/img/shapes/cpanel-curve.png";
  import laptop from "../../assets/img/shared-hosting/laptop.png";
  import shAboutRight from "../../assets/img/shapes/sh-about-right.png";
  import shAboutRightDark from "../../assets/img/shapes/sh-about-right-dark.png";
  import shAboutCircle from "../../assets/img/shapes/sh-about-circle.png";
  import shAboutCircleSmall from "../../assets/img/shapes/sh-about-circle-small.png";
  import manSpeed from "../../assets/img/shared-hosting/man-speed.png";
  import support from "../../assets/img/shared-hosting/support.jpg";
  import client1 from "../../assets/img/shared-hosting/client-1.png";
  import client2 from "../../assets/img/shared-hosting/client-2.png";
  import client3 from "../../assets/img/shared-hosting/client-3.png";
  import clientHome1 from "../../assets/img/home2/client-1.png";
  import clientHome2 from "../../assets/img/home2/client-2.png";
  import clientHome3 from "../../assets/img/home2/client-3.png";
  import twoStar from "../../assets/img/two-star.svg";
  import threeStar from "../../assets/img/three-star.svg";
  import fiveStar from "../../assets/img/five-star.svg";
  import arrowDark from "../../assets/img/shapes/arrow-dark.png";
  import arrowWhite from "../../assets/img/shapes/arrow-white.png";
</script>

<svelte:head>
  <title>Shared Hosting</title>
  <meta name="description" content="Shared Hosting this app" />
</svelte:head>
<!--hero section start-->
<section
  class="sh-hero-section position-relative bg-primary-gradient ptb-100 zindex-1 overflow-hidden"
>
  <img src={shHeroBg} alt="shape" class="position-absolute left-bottom" />
  <div class="container">
    <div class="row align-items-center">
      <div class="col-lg-6 order-2 order-lg-1">
        <div class="sh-hero-left mt-5 mt-lg-0">
          <h1 class="display-font">We Provide Best Shared Web Hosting</h1>
          <div class="wp-hero-list mt-20">
            <ul>
              <li>
                <span class="me-2">
                  <svg
                    width="16"
                    height="13"
                    viewBox="0 0 16 13"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M7.29784 12.9999C7.24944 12.9999 7.20157 12.9906 7.15723 12.9727C7.11289 12.9548 7.07304 12.9287 7.04019 12.8959L0.093221 5.96473C0.0469107 5.91852 0.0162099 5.86086 0.00487599 5.79881C-0.00645791 5.73676 0.00206669 5.673 0.0294066 5.61535C0.0567465 5.5577 0.101716 5.50865 0.15881 5.4742C0.215905 5.43976 0.282649 5.42141 0.350872 5.42141H3.69476C3.74497 5.42142 3.79459 5.43135 3.84028 5.45055C3.88596 5.46975 3.92665 5.49777 3.95961 5.53271L6.28131 7.99636C6.53222 7.50165 7.01795 6.67793 7.87031 5.6742C9.13039 4.19033 11.4742 2.00802 15.4842 0.0379785C15.5617 -9.01509e-05 15.6519 -0.00997048 15.7369 0.0102886C15.8219 0.0305477 15.8956 0.0794735 15.9434 0.147405C15.9912 0.215337 16.0097 0.297336 15.9952 0.377211C15.9806 0.457086 15.9341 0.529031 15.8649 0.578839C15.8496 0.589875 14.3035 1.71289 12.5241 3.76989C10.8865 5.66284 8.70954 8.7581 7.63834 12.754C7.61952 12.8242 7.57575 12.8866 7.51402 12.9312C7.45229 12.9758 7.37614 13 7.29774 13L7.29784 12.9999Z"
                      fill="white"
                    />
                  </svg>
                </span>
                Managed Performance, Security, & Updates
              </li>
              <li>
                <span class="me-2">
                  <svg
                    width="16"
                    height="13"
                    viewBox="0 0 16 13"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M7.29784 12.9999C7.24944 12.9999 7.20157 12.9906 7.15723 12.9727C7.11289 12.9548 7.07304 12.9287 7.04019 12.8959L0.093221 5.96473C0.0469107 5.91852 0.0162099 5.86086 0.00487599 5.79881C-0.00645791 5.73676 0.00206669 5.673 0.0294066 5.61535C0.0567465 5.5577 0.101716 5.50865 0.15881 5.4742C0.215905 5.43976 0.282649 5.42141 0.350872 5.42141H3.69476C3.74497 5.42142 3.79459 5.43135 3.84028 5.45055C3.88596 5.46975 3.92665 5.49777 3.95961 5.53271L6.28131 7.99636C6.53222 7.50165 7.01795 6.67793 7.87031 5.6742C9.13039 4.19033 11.4742 2.00802 15.4842 0.0379785C15.5617 -9.01509e-05 15.6519 -0.00997048 15.7369 0.0102886C15.8219 0.0305477 15.8956 0.0794735 15.9434 0.147405C15.9912 0.215337 16.0097 0.297336 15.9952 0.377211C15.9806 0.457086 15.9341 0.529031 15.8649 0.578839C15.8496 0.589875 14.3035 1.71289 12.5241 3.76989C10.8865 5.66284 8.70954 8.7581 7.63834 12.754C7.61952 12.8242 7.57575 12.8866 7.51402 12.9312C7.45229 12.9758 7.37614 13 7.29774 13L7.29784 12.9999Z"
                      fill="white"
                    />
                  </svg>
                </span>
                Unhindered performance with your own server resources
              </li>
              <li>
                <span class="me-2">
                  <svg
                    width="16"
                    height="13"
                    viewBox="0 0 16 13"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M7.29784 12.9999C7.24944 12.9999 7.20157 12.9906 7.15723 12.9727C7.11289 12.9548 7.07304 12.9287 7.04019 12.8959L0.093221 5.96473C0.0469107 5.91852 0.0162099 5.86086 0.00487599 5.79881C-0.00645791 5.73676 0.00206669 5.673 0.0294066 5.61535C0.0567465 5.5577 0.101716 5.50865 0.15881 5.4742C0.215905 5.43976 0.282649 5.42141 0.350872 5.42141H3.69476C3.74497 5.42142 3.79459 5.43135 3.84028 5.45055C3.88596 5.46975 3.92665 5.49777 3.95961 5.53271L6.28131 7.99636C6.53222 7.50165 7.01795 6.67793 7.87031 5.6742C9.13039 4.19033 11.4742 2.00802 15.4842 0.0379785C15.5617 -9.01509e-05 15.6519 -0.00997048 15.7369 0.0102886C15.8219 0.0305477 15.8956 0.0794735 15.9434 0.147405C15.9912 0.215337 16.0097 0.297336 15.9952 0.377211C15.9806 0.457086 15.9341 0.529031 15.8649 0.578839C15.8496 0.589875 14.3035 1.71289 12.5241 3.76989C10.8865 5.66284 8.70954 8.7581 7.63834 12.754C7.61952 12.8242 7.57575 12.8866 7.51402 12.9312C7.45229 12.9758 7.37614 13 7.29774 13L7.29784 12.9999Z"
                      fill="white"
                    />
                  </svg>
                </span>
                Expandable RAM & storage
              </li>
            </ul>
          </div>
          <p class="lead mt-30 mb-30">
            Start Web Hosting at <mark>$11.99/mo!</mark>
          </p>
          <a href="/shared-hosting" class="template-btn primary-btn rounded-pill"
            >Get Started Now</a
          >
        </div>
      </div>
      <div class="col-lg-6 order-1 order-lg-2">
        <div class="sh-hero-right">
          <img src={shHero} alt="shape" />
        </div>
      </div>
    </div>
  </div>
</section>
<!--hero section end-->

<!--feature area-->
<section class="sh-benefits pt-120 pb-120 position-relative zindex-1">
  <span class="sh-bn-circle position-absolute" />
  <div class="container">
    <div class="row g-4">
      <div class="col-lg-6">
        <div class="sh-section-title">
          <h2 class="mb-4">Benefits of Using Shared <br /> Web Hosting.</h2>
          <p>
            We were hoping you'd say that. DreamHost offers aspiring website
            owners a great starting place Shared hosting plans that won't pinch
            the purse strings or overwhelm your to-do list.
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="sh-benefits-wrapper bg-white deep-shadow rounded">
          <div class="sh-item-top d-flex align-items-center">
            <span
              class="icon-wrapper d-inline-flex flex-shrink-0 align-items-center justify-content-center rounded-circle"
            >
              <img
                src={handphone}
                alt="not found"
                class="img-fluid logo-black"
              />
              <img
                src={handphoneWhite}
                alt="not found"
                class="img-fluid logo-white"
              />
            </span>
            <h3 class="h4 ms-3 mb-0">24x7 Technical Support</h3>
          </div>
          <p class="mb-0 mt-4">
            Contrary to popular belief, Lorem Ipsum is not simply random text.
            It has roots in a piece of classical Latin literature from 45 BC,
            making it over 2000 years old. Richard McClintock, a Latin professor
            at Hampden-Sydney
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="sh-benefits-wrapper bg-white deep-shadow rounded">
          <div class="sh-item-top d-flex align-items-center">
            <span
              class="icon-wrapper d-inline-flex flex-shrink-0 align-items-center justify-content-center rounded-circle"
            >
              <img src={server} alt="not found" class="img-fluid logo-black" />
              <img
                src={serverWhite}
                alt="not found"
                class="img-fluid logo-white"
              />
            </span>
            <h3 class="h4 ms-3 mb-0">Low Number of Clients per Server</h3>
          </div>
          <p class="mb-0 mt-4">
            The power of Windows and open source combined. Just because you
            choose Windows VPS hosting doesn't mean you have to be tied to
            Microsoft technologies power of Windows and open source combined.
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="sh-benefits-wrapper bg-white deep-shadow rounded">
          <div class="sh-item-top d-flex align-items-center">
            <span
              class="icon-wrapper d-inline-flex flex-shrink-0 align-items-center justify-content-center rounded-circle"
            >
              <img src={ssd} alt="not found" class="img-fluid logo-black" />
              <img
                src={ssdWhite}
                alt="not found"
                class="img-fluid logo-white"
              />
            </span>
            <h3 class="h4 ms-3 mb-0">SSD Technology for 99.9% Uptime.</h3>
          </div>
          <p class="mb-0 mt-4">
            Hampden-Sydney College in Virginia, looked up one of the more
            obscure Latin words, consectetur, from a Lorem Ipsum passage, and
            going through the cites of the word in classical literature,
            discovered the un doubtable source.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
<!--feature area end-->

<!--pricing area start-->
<section class="sh-pricing pb-120 position-relative zindex-1 overflow-hidden">
  <img
    src={shPricingBg}
    alt="pricing bg"
    class="position-absolute right-bottom"
  />
  <div class="container position-relative zindex-1">
    <span class="sh-pricing-circle position-absolute" />
    <span class="sh-pricing-circle-red position-absolute" />
    <div class="row justify-content-center">
      <div class="col-lg-7">
        <div class="sh-pricing-top text-center">
          <div class="sh-section-title text-center">
            <h2 class="mb-20">World-Famous Website Hosting Plans</h2>
            <p>
              Clear pricing backed by our unbeatable 97-Day Money-Back
              Guarantee.
            </p>
          </div>
          <div
            class="tab-switch-btn d-inline-flex align-items-center justify-content-center position-relative mt-4"
          >
            <span class="monthly fw-bold">Monthly</span>
            <input type="checkbox" class="switch-input position-absolute" />
            <span class="toggle-switch-btn rounded-pill position-relative" />
            <span class="yearly fw-bold">Yearly</span>
          </div>
        </div>
      </div>
    </div>
    <div class="row mt-5 justify-content-center g-4">
      <div class="col-xxl-3 col-lg-4 col-md-6 col-sm-10">
        <div
          class="sh-pricing-column pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow"
        >
          <h3 class="h5">Shared Starter</h3>
          <p>The ideal starting point into shared Hosting!</p>
          <span class="saving-badge">Save 60% over Monthly</span>
          <h4 class="h2 mt-2 monthly-price">$4.25<span>/mo</span></h4>
          <h4 class="h2 mt-2 yearly-price">$32<span>/yr</span></h4>
          <ul class="feature-list mt-4">
            <li>
              <span class="me-2"><i class="fa-solid fa-rocket" /></span>10 GB
              SSD Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-database" /></span>10
              MySQL Database
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-globe" /></span>Unlimited
              Website
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-gears" /></span>cPanel
              Control Panel
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-briefcase" /></span>Auto
              Backup & Cloud Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-network-wired" /></span
              >Free Supersonic CDN
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-window-maximize" /></span
              >24 Hours Website Migration
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-lock" /></span>Automatic
              SSL installation
            </li>
          </ul>
          <a
            href="/shared-hosting"
            class="template-btn secondary-btn rounded-pill btn-small w-100 text-center mt-40"
            >Purchase Plan</a
          >
        </div>
      </div>
      <div class="col-xxl-3 col-lg-4 col-md-6 col-sm-10">
        <div
          class="sh-pricing-column pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow"
        >
          <h3 class="h5">Shared Basic</h3>
          <p>The ideal starting point into shared Hosting!</p>
          <span class="saving-badge">Save 60% over Monthly</span>
          <h4 class="h2 mt-2 monthly-price">$10.19<span>/mo</span></h4>
          <h4 class="h2 mt-2 yearly-price">$80<span>/yr</span></h4>
          <ul class="feature-list mt-4">
            <li>
              <span class="me-2"><i class="fa-solid fa-rocket" /></span>10 GB
              SSD Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-database" /></span>10
              MySQL Database
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-globe" /></span>Unlimited
              Website
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-gears" /></span>cPanel
              Control Panel
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-briefcase" /></span>Auto
              Backup & Cloud Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-network-wired" /></span
              >Free Supersonic CDN
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-window-maximize" /></span
              >24 Hours Website Migration
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-lock" /></span>Automatic
              SSL installation
            </li>
          </ul>
          <a
            href="/shared-hosting"
            class="template-btn secondary-btn rounded-pill btn-small w-100 text-center mt-40"
            >Purchase Plan</a
          >
        </div>
      </div>
      <div class="col-xxl-3 col-lg-4 col-md-6 col-sm-10">
        <div
          class="sh-pricing-column pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow"
        >
          <span
            class="popular-badge text-center d-inline-block position-absolute"
            >Popular</span
          >
          <h3 class="h5">Shared Business</h3>
          <p>The ideal starting point into shared Hosting!</p>
          <span class="saving-badge">Save 60% over Monthly</span>
          <h4 class="h2 mt-2 monthly-price">$15.25<span>/mo</span></h4>
          <h4 class="h2 mt-2 yearly-price">$70<span>/yr</span></h4>
          <ul class="feature-list mt-4">
            <li>
              <span class="me-2"><i class="fa-solid fa-rocket" /></span>10 GB
              SSD Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-database" /></span>10
              MySQL Database
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-globe" /></span>Unlimited
              Website
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-gears" /></span>cPanel
              Control Panel
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-briefcase" /></span>Auto
              Backup & Cloud Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-network-wired" /></span
              >Free Supersonic CDN
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-window-maximize" /></span
              >24 Hours Website Migration
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-lock" /></span>Automatic
              SSL installation
            </li>
          </ul>
          <a
            href="/shared-hosting"
            class="template-btn primary-btn rounded-pill btn-small w-100 text-center mt-40"
            >Purchase Plan</a
          >
        </div>
      </div>
      <div class="col-xxl-3 col-lg-4 col-md-6 col-sm-10">
        <div
          class="sh-pricing-column pricing-column overflow-hidden position-relative bg-white rounded-10 deep-shadow"
        >
          <h3 class="h5">Shared Pro</h3>
          <p>The ideal starting point into shared Hosting!</p>
          <span class="saving-badge">Save 60% over Monthly</span>
          <h4 class="h2 mt-2 monthly-price">$20.19<span>/mo</span></h4>
          <h4 class="h2 mt-2 yearly-price">$250<span>/yr</span></h4>
          <ul class="feature-list mt-4">
            <li>
              <span class="me-2"><i class="fa-solid fa-rocket" /></span>10 GB
              SSD Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-database" /></span>10
              MySQL Database
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-globe" /></span>Unlimited
              Website
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-gears" /></span>cPanel
              Control Panel
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-briefcase" /></span>Auto
              Backup & Cloud Storage
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-network-wired" /></span
              >Free Supersonic CDN
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-window-maximize" /></span
              >24 Hours Website Migration
            </li>
            <li>
              <span class="me-2"><i class="fa-solid fa-lock" /></span>Automatic
              SSL installation
            </li>
          </ul>
          <a
            href="/shared-hosting"
            class="template-btn secondary-btn rounded-pill btn-small w-100 text-center mt-40"
            >Purchase Plan</a
          >
        </div>
      </div>
    </div>
  </div>
</section>
<!--pricing area end-->

<!--control panel area start-->
<section
  class="sh-control-panel bg-primary-gradient pt-120 pb-120 position-relative overflow-hidden zindex-1"
>
  <img
    src={cpanelBuilding}
    alt="building"
    class="position-absolute building-shape"
  />
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-5">
        <div class="sh-section-title text-center">
          <h2>Hostim Web Hosting Easy Control Panel.</h2>
        </div>
      </div>
    </div>
    <div class="row mt-5 align-items-center">
      <div class="col-lg-6">
        <div class="sh-cp-left position-relative zindex-1 mb-5 mb-lg-0">
          <div class="accordion cp-accordion" id="cp_accordion">
            <div class="accordion-single">
              <div class="accordion-header">
                <a href="/shared-hosting" data-bs-toggle="collapse">
                  <h6>Installing apps is easy with Plesk!</h6>
                </a>
              </div>
              <div
                class="accordion-collapse collapse"
                id="one"
                data-bs-parent="/shared-hostingcp_accordion"
              >
                <div class="accordion-body">
                  <p>
                    Over 100 of the very best applications, including WordPress,
                    all ready to install with just a click of the mouse or the
                    tap of the finger.
                  </p>
                  <a href="/shared-hosting"
                    ><i class="fa-solid fa-circle-arrow-right" /> Order Now</a
                  >
                </div>
              </div>
            </div>
            <div class="accordion-single">
              <div class="accordion-header">
                <a href="/shared-hosting" data-bs-toggle="collapse">
                  <h6>Simple Email Management</h6>
                </a>
              </div>
              <div
                class="accordion-collapse collapse show"
                id="two"
                data-bs-parent="/shared-hostingcp_accordion"
              >
                <div class="accordion-body">
                  <p>
                    Over 100 of the very best applications, including WordPress,
                    all ready to install with just a click of the mouse or the
                    tap of the finger.
                  </p>
                  <a href="/shared-hosting"
                    ><i class="fa-solid fa-circle-arrow-right" /> Order Now</a
                  >
                </div>
              </div>
            </div>
            <div class="accordion-single">
              <div class="accordion-header">
                <a href="/shared-hosting" data-bs-toggle="collapse">
                  <h6>Installing apps is easy with Plesk!</h6>
                </a>
              </div>
              <div
                class="accordion-collapse collapse"
                id="three"
                data-bs-parent="/shared-hostingcp_accordion"
              >
                <div class="accordion-body">
                  <p>
                    Over 100 of the very best applications, including WordPress,
                    all ready to install with just a click of the mouse or the
                    tap of the finger.
                  </p>
                  <a href="/shared-hosting"
                    ><i class="fa-solid fa-circle-arrow-right" /> Order Now</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="sh-cp-right position-relative zindex-1">
          <img
            src={shCpanelCircle}
            alt="circle"
            class="position-absolute circle"
          />
          <img src={cpanelCurve} alt="curve" class="position-absolute curve" />
          <img src={laptop} alt="laptop" class="img-fluid" />
        </div>
      </div>
    </div>
  </div>
</section>
<!--control panel end-->

<!--feature area starts-->
<section class="sh-features ptb-120 light-bg">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-5">
        <div class="section-title text-center">
          <h2>Shared Hosting all Plans Include Features.</h2>
        </div>
      </div>
    </div>
    <div class="row mt-5 g-4">
      <div class="col-lg-4 col-sm-6">
        <div class="sh-feature-list">
          <ul>
            <li><i class="fa-solid fa-check" /> Reseller & Sub Account</li>
            <li><i class="fa-solid fa-check" /> Secure Shell(SSH) Access</li>
            <li><i class="fa-solid fa-check" /> IPv6 Support</li>
            <li><i class="fa-solid fa-check" /> Rails, Python, Perl Support</li>
            <li><i class="fa-solid fa-check" /> Unlimited SFTP Users</li>
          </ul>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6">
        <div class="sh-feature-list">
          <ul>
            <li><i class="fa-solid fa-check" /> Reseller & Sub Account</li>
            <li><i class="fa-solid fa-check" /> Secure Shell(SSH) Access</li>
            <li><i class="fa-solid fa-check" /> IPv6 Support</li>
            <li><i class="fa-solid fa-check" /> Rails, Python, Perl Support</li>
            <li><i class="fa-solid fa-check" /> Unlimited SFTP Users</li>
          </ul>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6">
        <div class="sh-feature-list">
          <ul>
            <li><i class="fa-solid fa-check" /> Reseller & Sub Account</li>
            <li><i class="fa-solid fa-check" /> Secure Shell(SSH) Access</li>
            <li><i class="fa-solid fa-check" /> IPv6 Support</li>
            <li><i class="fa-solid fa-check" /> Rails, Python, Perl Support</li>
            <li><i class="fa-solid fa-check" /> Unlimited SFTP Users</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>
<!--feature area end-->

<!--about section start-->
<section
  class="sh-about-section pt-120 pb-120 overflow-hidden position-relative zindex-1"
>
  <img
    src={shAboutRight}
    alt="shape"
    class="position-absolute right-bottom logo-dark"
  />
  <img
    src={shAboutRightDark}
    alt="shape"
    class="position-absolute right-bottom logo-white"
  />
  <img
    src={shAboutCircle}
    alt="shape"
    class="position-absolute sh-about-circle"
  />
  <img
    src={shAboutCircleSmall}
    alt="shape"
    class="position-absolute sh-about-circle-small"
  />
  <div class="container">
    <div class="row align-items-center g-5">
      <div class="col-lg-6 order-2 order-lg-1">
        <div class="sh-about-content">
          <h2 class="mb-30">Hostim With Lighting Fast Loading Speed.</h2>
          <p class="mb-40">
            Speed is one of the most basic but powerful features that you will
            get instantly with your Cloud VPS hosting package. A fast loading
            website ensures that your competitor are not able to snatch your
            potential customers.
          </p>
          <a href="/shared-hosting" class="template-btn primary-btn rounded-pill"
            >Explore More</a
          >
        </div>
      </div>
      <div class="col-lg-6 order-1 order-lg-2">
        <div class="sh-about-img">
          <img src={manSpeed} alt="man" class="img-fluid" />
        </div>
      </div>
    </div>
    <div class="row align-items-center g-5 mt-60">
      <div class="col-lg-6">
        <div class="sh-about-img">
          <img src={support} alt="support" class="img-fluid rounded" />
        </div>
      </div>
      <div class="col-lg-6">
        <div class="sh-about-content">
          <h2 class="mb-30">
            Let us take worries away & put time back in your day
          </h2>
          <p class="mb-40">
            We offer expert 24/7/365 problem-solving for everyone. For a closer
            partnership, choose the Advanced Support add-on that enhances your
            support experience or the Premium Support add-on where our Senior
            Support Engineers work as an extension of your in-house team.
          </p>
          <div class="sh-feature-list text-start mb-40">
            <ul>
              <li><i class="fa-solid fa-check" /> Reseller & Sub Account</li>
              <li><i class="fa-solid fa-check" /> Secure Shell(SSH) Access</li>
              <li><i class="fa-solid fa-check" /> IPv6 Support</li>
              <li>
                <i class="fa-solid fa-check" /> Rails, Python, Perl Support
              </li>
              <li><i class="fa-solid fa-check" /> Unlimited SFTP Users</li>
            </ul>
          </div>
          <a href="/shared-hosting" class="template-btn primary-btn rounded-pill"
            >Explore Now</a
          >
        </div>
      </div>
    </div>
  </div>
</section>
<!--about section end-->

<!--feedback section start-->
<section class="sh-feedback pt-120 pb-120">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-5">
        <div class="section-title text-center">
          <h2>Customer Feedback! Say About Us?</h2>
        </div>
      </div>
    </div>
    <div class="row mt-5 g-4 justify-content-center">
      <div class="col-lg-4 col-md-6">
        <div class="sh-feedback-wrapper bg-white rounded-10">
          <img
            src={client1}
            alt="client"
            class="clients-thumb img-fluid rounded-circle"
          />
          <span class="quote-icon float-end mt-3">
            <svg
              width="36"
              height="27"
              viewBox="0 0 36 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                opacity="0.4"
                d="M11.25 4.5L13.5 0H9C4.0275 0 0 6.2775 0 11.25V27H15.75V11.25H6.75C6.75 4.5 11.25 4.5 11.25 4.5ZM27 11.25C27 4.5 31.5 4.5 31.5 4.5L33.75 0H29.25C24.2775 0 20.25 6.2775 20.25 11.25V27H36V11.25H27Z"
                fill="/shared-hostingDBDBDB"
              />
            </svg>
          </span>
          <p class="mt-20">
            humouror randomised words which look even slightly believable. If
            Lorem Ipsum Lorem Ipsum, you need to be sure there isn't anything
            embarrassing.
          </p>
          <hr class="spacer" />
          <div
            class="sh-feedback-bottom d-flex align-items-center justify-content-between"
          >
            <div class="sh-feedback-client">
              <h6 class="mb-0">Darrell Steward</h6>
              <span>Co Founder</span>
            </div>
            <div class="sh-feedback-rating">
              <img src={threeStar} alt="rating" class="img-fluid" />
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="sh-feedback-wrapper bg-white rounded-10">
          <img
            src={client2}
            alt="client"
            class="clients-thumb img-fluid rounded-circle"
          />
          <span class="quote-icon float-end mt-3">
            <svg
              width="36"
              height="27"
              viewBox="0 0 36 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                opacity="0.4"
                d="M11.25 4.5L13.5 0H9C4.0275 0 0 6.2775 0 11.25V27H15.75V11.25H6.75C6.75 4.5 11.25 4.5 11.25 4.5ZM27 11.25C27 4.5 31.5 4.5 31.5 4.5L33.75 0H29.25C24.2775 0 20.25 6.2775 20.25 11.25V27H36V11.25H27Z"
                fill="/shared-hostingDBDBDB"
              />
            </svg>
          </span>
          <p class="mt-20">
            humouror randomised words which look even slightly believable. If
            Lorem Ipsum Lorem Ipsum, you need to be sure there isn't anything
            embarrassing.
          </p>
          <hr class="spacer" />
          <div
            class="sh-feedback-bottom d-flex align-items-center justify-content-between"
          >
            <div class="sh-feedback-client">
              <h6 class="mb-0">Darrell Steward</h6>
              <span>Co Founder</span>
            </div>
            <div class="sh-feedback-rating">
              <img src={fiveStar} alt="rating" class="img-fluid" />
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="sh-feedback-wrapper bg-white rounded-10">
          <img
            src={client3}
            alt="client"
            class="clients-thumb img-fluid rounded-circle"
          />
          <span class="quote-icon float-end mt-3">
            <svg
              width="36"
              height="27"
              viewBox="0 0 36 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                opacity="0.4"
                d="M11.25 4.5L13.5 0H9C4.0275 0 0 6.2775 0 11.25V27H15.75V11.25H6.75C6.75 4.5 11.25 4.5 11.25 4.5ZM27 11.25C27 4.5 31.5 4.5 31.5 4.5L33.75 0H29.25C24.2775 0 20.25 6.2775 20.25 11.25V27H36V11.25H27Z"
                fill="/shared-hostingDBDBDB"
              />
            </svg>
          </span>
          <p class="mt-20">
            humouror randomised words which look even slightly believable. If
            Lorem Ipsum Lorem Ipsum, you need to be sure there isn't anything
            embarrassing.
          </p>
          <hr class="spacer" />
          <div
            class="sh-feedback-bottom d-flex align-items-center justify-content-between"
          >
            <div class="sh-feedback-client">
              <h6 class="mb-0">Darrell Steward</h6>
              <span>Co Founder</span>
            </div>
            <div class="sh-feedback-rating">
              <img src={twoStar} alt="rating" class="img-fluid" />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div
      class="clients-explore d-flex app-explore align-items-center justify-content-center mt-10"
    >
      <div class="app-thumbs">
        <img
          src={clientHome1}
          alt="not found"
          class="img-fluid rounded-circle"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title=""
          data-bs-original-title="Darrel"
          aria-label="Darrel"
        />
        <img
          src={clientHome2}
          alt="not found"
          class="img-fluid rounded-circle"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title=""
          data-bs-original-title="Steward"
          aria-label="Steward"
        />
        <img
          src={clientHome3}
          alt="not found"
          class="img-fluid rounded-circle"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title=""
          data-bs-original-title="Oswarld"
          aria-label="Oswarld"
        />
      </div>
      <img src={arrowDark} alt="arrow dark" class="img-fluid ms-2 logo-black" />
      <img
        src={arrowWhite}
        alt="arrow white"
        class="img-fluid ms-2 logo-white"
      />
      <div class="app-info ms-2">
        <a href="/testimonials">
          <h6 class="text-decoration-underline">More Review</h6>
        </a>
      </div>
    </div>
  </div>
</section>
<!--feedback section end-->

<!--faq section-->
<section class="faq-section pt-120 pb-120 sh-faq">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-6">
        <div class="text-center">
          <h2>Frequently Asked Questions</h2>
          <p>
            We are regularly rated 5 stars by our customers and with over
            reviews on Trust-pilot and Facebook, see for yourself why you can
            trust us to power your website.
          </p>
        </div>
      </div>
    </div>
    <div class="faq-tab hm2-faq-tab mt-5">
      <div class="row">
        <div class="col-lg-4">
          <div class="tab-left">
            <ul class="hm2-server-tab-control nav nav-tabs border-0">
              <li>
                <button
                  class="active"
                  data-bs-toggle="tab"
                  data-bs-target="/shared-hostingfaq_shared_hosting"
                  ><i class="fa-solid fa-server" /><span class="ms-3"
                    >Shared Hosting</span
                  ></button
                >
              </li>
              <li>
                <button
                  data-bs-toggle="tab"
                  data-bs-target="/shared-hostingfaq_wp_hosting"
                  ><i class="fa-brands fa-wordpress" /><span class="ms-3"
                    >WordPress Hosting</span
                  ></button
                >
              </li>
              <li>
                <button
                  data-bs-toggle="tab"
                  data-bs-target="/shared-hostingfaq_vps_hosting"
                  ><i class="fa-solid fa-database" /><span class="ms-3"
                    >Vps Hosting</span
                  ></button
                >
              </li>
              <li>
                <button
                  data-bs-toggle="tab"
                  data-bs-target="/shared-hostingfaq_could_hosting"
                  ><i class="fa-solid fa-cloud-meatball" /><span class="ms-3"
                    >Dedicated Hosting</span
                  ></button
                >
              </li>
            </ul>
          </div>
        </div>
        <div class="col-lg-8">
          <div class="tab-content mt-5 mt-lg-0">
            <div class="tab-pane fade show active" id="faq_shared_hosting">
              <div
                class="accordion hm2-accordion rounded-2 deep-shadow bg-white"
                id="accordion_1"
              >
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What is Shared hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse show"
                    id="sh_1"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >How many websites can I host?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_2"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >Does Shared Hosting include email?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_3"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What's the difference between a domain name and web
                      hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_4"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What's the difference between a domain name and web
                      hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_5"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >Can I upgrade to a more powerful hosting plan later?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_6"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >Do you include SSL Certificates?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_7"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What if I have a domain at another company? Can I
                      transfer it?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_8"
                    data-bs-parent="/shared-hostingaccordion_1"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="tab-pane fade" id="faq_wp_hosting">
              <div
                class="accordion hm2-accordion rounded-2 deep-shadow bg-white"
                id="accordion_2"
              >
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What is WordPress hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse show"
                    id="sh_9"
                    data-bs-parent="/shared-hostingaccordion_2"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >How many websites can I host?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_10"
                    data-bs-parent="/shared-hostingaccordion_2"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >Do you provide SSL Certificate?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_11"
                    data-bs-parent="/shared-hostingaccordion_2"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="tab-pane fade" id="faq_vps_hosting">
              <div
                class="accordion hm2-accordion rounded-2 deep-shadow bg-white"
                id="accordion_3"
              >
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What is Vps hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse show"
                    id="sh_12"
                    data-bs-parent="/shared-hostingaccordion_3"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >How many websites can I host?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse"
                    id="sh_13"
                    data-bs-parent="/shared-hostingaccordion_3"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="tab-pane fade" id="faq_could_hosting">
              <div
                class="accordion hm2-accordion rounded-2 deep-shadow bg-white"
                id="accordion_4"
              >
                <div class="accordion-item">
                  <div class="accordion-header">
                    <a href="/shared-hosting" data-bs-toggle="collapse"
                      >What is Cloud hosting?</a
                    >
                  </div>
                  <div
                    class="accordion-collapse collapse show"
                    id="sh_14"
                    data-bs-parent="/shared-hostingaccordion_4"
                  >
                    <div class="accordion-body">
                      <p class="mb-0">
                        We care about safety big time — and so do your site's
                        visitors. With a Shared Hosting account, you get an SSL
                        certificate for free to add to your site. In this day
                        and age, having an SSL for your site is a no-brainer
                        best practice. Not only does an SSL help your visitors
                        feel safe interacting with your site — this is
                        particularly important if you run an e-commerce site.
                      </p>
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
<!--faq section end-->
