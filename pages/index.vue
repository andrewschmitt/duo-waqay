<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    
    <!-- NAV -->
    <!-- <nav class="navbar">
      <h1 class="navbar__header">duo WAQAY</h1>
    </nav> -->

    <!-- MAIN CONTENT -->
    <main>

      <!-- HERO IMG -->
      <section class="hero">
        <header>
          <!-- <h1 class="hero__header">duo WAQAY</h1> -->
        </header>
        <!-- <p><i>[wah-kaie]</i></p> -->
        <div class="hero__chevron"><fa :icon="['fas', 'chevron-down']" /></div>
      </section>

      <!-- DEFINITION AND EVENTS -->
      <section class="main-content">
        <div class="container">
          <div class="row">
            <!-- DEFINITION -->
            <div class="col-md-5">
              <div class="definition">
                <h2 class="definition__header">WAQAY</h2>
                <i class="definition__linguistic">[wah-kaie]</i>
                <ol class="definition__list">
                  <li>The cry of a musical instrument</li>
                  <li>A Latin guitar duo based in the Ottawa-Gatineau region. Providing entertainment for private and corporate events, parties, and more.</li>
                </ol>
                <div class="definition__button"><button class="btn btn--red">BOOK YOUR EVENT</button></div>
              </div>
            </div>

            <!-- EVENTS -->
            <div class="col-md-7">
              <div class="events">
                <h2 class="events__header">NEXT EVENT</h2>
                <div class="events__schedule">
                  <!-- <table class="table table-hover">
                    <tr>
                      <td class="event__date align-middle">March 5, 2019</td>
                      <td class="event__location align-middle"><a href="https://bistroalegria.ca/">Bistro Alégria</a></td>
                      <td class="event__button align-middle"><button class="btn btn--red disabled" disabled>TICKETS</button></td>
                    </tr>

                    <tr>
                      <td class="event__date align-middle">May 29, 2019</td>
                      <td class="event__location align-middle">National Arts Centre</td>
                      <td class="event__button align-middle"><button class="btn btn--red disabled" disabled>TICKETS</button></td>
                    </tr>
                  </table> -->
                  <div class="row">
                    <div class="col"><img src="@/assets/img/event-thumbnail.jpeg" alt="" class="img-fluid"></div>
                    <div class="col">
                      <h3>Bistro Alégria</h3>
                      <p>May 29, 2019</p>
                      <button class="btn btn--red disabled" disabled>BUY TICKETS</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- LATEST ALBUM STUFF -->
        <div class="album ">
          <div class="container">
            <div class="album__header-block">
              <h2 class="album__header">ALBUM</h2>
              <i class="album__subheader">Latin Roots</i>
            </div>
            
            <div class="row">
              <div class="col-md-6">
                <img src="http://cdbaby.name/i/r/iralb01552705_large.jpg" alt="" class="img-fluid album__img">
              </div>
              <div class="col-md-6">
                <!-- <div class="album__soundtrack">song</div> -->
                <div class="album__description">
                  <p>Known for their “unique” and “symbiotic connectivity” while playing together, Duo Waqáy has perfected their duality over the course of the past nine years. Guitarists Gabriela Iznardo and Alejandro Vega have been performing alongside one another since early adolescence and are both graduates of the University of Ottawa for Performance Guitar, one holding a Bachelor’s degree and the other a Master’s degree. While growing up playing together, they developed an inseparable bond; connected by their love for guitar and their latin heritage, they quickly discovered their passion for Latin American and Spanish rhythms. The fusion of Alejandro’s Cuban heritage and Gabriela’s Peruvian and Argentinian background lead to the creation of a unique sound which sparks energy and creativity into the hearts of their audience. It is this very fusion of culture which created their name “[Duo] “Waqáy”, a Quechuan word that means “The cry and timbre of a musical instrument”.</p> 
                  <p>Although they have been playing together for almost a decade, 2017 marked the debut of their professional performance career and brought some new and captivating repertoire which they are so very excited to share with their audiences.</p>
                  <!-- <button class="btn btn--white">Buy Now!</button> -->
                  <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                    <input type="hidden" name="cmd" value="_s-xclick">
                    <table>
                    <tr><td><input type="hidden" name="on0" value="Album: Latin Roots"></td></tr>
                    </table>
                    <input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----">
                    <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
                    <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- VIDEO EMBED -->
        <div class="video-frame">
          <iframe class="video-frame__embedded" width="100%" height="500px" src="https://www.youtube.com/embed/c2DmQUYctPc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
        </div>

        <!-- ABOUT US --> 
        <div class="about about--brown">
          <div class="container">
            <div class="row">
              <div class="col">
                <div>
                  <h2 class="about__header">ABOUT</h2>
                  <p>Based in the Ottawa-Gatineau Region, this Latin guitar duo has been quickly establishing a reputation for their unique and symbiotic connectivity on stage. Guitarists Gabriela Iznardo and Alejandro Vega have wowed and delighted audiences with their signatre blend of Latin American and Spanish rhythms.</p>
                  <p>Making themselves available for venues, private and corporate events,  reunions, and dinner parties in Ottawa, Montreal, and Toronto, Duo Waqay will provide a fusion of guitar and entertainment to suit any venue.</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- UPCOMING EVENTS -->
        <div class="container">
          <div class="row">
            <div class="col">
              <div class="events">
                <h2 class="events__header events__header--red">EVENTS</h2>
                <div class="event__schedule">
                  <table class="table table-hover">
                    <tr>
                      <td class="event__date align-middle">March 5, 2019</td>
                      <td class="event__location align-middle"><a href="https://bistroalegria.ca/">Bistro Alégria</a></td>
                      <td class="event__button align-middle"><button class="btn btn--red disabled" disabled>TICKETS <fa :icon="['fas', 'fa-ticket']" /></button></td>
                    </tr>

                    <tr>
                      <td class="event__date align-middle">May 29, 2019</td>
                      <td class="event__location align-middle">National Arts Centre</td>
                      <td class="event__button align-middle"><button class="btn btn--red">TICKETS <font-awesome-icon icon="ticket-alt" /></button></td>
                    </tr>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="contact">
          <div class="container">
            <h3 class="title">CONTACT</h3>
            <p>We'd love to hear from you! Please drop us a line if you've any query related to our products or services.</p>
            <div class="content">
              <form name="contact" method="post" data-netlify="true">
                <div class="form-group">
                  <input type="hidden" name="form-name" value="contact" />
                  <label for="inputContact">Name</label>
                  <input class="form-control" id="inputContact" placeholder="John Doe" name="name">
                </div>
                <div class="form-group">
                  <label for="exampleInputEmail1">Email address</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email" name="email">
                  <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                </div>
                <!-- <div class="form-group form-check">
                  <input type="checkbox" class="form-check-input" id="exampleCheck1">
                  <label class="form-check-label" for="exampleCheck1">Check me out</label>
                </div> -->
                <div class="form-group">
                  <label for="exampleFormControlTextarea1">Message</label>
                  <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="message"></textarea>
                </div>
                <button class="form-button btn btn--red" type="submit" value="Send message">SEND</button>
              </form>
            </div>
          </div>
        </div>


        
      </section>
    </main>
    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col footer__divide-line">
            <h3 class="footer__header">Follow duo WAQAY</h3>
            <div class="media-tags d-flex justify-content-center align-items-center">
              <a href="https://www.facebook.com/duowaqay/" target="_blank" class="fa fa--facebook"><fa :icon="['fab', 'facebook-f']" /></a>
              <a href="https://www.youtube.com/channel/UCmMtA54V0IBvaJgBVHPgK6Q" target="_blank" class="fa fa--youtube"><fa :icon="['fab', 'youtube']" /></a>
              <a href="https://www.instagram.com/duowaqay/" target="_blank" class="fa fa--instagram"><fa :icon="['fab', 'instagram']" /></a>
            </div>
          </div>
          <div class="col">
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
// import 'bootstrap'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss">

  // COLORS
  $orange: #e77431;
  $red: #b5302b;
  $brown: #503431;
  $teal: #55a393;
  $green: #4b6c57;

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  // remove margin on body
  body {
    margin: 0px;
  }

  /**
  * NAVBAR
  */
  .navbar {
    background-color: $orange;

    &__header {
      margin: 0;
      padding: 0.3rem;
    }
  }


  /**
  * HERO IMG
  */
  .hero {
    background-image: url('~assets/img/hero-img.jpg');
    background-size: cover;
    background-position: center;
    padding: 17% 25% 40%;
    position: relative;

    &__header {
      font-size: 2rem;
      text-align: center;
      color: #fff;
      background-color: black;
      // margin: 0; 
    }

    &__definition {
      font-size: 1rem;
    }

    &__chevron {
      display: block;
      position: absolute;
      bottom: 10%;
      left: 0px;
      font-size: 3rem;
      color: #fff;
      text-align: center;
      width: 100vw;
    }
  }

  /**
  * MAIN CONTENT
  */
  .main-content {
    // background-image: #eee;
  }
  
  /**
  * DEFINITION
  */
  .definition {
    padding-top: 2rem;

    &__header {
      margin: 0;
    }

    &__linguistic {
       font-size: 1.3em;
      font-weight: 700;
      color: #999;
    }

    &__button {
      // text-align: center; 
      padding: 1rem;
    }
  }

  /**
  * CONCERTS / TOUR DATES
  */
  .events {
    padding-top: 2em;

    &__header {

      &--red {
        color: $red;
      }
    }

    &__schedule {
      margin-bottom: 2rem;
    }
    
  }

  /**
  * ALBUM
  */
  .album {
    background-color: #333;
    color: #fff;
    padding: 2rem 0;

    // ELEMENTS
    &__header-block {
      display: block;
      margin: auto;
      width: 175px;
      margin-bottom: 2rem;
    }

    &__header {
      margin: 0;
    }

    &__subheader {
      font-size: 1.3em;
      font-weight: 700;
      color: #999;
    }

    &__img {
      display: block;
      margin: auto;
      margin-bottom: 1rem;
    }

    &__soundtrack {
      background-color: #eee;
      height: 4rem;
    }

    &__description {
      // padding: 1rem 0;
    }

    // Modifiers
    &--brown {
      background-color: $brown;
    }

    &--red {
      background-color: $red;
    }
  }

  /**
  * EMBEDDED VIDEO
  */
  .video-frame {
    padding: 30% 0;
    width: 100%;
    position: relative;
    // margin: 2rem 0;

    &__embedded {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      bottom: 0;
    }
  }

  /**
  * ABOUT
  */
  .about {
    padding: 2rem 0;
    background-color: #333;
    color: #fff;

    &--brown {
      background-color: $brown;
    }

    &--red {
      background-color: $red;
    }
  }

  /**
  * CONTACT
  */
  .contact {
    margin: 1rem auto; 
  }

  /**
  * mc-signup
  */
  .mc-signup {
    // margin: 1rem auto;
    color: #fff;
  }

  /**
  * Footer
  */
  .footer {
    // min-height: 10rem;
    background-color: #333;
    padding: 2rem 0;

    //
    &__header {
      color: #fff;
      text-align: center;
    }

    // 
    &__divide-line {
      // border-right: 1px solid #fff;
    }
  }
  
  /**
  * social media
  */
  .fa {
    // padding: 15px;
    font-size: 1.5rem;
    width: 50px;
    line-height: 50px;
    text-align: center;
    text-decoration: none;
    margin: .5rem;
    border-radius: 50%;
    border: 2px solid #fff;
    transition: all 0.4s ease;

    &:hover {
      opacity: 0.7;
      color: $orange;
      border: 2px solid $orange;
      transition: all 0.4s ease;
    }
    
    // 
    &--facebook {
      // background-color: #3B5998;
      color: #fff;
    }

    &--youtube {
      // background-color: #bb0000;
      color: #fff;
    }

    &--instagram {
      // background-color: #125688;
      color: #fff;
    }
  }

  .svg-inline--fa {
    vertical-align: -0.18em;
  }
  
  /**
  * button styles
  */
  .btn {
    border-radius: 0px;
  }
  .btn--grey {
    background-color: #ccc;
  }
  .btn--white {
    background-color: transparent;
    color: #fff;
    border: 2px solid #fff;

    &:hover {
      color: #ccc;
    }
  }

  .btn--red {
    color: $red;
    border: 2px solid $red;

    &:hover {
      opacity: .75;
      color: $red;
    }
  }

  .btn--orange {
    color: $orange;
    border: 2px solid $orange;

    &:hover {
      opacity: .75;
      color: $orange;
    }
  }

  /*------------------------------------*\
  #TABLET RESOLUTION
  \*------------------------------------*/
  @media(min-width: 768px) {
    /**
    * HERO IMG
    */
    .hero {
      padding: 17% 30% 40%;

      &__header {
        font-size: 4rem;
      }
    }
  }

  /*------------------------------------*\
  #LAPTOP RESOLUTION
  \*------------------------------------*/
  @media(min-width: 1024px) {
    /**
    * HERO IMG
    */
    .hero {
      padding: 18% 30% 40%;

      &__header {
        font-size: 4rem;
      }
    }
  }

  /*------------------------------------*\
  #LARGE RESOLUTION
  \*------------------------------------*/
  @media(min-width: 1200px) {
    /**
    * HERO IMG
    */
    .hero {
      padding: 18% 30% 40%;

      &__header {
        font-size: 6rem;
      }
    }
  }
</style>
