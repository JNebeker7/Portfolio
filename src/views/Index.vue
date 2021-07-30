<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle" id="banner-gradient">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <div class="brand">
              <h1>Jared R Nebeker</h1>
              <h3>Portfolio / Resume</h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section">

        <div class="container">
          <div class="md-layout">
            <div
              class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center"
            >
              <h2 class="title text-center">Example Designs</h2>
            </div>
          </div>

          <div class="md-layout">
            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box1"></div>
                <a href="https://karamullane.com/" target="_blank">
                <button class="portfolio-btn" >Kara Mullane</button>
                </a>
              </div>

            </div>

            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box2"></div>
                <a href="https://iconicnutritionsupplements.com/" target="_blank">
                <button class="portfolio-btn" >Iconic Nutrition</button>
                </a>
              </div>

            </div>

            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box3"></div>
                <a href="https://infusedreleaf.com/" target="_blank">
                <button class="portfolio-btn" >Infused ReLeaf</button>
                </a>
              </div>

            </div>

            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box4"></div>
                <a href="https://prettykinz.com/" target="_blank">
                <button class="portfolio-btn" >Pretty Kinz</button>
                </a>
              </div>

            </div>

            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box5"></div>
                <a href="https://uncledelspettreats.com/" target="_blank">
                <button class="portfolio-btn" >Uncle Del's</button>
                </a>
              </div>

            </div>

            <div class="md-layout-item md-size-50 md-small-size-100">

              <div class="img-comtainer">
                <div class="box box6"></div>
                <a href="https://beewiseorganics.com/" target="_blank">
                <button class="portfolio-btn" >Bee Wise Organics</button>
                </a>
              </div>

            </div>
          </div>

          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
              <h2 class="title text-center">More websites</h2>
                <a href="https://thereeftanning.com/" target="_blank">
                  <button class="portfolio-btn" >The Reef Tanning</button>
                </a>
                <p>Client wanted this exact layout. I got to explore the wordpress divi library to make it happen. This website is neat
                  in that you can flip the hopepage on its back and it's still indexable -- Tab module.
                </p>
                
                <a href="https://prettykinz.com/" target="_blank">
                  <button class="portfolio-btn" >Pretty Kinz</button>
                </a>
                <p>I like this website because it playes into the logo (theme)(logo) from header to footer. Its one of
                  of my best.
                </p>
            </div>
          </div>
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
              <div class="md-layout">
                <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
                  <h2 class="title text-center">Favorite Example Code</h2>
                </div>
              </div>

              <div class="md-layout" style="text-align: center; margin-bottom: 25px;">
                <div class="md-layout-item">
                  <div class="image-wrapper">
                    <img src="~@/assets/img/doom3.jpg" />
                  </div>
                </div>
              </div>

              <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
                <h4>
                  <a href="https://en.wikipedia.org/wiki/Fast_inverse_square_root" target="_blank">Fast inverse square root</a>
                </h4>
                <p>
                  This is one of my favorite examples that shows how to avoid slow divison operations with an fast algorithm.
                </p>
              </div>

            </div>
          </div>



        </div>
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
              <div class="md-layout">
                <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto text-center">
                  <h2 class="title text-center">Side projects (remote) 05/2021 - Current</h2>
                  <h4>
                    <a href="https://www.projectdiablo2.com/" target="_blank">Project Diablo 2</a>
                  </h4>
                  <p>
                    I'm currently working with the developers of PD2 on creating 2 new websites in Next.js (frontend) + Feathers.js (backend).
                  </p>
                  <p>
                    I'm also working on the launcher for the game. The launcher is built on top of <a href="https://sciter.com/" target="_blank">Sciter</a> (C++ and Typescript)
                  </p>
                </div>
              </div>

            </div>
          </div>

      </div>
    </div>
  </div>
</template>

<script>
import BasicElements from "./components/BasicElementsSection";
import Navigation from "./components/NavigationSection";
import SmallNavigation from "./components/SmallNavigationSection";
import Tabs from "./components/TabsSection";
import NavPills from "./components/NavPillsSection";
import Notifications from "./components/NotificationsSection";
import TypographyImages from "./components/TypographyImagesSection";
import JavascriptComponents from "./components/JavascriptComponentsSection";
import { LoginCard } from "@/components";

export default {
  components: {
    // BasicElements,
    // Navigation,
    // SmallNavigation,
    // Tabs,
    // NavPills,
    // Notifications,
    // TypographyImages,
    // JavascriptComponents,
    // LoginCard
  },
  name: "index",
  bodyClass: "index-page",
  props: {
    image: {
      type: String,
      // default: require("@/assets/img/banner2.jpg")
      default: require("@/assets/img/me.jpg")
    }
  },
  data() {
    return {
      firstname: null,
      email: null,
      password: null,
      leafShow: false
    };
  },
  methods: {
    leafActive() {
      if (window.innerWidth < 768) {
        this.leafShow = false;
      } else {
        this.leafShow = true;
      }
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `linear-gradient(to top, rgba(245, 246, 252, 0.52), rgba(0, 0, 0, 0.73)), url(${this.image})`
      };
    },
    signupImage() {
      return {
        backgroundImage: `url(${this.signup})`
      };
    }
  },
  mounted() {
    this.leafActive();
    window.addEventListener("resize", this.leafActive);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.leafActive);
  }
};
</script>
<style lang="scss">

.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
}

.img-comtainer .box {
  width: 480px;
  height: 480px;
  background-color: #000;
  background-position: top;
  transition: ease-in-out 5s;
  margin-bottom: 25px;
  box-shadow: 0px 2px 18px 0px rgb(0 0 0 / 15%);
}
.img-comtainer .box.box1 {
  background: url("~@/assets/img/Kara.jpg");
  background-size: cover;
}
.img-comtainer .box.box2 {
  background: url("~@/assets/img/Iconic.jpg");
  background-size: cover;
}
.img-comtainer .box.box3 {
  background: url("~@/assets/img/Infused.jpg");
  background-size: cover;
}
.img-comtainer .box.box4 {
  background: url("~@/assets/img/Pretty.jpg");
  background-size: cover;
}
.img-comtainer .box.box5 {
  background: url("~@/assets/img/Uncle.jpg");
  background-size: cover;
}
.img-comtainer .box.box6 {
  background: url("~@/assets/img/Beewise.jpg");
  background-size: cover;
}
.img-comtainer .box.box7 {
  background: url("~@/assets/img/bs.png");
  background-size: cover;
}
.img-comtainer .box:hover {
  background-position: bottom;
}
.portfolio-btn {
  width: 100%;
  border: none;
  padding: 10px 30px 10px 30px;
  font-size: 18px;
  margin-bottom: 10px;
  border-bottom: 1px solid black;
}
.portfolio-btn:hover {
  cursor: pointer;
}


@font-face {
  font-family: "Gothic" !important;
  src: local("Gothic"), url("~@/assets/CenturyGothic.ttf") format("truetype");
}

h1, h2, h3, h4, h5, h6, button, p {
    font-family: "Gothic" !important;
    // font-weight: 400 !important;
}

.title, .card-title, .info-title, .footer-brand, .footer-big h5, .footer-big h4, .media .media-heading {
    // font-family: "Arial" !important;
}

</style>
