<template>
  <div>
    <section class="banner">
      <VueSlickCarousel v-bind="settings" class="home-slider" style="position: relative; z-index: 10;">
        <template #prevArrow>
          <button class="slick-prev slick-arrow">
            <font-awesome-icon :icon="['fas', 'long-arrow-alt-left']" />
          </button>
        </template>
        <div class="home-slider-content">
          <div class="banner-floating-text ijireHeading">
            <h1 class="wow animate__animated animate__fadeInDown animate__delay-1s side-content">
              IJSREAT
            </h1>
          </div>
          <div class="container position-relative">

            <div class="row justify-content-between">
              <div class="col-lg-12 col-md-12">
                <div class="banner-text  wow animate__animated animate__fadeInDown">
                  <h1 class="heading-title text-center px-lg-5">International Journal of Scientific Research in Engineering & Technology
                  </h1>
                  <p class="banner-sub-content "><span class="essn-content">e-ISSN:2583-1240</span>, Follows UGC-CARE
                    Guidelines
                  </p>
                  <p class="banner-sub-content sub-bold-content">
                    An International Scholarly Open Access Journal, Peer-reviewed, Refereed Journal
                  </p>
                  <p class="banner-sub-content">High Impact factor, Bi-Monthly, Multidisciplinary Journal

                  </p>
                  <p class="banner-sub-content px-lg-5">CrossRef DOI (Digital Object Identifier) allotted to all published
                    papers.
                    Indexed by Google Scholar, Elsevier-Mendeley and many other research databases
                  </p>
                  <div class="row justify-content-center">
                    <div class="banner-button">
                      <a href="http://editorial.fdrpjournals.org/login?journal=2"
                        class="wow animate__animated animate__flipInX animate__delay-1s large-blue-button text-center">SUBMIT YOUR
                        Article</a>
                    </div>
                    <div class="banner-button">
                      <a href="http://editorial.fdrpjournals.org/login?journal=2"
                        class="wow animate__animated animate__flipInX animate__delay-1s large-blue-button">
                        Author Login</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </VueSlickCarousel>
      <div class="shape-01 banner-ellipse">
        <img src="@/assets/Images/ellipse.png" class="wow animate__animated animate__pulse animate__infinite"
          alt="img" />
      </div>
    </section>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";

export default {
  name: "BannerStyle1",
  components: {
    VueSlickCarousel,
  },
  data() {
    return {
      settings: {
        autoplay: false,
        slidesToShow: 1,
        slidesToScroll: 1,
        dots: false,
        infinite: true,
        arrows: true,
        speed: 1000,
      },
    };
  },
};
</script>

<style>
@media screen and (max-width: 991.5px) {
  .banner-image {
    background-image: url("~@/assets/banner/home_banner.png");
    height: 74%;
    background-position-x: 68%;
    background-size: cover;
  }
}


.large-blue-button {
  margin-left: 30px;
}

.banner-text h1 {
  color: rgb(34, 54, 69);
}

.large-blue-button {
  background-color: #d1a614;
  border-radius: 15px;
}

.banner-floating-text h1 {
  color: #e8dfc1;
}

.banner-text h1 {
  color: #d1a614;
}

.banner-button {
  display: flex;
  justify-content: center;
  padding: 16px 0;
}

.sub-bold-content {
  font-weight: bold;

}

.essn-content {
  color: #d1a614;
  font-weight: bold;
  font-style: italic
}

.banner-sub-content {
  margin: 0 !important;
  padding: 12px 0;
  text-align: center !important;
}

.large-blue-button {
  background-color: #d1a614;
  border-radius: 15px;
}



.large-blue-button {
  margin-left: 30px;
}
</style>
