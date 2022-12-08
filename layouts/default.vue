<template>
  <div>
    <Header />
    <a href="/vans_iletisim">
      <div id="vans-feedback-tab-area">ONLINE DESTEK</div>
    </a>
    <div id="container">
      <div id="home">
        <div class="w1380">
          <Hero />
          <Videobanner />
          <Productbanner />
          <Haberler />
        </div>
        <Koleksiyon />
        <Homearea />
      </div>
    </div>
    <Footer />
  </div>
</template>
<script>
import Header from "../components/header.vue";
import Hero from "../components/hero.vue";
import Videobanner from "../components/videobanner.vue";
import Productbanner from "../components/productbanner";
import Haberler from "../components/haberler.vue";
import Koleksiyon from "../components/koleksiyon.vue";
import Homearea from "../components/homearea.vue";
import Footer from "../components/footer.vue";

export default {
  name: "IndexPage",
  components: {
    Header,
    Hero,
    Videobanner,
    Productbanner,
    Haberler,
    Koleksiyon,
    Homearea,
    Footer,
  },
};
</script>
