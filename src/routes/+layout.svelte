<script>
  import Header from "./Header.svelte";
  import Loader from "./Loader.svelte";
  import Notice from "./Notice.svelte";
  import Footer from "./Footer.svelte";
  import "../assets/css/main.css";
  import "../assets/css/custom.css";
  import faveicon from '../assets/img/favicon.png';
</script>

<svelte:head>
  <link rel="icon" href={faveicon} type="image/png" sizes="16x16" />
  <script
    src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/2.11.8/umd/popper.min.js"
  ></script>
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/Swiper/11.0.3/swiper-bundle.min.js"
  ></script>
  <script
    src="https://unpkg.com/masonry-layout@4/dist/masonry.pkgd.min.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-slider/11.0.2/bootstrap-slider.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/Counter-Up/1.0.0/jquery.counterup.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/jquery.isotope/3.0.6/isotope.pkgd.min.js"
  ></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/countdown/2.6.0/countdown.min.js"
  ></script>
  <script>
    (function ($, document) {
      "use strict";

      $(function () {
        //Data Background Set
        $("[data-background]").each(function () {
          $(this).css(
            "background-image",
            "url(" + $(this).attr("data-background") + ")"
          );
        }); //ScrollTop

        $(".scrolltop-btn").on("click", function () {
          $("body,html").animate({
            scrollTop: 0,
          });
        }); //Mobile Menu

        $(".mobile-menu-toggle").on("click", function () {
          $(".body-overlay").addClass("overlay-on");
          $(".mobile-menu").addClass("active");
          return false;
        });
        $(".close-menu").on("click", function () {
          $(".mobile-menu").removeClass("active");
          $(".body-overlay").removeClass("overlay-on");
        });
        $(".body-overlay").on("click", function () {
          $(".mobile-menu").removeClass("active");
          $(this).removeClass("overlay-on");
        });
        $(".mobile-menu ul li.has-submenu a").each(function () {
          $(this).on("click", function () {
            $(this).siblings("ul").slideToggle();
            $(this).toggleClass("icon-rotate");
          });
        }); //Canvus Menu

        $(".ofcanvus-btn").on("click", function () {
          $(".ofcanvus-menu").addClass("active");
          return false;
        });
        $(".close-canvus").on("click", function () {
          $(".ofcanvus-menu").removeClass("active");
          return false;
        }); // Hide ofcanvus when click outside it.

        $(document).on("mouseup", function (e) {
          const ofcanvusMenu = $(".ofcanvus-menu");

          if (
            !ofcanvusMenu.is(e.target) &&
            ofcanvusMenu.has(e.target).length === 0
          ) {
            ofcanvusMenu.removeClass("active");
          }
        }); //dark light mood

        var setDarkMode = (active = false) => {
          var wrapper = document.querySelector(":root");

          if (active) {
            wrapper.setAttribute("data-bs-theme", "dark");
            localStorage.setItem("theme", "dark");
          } else {
            wrapper.setAttribute("data-bs-theme", "light");
            localStorage.setItem("theme", "light");
          }
        };

        var toggleDarkMode = () => {
          var theme = document
            .querySelector(":root")
            .getAttribute("data-bs-theme"); // If the current theme is "light", we want to activate dark

          setDarkMode(theme === "light");
        };

        var initDarkMode = () => {
          var theme = localStorage.getItem("theme");

          if (theme == "dark") {
            setDarkMode(true);
          } else {
            setDarkMode(false);
          }

          var toggleButton = document.querySelector(".dark-light-switcher");
          toggleButton &&
            toggleButton.addEventListener("click", toggleDarkMode);
        };

        initDarkMode(); //Pricing Table

        $(".switch-input").on("change", function () {
          if (this.checked) {
            $(".yearly-price").css({
              display: "block",
            });
            $(".monthly-price").css({
              display: "none",
            });
          } else {
            $(".yearly-price").css({
              display: "none",
            });
            $(".monthly-price").css({
              display: "block",
            });
          }
        });
        $(".expand-btn").each(function () {
          $(this).on("click", function () {
            $(this).siblings(".feature-list").toggleClass("expand-list");
            $(this).toggleClass("active");
          });
        }); //Feedback Slider

        const swiper = new Swiper(".feedback-slider", {
          slidesPerView: 3,
          speed: 700,
          spaceBetween: 30,
          slidesPerGroup: 2,
          loop: true,
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        });
        const blogSlider = new Swiper(".hm2-blog-slider", {
          slidesPerView: 3,
          spaceBetween: 30,
          loop: true,
          pagination: {
            el: ".swiper-pagination",
            type: "bullets",
            clickable: true,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        });
        const brandSlider = new Swiper(".brand-slider", {
          slidesPerView: 5,
          spaceBetween: 30,
          loop: true,
          autoplay: {
            delay: 3000,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            400: {
              slidesPerView: 2,
              spaceBetween: 20,
            },
            768: {
              slidesPerView: 3,
            },
            992: {
              slidesPerView: 4,
              spaceBetween: 25,
            },
            1200: {
              slidesPerView: 5,
              spaceBetween: 25,
            },
          },
        });
        const productSlider = new Swiper(".gm-product-slider", {
          slidesPerView: 4,
          spaceBetween: 30,
          loop: true,
          autoplay: {
            delay: 3000,
          },
          pagination: {
            el: ".swiper-pagination",
            type: "bullets",
            clickable: true,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            992: {
              slidesPerView: 3,
            },
            1400: {
              slidesPerView: 4,
              spaceBetween: 25,
            },
          },
        });
        const dmFeedbackSlider = new Swiper(".dm-feedback-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            992: {
              slidesPerView: 3,
            },
          },
        });
        const vps_scripts_slider = new Swiper(".vps-scripts-slider", {
          slidesPerView: 6,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          navigation: {
            nextEl: ".swiper-next",
            prevEl: ".swiper-prev",
          },
          autoplay: {
            delay: 5000,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            400: {
              slidesPerView: 2,
            },
            768: {
              slidesPerView: 3,
            },
            992: {
              slidesPerView: 4,
            },
            1200: {
              slidesPerView: 5,
            },
            1400: {
              slidesPerView: 6,
            },
          },
        }); //HM2 Feedback Slider

        const hm2_feedback_slider = new Swiper(".hm2-feedback-slider", {
          slidesPerView: 1,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
        }); //Game Hosting Feedback Slider

        const gh_feedback_slider = new Swiper(".gh-feedback-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
          breakpoints: {
            320: {
              slidesPerView: 1,
            },
            992: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        }); //Game Hosting Feedback Slider

        const h4_feedback_slider = new Swiper(".h4-feedback-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        }); //home4 apps slider

        const h4AppsSlider = new Swiper(".h4-apps-slider", {
          slidesPerView: 4,
          spaceBetween: 24,
          loop: true,
          autoplay: {
            delay: 3000,
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            375: {
              slidesPerView: 2,
              spaceBetween: 20,
            },
            768: {
              slidesPerView: 3,
            },
            992: {
              slidesPerView: 4,
              spaceBetween: 25,
            },
          },
        });
        const h5FeedbackSlider = new Swiper(".h5-feedback-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          loop: true,
          autoplay: {
            delay: 3000,
          },
          navigation: {
            nextEl: ".swiper-next",
            prevEl: ".swiper-prev",
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            1200: {
              slidesPerView: 2,
            },
            1400: {
              slidesPerView: 3,
            },
          },
        });
        const pricingPlanSlider = new Swiper(".pricing-plan-slider", {
          slidesPerView: 4,
          spaceBetween: 24,
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
          pagination: {
            el: ".swiper-pagination",
            type: "bullets",
            clickable: true,
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            992: {
              slidesPerView: 3,
            },
            1400: {
              slidesPerView: 4,
            },
          },
        });
        const emPricingSlider = new Swiper(".em-pricing-slider", {
          loop: true,
          speed: 1500,
          autoplay: {
            delay: 5000,
          },
          pagination: {
            el: ".swiper-pagination",
            type: "bullets",
            clickable: true,
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
              centeredSlides: false,
              spaceBetween: 24,
            },
            992: {
              slidesPerView: 3,
              centeredSlides: true,
              spaceBetween: -25,
            },
          },
        });
        const mnHeroPricingSlider = new Swiper(".mn-hero-pricing-slider", {
          loop: true,
          autoplay: true,
          navigation: {
            nextEl: ".slide-control-next",
            prevEl: ".slide-control-prev",
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
              spaceBetween: 16,
              centeredSlides: false,
            },
            768: {
              slidesPerView: 3,
              spaceBetween: -150,
              centeredSlides: true,
            },
          },
        });
        const mnChattingSlider = new Swiper(".mn-chatting-slider", {
          loop: true,
          autoplay: true,
          slidesPerView: 3,
          centeredSlides: true,
          direction: "vertical",
        });
        const mnFeatureSlider = new Swiper(".mn-feature-slider", {
          autoplay: true,
          loop: true,
          spaceBetween: 24,
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        });
        const mnFeedbackSlider = new Swiper(".mn-feedback-slider", {
          slidesPerView: 1,
          autoplay: true,
          speed: 700,
          loop: true,
          spaceBetween: 24,
          pagination: {
            el: ".swiper-pagination",
            type: "bullets",
            clickable: true,
          },
        });
        const hm7HeroSlider = new Swiper(".hm7-hero-slider", {
          slidesPerView: 1,
          autoplay: true,
          loop: true,
          speed: 700,
          effect: "fade",
          fadeEffect: {
            crossFade: true,
          },
          navigation: {
            nextEl: ".hm7-hero-slider-next",
            prevEl: ".hm7-hero-slider-prev",
          },
        });
        const hm7ApplicationSlider = new Swiper(".hm7-application-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          autoplay: true,
          loop: true,
          speed: 700,
          navigation: {
            nextEl: ".hm7-app-slide-next",
            prevEl: ".hm7-app-slide-prev",
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            992: {
              slidesPerView: 3,
            },
            1200: {
              slidesPerView: 2,
            },
            1400: {
              slidesPerView: 3,
            },
          },
        });
        const hm7FeedbackSlider = new Swiper(".hm7-feedback-slider", {
          slidesPerView: 1,
          autoplay: true,
          loop: true,
          spaceBetween: 24,
          speed: 800,
          navigation: {
            nextEl: ".hm7-feedback-next",
            prevEl: ".hm7-feedback-prev",
          },
        });
        const cmpPricingSlider = new Swiper(".cmp-pricing-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          speed: 800,
          navigation: {
            nextEl: ".cmp-pricing-prev",
            prevEl: ".cmp-pricing-next",
          },
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        });
        var tooltipTriggerList = [].slice.call(
          document.querySelectorAll('[data-bs-toggle="tooltip"]')
        );
        var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
          return new bootstrap.Tooltip(tooltipTriggerEl);
        });
        const dd_feedback_slider = new Swiper(".dd-feedback-slider", {
          slidesPerView: 2,
          spaceBetween: 24,
          autoplay: true,
          speed: 700,
          loop: true,
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            1200: {
              slidesPerView: 2,
            },
          },
        });
        const hm10_feedback_slider = new Swiper(".hm10-feedback-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          autoplay: true,
          speed: 700,
          loop: true,
          breakpoints: {
            0: {
              slidesPerView: 1,
            },
            768: {
              slidesPerView: 2,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        });
        const ops_slider = new Swiper(".ops-slider", {
          slidesPerView: 3,
          spaceBetween: 24,
          autoplay: true,
          speed: 700,
          loop: true,
          navigation: {
            nextEl: ".ops-slider-btn.btn-next",
            prevEl: ".ops-slider-btn.btn-prev",
          },
          breakpoints: {
            0: {
              slidesPerView: 2,
            },
            576: {
              slidesPerView: 3,
            },
            768: {
              slidesPerView: 4,
            },
            1200: {
              slidesPerView: 3,
            },
          },
        }); //Accordion

        $(".hm2-accordion .accordion-header a").each(function () {
          $(this).on("click", function () {
            $(this)
              .parents(".accordion")
              .find(".show")
              .parents(".acoridion-item")
              .addClass("active");
          });
        }); //notice bar close

        $(".notice-close").on("click", function () {
          $(".notice-wrapper").slideUp();
          $(".notice-bar").slideUp();
          $("body").css("overflow", "auto");
        });
        $(".notice-toggle").on("click", function () {
          $(".notice-wrapper").toggleClass("active");

          if ($(".notice-wrapper").hasClass("active")) {
            $("body").css("overflow", "hidden");
          } else {
            $("body").css("overflow", "auto");
          }
        });
      }); //video popup

      $(".vps-video-popup").magnificPopup({
        type: "iframe",
      }); //counterup

      $(".counter").counterUp({
        delay: 10,
        time: 1000,
      }); //countdown timer

      $(".countdown-timer").each(function () {
        var $data_date = $(this).data("date");
        $(this).countdown({
          date: $data_date,
        });
      }); //data center

      $(".mn-data-center .data-center-pointer").each(function () {
        $(this).on("mouseenter", function () {
          $(this)
            .parents(".mn-data-center")
            .find("a.active")
            .removeClass("active");
          $(this).addClass("active");
        });
      }); //pricing switch

      $(".crm-monthly").each(function () {
        $(this).on("click", function () {
          $(this)
            .parents(".crm-pricing-switch-wrapper")
            .find(".crm-checkbox-switch")
            .prop("checked", false);
        });
      });
      $(".crm-yearly").each(function () {
        $(this).on("click", function () {
          $(this)
            .parents(".crm-pricing-switch-wrapper")
            .find(".crm-checkbox-switch")
            .prop("checked", true);
        });
      });
      $(".crm-pricing-switch").each(function () {
        $(this).on("click", function () {
          var isBoxChecked = $(this)
            .find(".crm-checkbox-switch")
            .is(":checked");

          if (isBoxChecked !== true) {
            $(this).parents(".table").find(".crm_monthly_price").show();
            $(this).parents(".table").find(".crm_yearly_price").hide();
          } else {
            $(this).parents(".table").find(".crm_monthly_price").hide();
            $(this).parents(".table").find(".crm_yearly_price").show();
          }
        });
      });
      $(window).on("scroll", function () {
        var offsetTop = $(window).scrollTop();

        if (offsetTop > 150) {
          $(".scrolltop-btn").fadeIn();
        } else {
          $(".scrolltop-btn").fadeOut();
        }

        var scrollBarPosition = $(window).scrollTop();

        if (scrollBarPosition > 80) {
          $("header").addClass("sticky-header");
        } else {
          $("header").removeClass("sticky-header");
        }
      }); //Sticky Header

      jQuery(window).on("load", function () {
        var feedBack = document.querySelectorAll(".feedback-wrapper");

        if (feedBack.length > 0) {
          var elem = document.querySelector(".feedback-massonry");
          var msnry = new Masonry(elem, {
            itemSelector: ".col-lg-4",
            columnWidth: 1,
          });
        }

        $(".loader-wrap").fadeOut(); //Price range slider

        $(".range-slider").slider({
          min: 1,
          max: 6,
          value: 2,
        });
        var rangeInput = $("#vps_range_slider input");
        var checkValue = rangeInput.val(); //vps 1 value

        if (checkValue <= 1) {
          $(".vps_value").hide();
          $(".vps_1_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_1").addClass("active");
        } else if (checkValue <= 2) {
          $(".vps_value").hide();
          $(".vps_2_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_2").addClass("active");
        } else if (checkValue <= 3) {
          $(".vps_value").hide();
          $(".vps_3_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_3").addClass("active");
        } else if (checkValue <= 4) {
          $(".vps_value").hide();
          $(".vps_4_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_4").addClass("active");
        } else if (checkValue <= 5) {
          $(".vps_value").hide();
          $(".vps_5_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_5").addClass("active");
        } else if (checkValue <= 6) {
          $(".vps_value").hide();
          $(".vps_6_value").show();
          $(".vps_label").removeClass("active");
          $(".vps_label_6").addClass("active");
        }

        rangeInput.on("change", function () {
          checkValue = $(this).val();

          if (checkValue <= 1) {
            $(".vps_value").hide();
            $(".vps_1_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_1").addClass("active");
          } else if (checkValue <= 2) {
            $(".vps_value").hide();
            $(".vps_2_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_2").addClass("active");
          } else if (checkValue <= 3) {
            $(".vps_value").hide();
            $(".vps_3_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_3").addClass("active");
          } else if (checkValue <= 4) {
            $(".vps_value").hide();
            $(".vps_4_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_4").addClass("active");
          } else if (checkValue <= 5) {
            $(".vps_value").hide();
            $(".vps_5_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_5").addClass("active");
          } else if (checkValue <= 6) {
            $(".vps_value").hide();
            $(".vps_6_value").show();
            $(".vps_label").removeClass("active");
            $(".vps_label_6").addClass("active");
          }
        });
        var rangeTooltip = $("#vps_range_slider .tooltip");

        if (rangeTooltip.length > 0) {
          var tooltipOffset = rangeTooltip.attr("style").match(/\d+/g);
          var labelPosition = tooltipOffset[0];
          $(".price-slider-wrapper .vps_labels span.active").css({
            marginLeft: tooltipOffset[0] - 2 + "%",
          });
          rangeInput.on("change", function () {
            var tooltipOffset = rangeTooltip.attr("style").match(/\d+/g);
            $(".price-slider-wrapper .vps_labels span.active").css({
              marginLeft: tooltipOffset[0] - 2 + "%",
            });
          });
        } // init Isotope

        var $isotop_filter_items = $(".gh-filter-items").isotope({
          // options
        }); // filter items on button click

        $(".gh-filter-controls").on("click", "button", function () {
          var filterValue = $(this).attr("data-filter");
          $isotop_filter_items.isotope({
            filter: filterValue,
          });
        }); //replace active class

        $(".gh-filter-controls button").each(function () {
          $(this).on("click", function () {
            $(this)
              .parents(".gh-filter-controls")
              .find("button.active")
              .removeClass("active");
            $(this).addClass("active");
          });
        }); //data center filter

        var $dtc_grid = $(".dtc-grid").isotope({}); // filter items on button click

        $(".data-center-filter-btns").on("click", "button", function () {
          var filterValue = $(this).attr("data-filter");
          $dtc_grid.isotope({
            filter: filterValue,
          });
        });
        $(".data-center-filter-btns button").each(function () {
          $(this).on("click", function () {
            $(this).parent().find("button.active").removeClass("active");
            $(this).addClass("active");
          });
        }); //showing notice bar

        setTimeout(function () {
          $(".notice-bar").slideDown();
        }, 500);
      }); // Contact form

      if ($("#contactForm").length) {
        $("#contactForm").on("submit", function (event) {
          if (event.isDefaultPrevented()) {
            // handle the invalid form...
            submitMSG(false, "#contact");
          } else {
            // everything looks good!
            event.preventDefault();
            submitContactForm();
          }
        });
      }

      function submitContactForm() {
        // Initiate Variables With Form Content
        var name = $('#contactForm input[name="name"]').val();
        var email = $('#contactForm input[name="email"]').val();
        var phone = $('#contactForm input[name="phone"]').val();
        var subject = $('#contactForm input[name="subject"]').val();
        var message = $('#contactForm textarea[name="message"]').val(); // Ajax call

        if (name && email && message) {
          $.ajax({
            type: "POST",
            url: "libs/contact-form-process.php",
            data: {
              name: name,
              email: email,
              phone: phone,
              subject: subject,
              message: message,
            },
            success: function success(text) {
              if (text == "success") {
                $("#contactForm")[0].reset();
                submitMSG(true, "#contact");
              } else {
                submitMSG(false, "#contact");
              }
            },
          });
        } else {
          submitMSG(false, "#contact");
        }
      } // Showing message

      function submitMSG(valid, parentSelector) {
        if (valid) {
          $(parentSelector + " .message-box")
            .removeClass("d-none")
            .addClass("d-block ");
          $(parentSelector + " .message-box div")
            .removeClass("alert-danger")
            .addClass("alert-success")
            .text("Form submitted successfully");
        } else {
          $(parentSelector + " .message-box")
            .removeClass("d-none")
            .addClass("d-block ");
          $(parentSelector + " .message-box div")
            .removeClass("alert-success")
            .addClass("alert-danger")
            .text("Found error in the form. Please check again.");
        }
      }
    })(jQuery, document);
  </script>
</svelte:head>

<div class="app">
  <div class="body-overlay" />

  <!--scrolltop button -->
  <button class="scrolltop-btn"><i class="fa-solid fa-angle-up" /></button>
  <!--preloader start-->
  <!-- <div class="loader-wrap">
    <div class="preloader">
        <div id="handle-preloader" class="handle-preloader">
            <div class="animation-preloader">
                <div class="spinner"></div>
                <div class="txt-loading">
                    <span data-text-preloader="H" class="letters-loading">H</span>
                    <span data-text-preloader="O" class="letters-loading">O</span>
                    <span data-text-preloader="S" class="letters-loading">S</span>
                    <span data-text-preloader="T" class="letters-loading">T</span>
                    <span data-text-preloader="I" class="letters-loading">I</span>
                    <span data-text-preloader="M" class="letters-loading">M</span>
                </div>
            </div>
        </div>
    </div>
  </div> -->
  <div class="main-wrapper">
    <Notice />
    <Header />

    <main>
      <slot />
    </main>

    <Footer />
  </div>
</div>

<style>
</style>
