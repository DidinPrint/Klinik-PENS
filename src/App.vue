<template>
 <div class="hero_area">

<div class="hero_bg_box">
  <img src="images/hero-bg.png" alt="">
</div>

<!-- header section strats -->
<header class="header_section">
<Navbar></Navbar>
<router-view/>
</header>
<!-- end header section -->
<!-- slider section -->
<slider></slider>
<!-- end slider section -->
</div>


<!-- department section -->
<department></department>
<!-- end department section -->

<!-- about section -->
<about></about>
<!-- end about section -->

<!-- doctor section -->
<doctor></doctor>
<!-- end doctor section -->

<!-- contact section -->
<contact></contact>
<!-- end contact section -->

<!-- client section -->

<!-- end client section -->
<client></client>
<!-- footer section -->
<Footer></Footer>
<!-- footer section -->

</template>
<script>
import Footer from "@/components/Footer.vue"
import Navbar from "@/components/Navbar.vue"
import slider from "@/components/slider.vue"
import department from "@/components/department.vue"
import about from "@/components/about.vue"
import doctor from "@/components/doctor.vue"
import contact from "@/components/contact.vue"
import client from "@/components/client.vue"
export default {
  name: 'App',
  components: {
    Footer, Navbar,slider,department, about, doctor, contact, client,
  },
}
</script>
<style>

</style>
