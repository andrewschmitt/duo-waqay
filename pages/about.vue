<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        Duo Waqay
      </h1>
      <h2 class="subtitle">
        Website for musical group Duo Waqay
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
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
