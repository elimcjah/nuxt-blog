<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Elijah MAC
      </h1>
      <h2 class="subtitle">
        Software Engineer
      </h2>
      <h3 class="home-boulder">
        Boulder, Colorado
      </h3>
      <div class="links">
        <a
          href="https://github.com/Elijah-VGW"
          target="_blank"
          class="button--grey"
        >
          Github Profile
        </a>
        <a
          href="https://www.linkedin.com/in/elimcjah/"
          target="_blank"
          class="button--grey"
        >
          LinkedIn Profile
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
  import Logo from '~/components/Logo.vue'

  export default Vue.extend({
    components: {
      Logo
    }
  })
</script>

<style>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-size: 3rem;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 400;
    font-size: 2.5rem;
    color: #526488;
    padding-bottom: 5px;
  }

  .home-boulder {
    font-weight: 300;
    font-size: 2rem;
    color: #526488;
    padding-bottom: 5px;
  }

  .links {
    padding-top: 15px;
  }
</style>
