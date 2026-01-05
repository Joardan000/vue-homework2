<template>
  <header>
    <Header/>
  </header>
  <main>
    <Hero/>
    <Delivery/>
    <Details/>
    <Products/>
    <Download/>
    <Ask/>
  </main>
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Delivery from "./components/Delivery.vue";
import Details from "./components/Details.vue";
import Products from "./components/Products.vue";
import Download from "./components/Download.vue";
import Ask from "./components/Ask.vue";
export default {
  components: {
    Header,
    Hero,
    Delivery,
    Details,
    Products,
    Download,
    Ask
  }
}
</script>