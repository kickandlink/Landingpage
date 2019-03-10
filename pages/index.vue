<template>
  <div class="container">
    <hero/>
    <partners/>
    <services/>
    <testimonials/>
    <kickandlink/>
    <contact/>
  </div>
</template>

<script>
import Hero from "~/components/Hero.vue";
import Partners from "~/components/Partners.vue";
import Services from "~/components/Services.vue";
import Testimonials from "~/components/Testimonials.vue";
import Kickandlink from "~/components/Kickandlink.vue";
import Contact from "~/components/Contact.vue";

export default {
  components: {
    Hero,
    Partners,
    Services,
    Testimonials,
    Kickandlink,
    Contact
  }
};
</script>

<style>
</style>