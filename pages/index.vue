<template>
  <section class="container-fluid">
    <div>
      <navbar/>
      <app-logo/>
      <h1 class="title">
        Nuxt-PWA
      </h1>
      <h2 class="subtitle">
        Nuxt-PWA App by Alif Setyakurniawan
      </h2>
    </div>
    <Meals/>
    <Categories/>
    <Country/>
    <p class="footer">&copy;2020 Nuxt-PWA by Alif Setyakurniawan.</p>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Navbar from '~/components/Navbar.vue'
import Country from '~/components/Country.vue'
import Categories from '~/components/Category.vue'
import Meals from '~/components/Meals.vue'

export default {
  components: {
    AppLogo,
    Navbar,
    Country,
    Categories,
    Meals
  }
}
</script>

<style>
.container-fluid {
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 30px;
}

.links {
  padding-top: 15px;
}

.footer {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  margin-top: 100px;
  margin-bottom: 50px;
  color: #526488;
}
</style>

