<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    
    <!-- NAV -->
    <nav class="navbar">
      <h1 class="navbar__header">duo WAQAY</h1>
    </nav>

    <!-- MAIN CONTENT -->
    <main>

      <!-- HERO IMG -->
      <section class="hero">
        <header>
          <h1 class="hero__header">duo WAQAY</h1>
        </header>
        <!-- <p><i>[wah-kaie]</i></p> -->
      </section>

      <!-- DEFINITION AND EVENTS -->
      <section class="main-content">
        <div class="container">
          <div class="row">
            <!-- DEFINITION -->
            <div class="col-md-5 col-lg-4">
              <div class="definition">
                <h2 class="definition__header">WAQAY</h2>
                <i class="definition__linguistic">[wah-kaie]</i>
                <ol class="definition__list">
                  <li>The cry of a musical instrument</li>
                  <li>A Latin guitar duo based in the Ottawa-Gatineau region. Providing entertainment for private and corporate events, parties, and more.</li>
                </ol>
                <div class="definition__button"><button class="btn">Book Now</button></div>
              </div>
            </div>

            <!-- EVENTS -->
            <div class="col-md-7 col-lg-8">
              <div class="events">
                <h2 class="events__header">EVENTS</h2>
                <div class="event__schedule">
                  <table class="table table-hover">
                    <tr>
                      <td class="event__date align-middle">Oct 5, 2018</td>
                      <td class="event__location align-middle"><a href="https://pressed-ottawa.com/">Pressed</a></td>
                      <td class="event__button align-middle"><button class="btn">TICKETS <font-awesome-icon icon="ticket-alt" /></button></td>
                    </tr>

                    <tr>
                      <td class="event__date align-middle">Nov 3, 2018</td>
                      <td class="event__location align-middle">25 Anniversary Galla of Eco-Latino News Paper</td>
                      <td class="event__button align-middle"><button class="btn">TICKETS <font-awesome-icon icon="ticket-alt" /></button></td>
                    </tr>

                    <tr>
                      <td class="event__date align-middle">November 19th, 2018</td>
                      <td class="event__location align-middle">OGS Young Artists Series</td>
                      <td class="event__button align-middle"><button class="btn">TICKETS <font-awesome-icon icon="ticket-alt" /></button></td>
                    </tr>
                  </table>
                </div>
              </div>
            </div>

            <!-- VIDEO EMBED -->
            <div class="video-frame">
              <iframe class="video-frame__embedded" width="100%" height="500px" src="https://www.youtube.com/embed/m_vZ4JLnfDI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
            </div>

            <!-- ABOUT US --> 
            <div class="col">
              <div class="about">
                  <h2 class="about__header">ABOUT</h2>
                  <p>Based in the Ottawa-Gatineau Region, this Latin guitar duo has been quickly establishing a reputation for their unique and symbiotic connectivity on stage. Guitarists Gabriela Iznardo and Alejandro Vega have wowed and delighted audiences with their signatre blend of Latin American and Spanish rhythms.</p>
                  <p>Making themselves available for venues, private and corporate events,  reunions, and dinner parties in Ottawa, Montreal, and Toronto, Duo Waqay will provide a fusion of guitar and entertainment to suit any venue.</p>
              </div>
            </div>


          </div>
        </div>
      </section>
    </main>
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
    background-color: #eee;

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
    padding: 17% 25% 40%;

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
      text-align: center; 
      padding: 1rem;
    }
  }

  /**
  * CONCERTS / TOUR DATES
  */
  .events {
    padding-top: 2em;
    
  }

  /**
  * EMBEDDED VIDEO
  */
  .video-frame {
    padding: 30% 0;
    width: 100%;
    position: relative;
    margin: 2rem 0;

    &__embedded {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      bottom: 0;
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
      padding: 18% 30% 40%;

      &__header {
        font-size: 3rem;
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
