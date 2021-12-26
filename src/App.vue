<script setup>
import Nav from './components/nav.vue'
import Hero from './components/hero.vue'
import Rewards from './components/rewards.vue'
import Discover from './components/discover.vue'
import Transfer from './components/transfer.vue'
import Manage from './components/manage.vue'
import HappyCustomers from './components/happyCustomers.vue'
import Footer from './components/footer.vue'

</script>

<template>
  <div class="container mx-auto px-10">
  <Nav></Nav>

  <Hero></Hero>

  <Rewards></Rewards>

  <Discover></Discover>
  </div>

  <Transfer></Transfer>

  <Manage></Manage>

  <HappyCustomers></HappyCustomers>

  <Footer></Footer>
</template>

<style>

</style>
