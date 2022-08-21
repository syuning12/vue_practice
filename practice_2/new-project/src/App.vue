<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <router-link
            class="nav-link active"
            aria-current="page"
            :to="{
              name: 'home',
            }"
            >Home</router-link
          >
          <router-link
            class="nav-link active"
            aria-current="page"
            :to="{
              name: 'about',
            }"
            >About</router-link
          >
          <router-link
            class="nav-link active"
            aria-current="page"
            :to="{
              name: 'addnewpage',
            }"
            >NewPage</router-link
          >
        </div>
      </div>
    </div>
  </nav>

  <div class="container">
    <router-view />
  </div>

  <!-- {{name}} -->
</template>

<script>
// export default {
//   data () {
//     return {
//       name: process.env.VUE_APP_NAME
//     }
//   }
// }
</script>

<style lang="scss">
@import "bootstrap";
</style>
