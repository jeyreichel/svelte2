<script>
  import circle from "../../assets/img/shapes/circle.svg";
  import contactHeroLeft from "../../assets/img/shapes/contact-hero-left.png";
  import pic1 from "../../assets/img/0001.svg";
  import contactBgLeft from "../../assets/img/contact-bg-left.png";
  import contactBgRight from "../../assets/img/contact-bg-right.png";
</script>

<svelte:head>
  <title>Contact</title>
  <meta name="description" content="Contact this app" />
</svelte:head>

<!--breadcrumb area start-->
<section class="hero-style-1 contact-hero bg-white">
  <div
    class="hero-area overflow-hidden position-relative zindex-1 bg-primary-gradient pt-120"
  >
    <img
      src={circle}
      alt="circle shape"
      class="circle-shape position-absolute"
    />
    <img
      src={contactHeroLeft}
      alt="circle"
      class="left-bottom position-absolute"
    />
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-6">
          <div class="hero1-content-wrap">
            <h1 class="display-font mt-4">
              Contact us,<br /> Feel free to contact
            </h1>
            <p class="mt-4">
              Easily accessible customer service is crucial in today's 24-hour,
              online business environment Hostim's experienced team Members.
            </p>
            <a href="/" class="template-btn primary-btn rounded-pill mt-4"
              ><span class="me-2"><i class="fa-solid fa-comments" /></span>Live
              Chat</a
            >
          </div>
        </div>
        <div class="col-lg-6">
          <div class="hero-right">
            <img src={pic1} alt="hero image" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="hm-contact-info promo-area position-relative">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-4 col-md-6 col-sm-10">
          <div class="hm-ct-info-wrapper rounded">
            <span
              class="icon-wrapper rounded-circle d-inline-flex align-items-center justify-content-center"
            >
              <i class="fa-solid fa-phone" />
            </span>
            <div class="info-content mt-4">
              <h4>Hotline</h4>
              <span>+90 225 555 0118, + 015 (454) 678</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-10">
          <div class="hm-ct-info-wrapper rounded">
            <span
              class="icon-wrapper rounded-circle d-inline-flex align-items-center justify-content-center"
            >
              <i class="fa-solid fa-at" />
            </span>
            <div class="info-content mt-4">
              <h4>Email Us</h4>
              <span>supportinfo@gmail.com</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-10">
          <div class="hm-ct-info-wrapper rounded">
            <span
              class="icon-wrapper rounded-circle d-inline-flex align-items-center justify-content-center"
            >
              <i class="fa-solid fa-house" />
            </span>
            <div class="info-content mt-4">
              <h4>Address</h4>
              <span>3891 Ranchview, California, NY-1216</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!--breadcrumb area end-->

<!--contact form -->
<section
  class="hm-contact-area position-relative pt-60 pb-120 overflow-hidden bg-white zindex-1"
>
  <img src={contactBgLeft} alt="bg" class="position-absolute left-bottom" />
  <img src={contactBgRight} alt="bg" class="position-absolute right-bottom" />
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-5">
        <div class="ct-section-title text-center">
          <h2>We're Ready To Help You Send Us Message.</h2>
        </div>
      </div>
    </div>
    <div class="hm-contact-form mt-5" id="contact">
      <div class="col-12 pb-3 message-box d-none">
        <div class="alert alert-danger" />
      </div>
      <form action="" method="POST" id="contactForm" class="contact-us-form">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="row g-4">
              <div class="col-md-6">
                <div class="input-field">
                  <label for="name">Name</label>
                  <input
                    type="text"
                    class=""
                    name="name"
                    id="name"
                    placeholder="Enter name"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="input-field">
                  <label for="email">Email</label>
                  <input
                    type="email"
                    class=""
                    name="email"
                    id="email"
                    placeholder="Enter email"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="input-field">
                  <label for="phone">Phone</label>
                  <input
                    type="text"
                    class=""
                    name="phone"
                    id="phone"
                    placeholder="Enter phone"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="input-field">
                  <label for="subject">Subject</label>
                  <input
                    type="text"
                    class=""
                    name="subject"
                    id="subject"
                    placeholder="Enter subject"
                    required
                  />
                </div>
              </div>
              <div class="col-md-12">
                <div class="input-field">
                  <label for="message">Message</label>
                  <textarea
                    placeholder="Write Message"
                    rows="5"
                    name="message"
                    id="message"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="submit-btn text-center mt-4">
          <button
            type="submit"
            class="template-btn primary-btn border-0 rounded-pill"
            >Send Message
            <i class="fa-solid fa-chevron-right ms-2" />
          </button>
        </div>
      </form>
    </div>
  </div>
</section>
