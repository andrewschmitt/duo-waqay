<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    
    <!-- NAV -->
    <nav class="navbar navbar-fixed navbar-expand-sm justify-content-between">
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <nuxt-link class="navbar-brand" to="/">duo Waqáy</nuxt-link>
        <div class="navbar-nav">
          <nuxt-link class="nav-item nav-link" to="/about"><strong>About</strong></nuxt-link>
          <a class="nav-item nav-link" href="#">Gallery</a>
          <a class="nav-item nav-link" href="#">Contact</a>
          <a class="nav-item nav-link" href="#">Events</a>
        </div>
        <!-- <form class="form-inline">
          <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form> -->
      </div>
    </nav>

    <!-- MAIN CONTENT -->
    <main>

      <!-- HERO IMG -->
      <section class="hero">
        <header>
          <h1 class="hero__header">duo&nbsp;Waqáy</h1>
          <p class="hero__subheader">Latin Guitar</p>
          <!-- <div class="links text-center mt-4">
            <a
              href="#contact"
              target="_blank"
              class="btn btn--white">Get in touch</a>
            <a
              href="#latest-album"
              target="_blank"
              class="btn btn--white">Latest Album</a>
          </div> -->
        </header>
        <!-- <p><i>[wah-kaie]</i></p> -->
        <!-- <div class="hero__chevron"><fa :icon="['fas', 'chevron-down']" /></div> -->
      </section>

      <!-- main content -->
      <div class="content-block">
        <div class="container">
          <div class="row">
            <div class="col">
              <h2 class="content-block__header">About</h2>
              <div class="row">
                <div class="col-md-7">
                  <!-- <div class="album__soundtrack">song</div> -->
                  <div class="album__description">
                    <p>Known for their “unique” and “symbiotic connectivity” while playing together, Duo Waqáy has perfected their duality over the course of the past nine years. Guitarists Gabriela Iznardo and Alejandro Vega have been performing alongside one another since early adolescence and are both graduates of the University of Ottawa for Performance Guitar, one holding a Bachelor’s degree and the other a Master’s degree. While growing up playing together, they developed an inseparable bond; connected by their love for guitar and their latin heritage, they quickly discovered their passion for Latin American and Spanish rhythms. The fusion of Alejandro’s Cuban heritage and Gabriela’s Peruvian and Argentinian background lead to the creation of a unique sound which sparks energy and creativity into the hearts of their audience. It is this very fusion of culture which created their name “[Duo] “Waqáy”, a Quechuan word that means “The cry and timbre of a musical instrument”.</p> 
                    <!-- <button class="btn btn--white">Buy Now!</button> -->
                  </div>
                </div>
                <div class="col-md-5">
                  <img src="http://cdbaby.name/i/r/iralb01552705_large.jpg" alt="" class="img-fluid album__img">
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Alejandro -->
      <div class="content-block">
        <div class="container">
          <div class="row">
            <div class="col">
              <h2 class="content-block__header">Alejandro</h2>
              <div class="row">
                <div class="col-md-6">
                  <img src="https://cdn.bandmix.ca/bandmix_ca/media/77/77946/267104-p.jpg" alt="" class="img-fluid album__img">
                </div>
                <div class="col-md-6">
                  <!-- <div class="album__soundtrack">song</div> -->
                  <div class="album__description">
                    <p>Alejandro Vega, a native of Cuba, graduated from the Manuel Saumell and Amadeo Roldán Conservatory in Havana. Since the age of fifteen Alejandro has called Ottawa home, and has been an active collaborative and solo artist at music festivals and recitals in the region for the past eight years. He spent several years mentoring young kids at the Suzuki Music School of Ottawa and was endowed with the Kiwanis Club of Vanier Trophy before becoming an undergraduate at the University of Ottawa, during which time he was the recipient of the Ed Honeywell Scholarship for Classical Guitar.</p>
                    <p>A recent graduate from the University of Ottawa where he earned a Masters in Music under the guidance of Patrick Roux, Alejandro has gained experience coaching undergraduate student ensembles as well as instructing students at small music schools in the city. This past summer he was awarded silver medal at the national level competition in Canada representing the Ontario Province for classical guitar.</p>
                    <p>Alejandro has a strong interest in other styles of music, most notably South American genres, Afro-Cuban music and jazz.</p>
                    <p>When not performing with duo Waqáy, Alejandro also teaches music at <a href="https://www.ajvega.com">www.ajvega.com</a></p>
                    <!-- <button class="btn btn--white">Buy Now!</button> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Gabi -->
      <div class="content-block">
        <div class="container">
          <div class="row">
            <div class="col">
              <h2 class="content-block__header">Gabriela</h2>
              <div class="row">
                <div class="col-md-8">
                  <!-- <div class="album__soundtrack">song</div> -->
                  <div class="album__description">
                    <p>Gabriela Iznardo is a Classical guitar teacher and performer who began playing guitar at the age five. Growing up, she followed the Suzuki method with her mother and Peruvian guitarist Graciela Escudero and at the age of eleven continued her studies at the National Capital Suzuki School of Music with Argentinian guitarist Daniel Srugo.</p>
                    <p>While pursuing her undergrad in Classical Guitar Performance, Gabriela also completed intensive teacher trainings to become a certified Suzuki Teacher: Today she is ECC certified and has completed registered Suzuki-Guitar teacher trainings with acclaimed instructors David Madsen and Bill Kossler. Gabriela completed her Bachelor of Music specialized in Guitar Performance at the University of Ottawa in 2016 where she studied under the guidance of renowned Canadian professors Louis Trepanier, Dennis Donegoni and Patrick Roux.</p>
                    <p>When not performing with duo Waqáy, Gabriela owns and teaches the Start Suzuki method at <a href="https://www.startsuzuki.com/">www.startsuzuki.com</a></p>
                    <!-- <button class="btn btn--white">Buy Now!</button> -->
                  </div>
                </div>
                <div class="col-md-4">
                  <img src="https://uocal.uottawa.ca/sites/default/files/styles/260px_width/public/events/media/Gabriela%20Iznardo.jpg" alt="" class="img-fluid album__img">
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>

    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col-sm footer__divide-line">
            <h3 class="footer__header">Follow duo Waqáy</h3>
            <div class="media-tags d-flex justify-content-center align-items-center">
              <a href="https://www.facebook.com/duowaqay/" target="_blank" class="fa fa--facebook"><fa :icon="['fab', 'facebook-f']" /></a>
              <a href="https://www.youtube.com/channel/UCmMtA54V0IBvaJgBVHPgK6Q" target="_blank" class="fa fa--youtube"><fa :icon="['fab', 'youtube']" /></a>
              <a href="https://www.instagram.com/duowaqay/" target="_blank" class="fa fa--instagram"><fa :icon="['fab', 'instagram']" /></a>
            </div>
          </div>
          <div class="col-sm">
            <!-- Begin Mailchimp Signup Form -->
            <div id="mc_embed_signup" class="mc-signup">
              <form action="https://duowaqay.us20.list-manage.com/subscribe/post?u=d016f0f155fab9fd240310503&amp;id=698009c923" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
                <div id="mc_embed_signup_scroll">
                  <h3 class="footer__header">Subscribe to our mailing list</h3>
                  <!-- <div class="indicates-required"><span class="asterisk">*</span> indicates required</div> -->
                  <div class="mc-field-group form-group">
                    <label for="mce-EMAIL">Email Address </label>
                    <input type="email" value="" name="EMAIL" class="required email form-control" id="mce-EMAIL">
                  </div>
                  <div id="mce-responses" class="clear">
                    <div class="response" id="mce-error-response" style="display:none"></div>
                    <div class="response" id="mce-success-response" style="display:none"></div>
                  </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                  <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_d016f0f155fab9fd240310503_698009c923" tabindex="-1" value=""></div>
                  <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button form-button btn btn--white"></div>
                </div>
              </form>
            </div>
            <!--End mc_embed_signup-->
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

// Bootstrap
import 'bootstrap'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss" scoped>
  /**
  * HERO IMG
  */
  .hero {
    height: 50vh;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
  }

  /**
  * CONTENT BLOCK
  */
  .content-block {

    // Elements
    &__header {
      color: #000;
    }

    // MOds
    &--justified-margin {
      // padding-top: 50
    }
  }
  
</style>
