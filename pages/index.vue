<template>
  <div class="container">
    <hero/>
    <partners/>
    <services/>
    <testimonials/>
    <kickandLink/>
    <contact/>
  </div>
</template>

<script>
import Hero from "~/components/Hero.vue";
import Partners from "~/components/Partners.vue";
import Services from "~/components/Services.vue";
import Testimonials from "~/components/Testimonials.vue";
import KickandLink from "~/components/KickandLink.vue";
import Contact from "~/components/Contact.vue";

export default {
  components: {
    Hero,
    Partners,
    Services,
    Testimonials,
    KickandLink,
    Contact
  }
};
</script>

<style>
</style>