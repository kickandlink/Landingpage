<template>
  <section class="hero is-white is-fullheight is-paddingless">
    <div class="hero-head is-paddingless">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item" href="../">
              <img src="@/assets/img/Logo.png" alt="Logo">
            </a>
          </div>
        </div>
      </nav>
    </div>

    <div class="hero-body is-paddingless">
      <div class="container has-text-centered is-multiline">
        <div class="column">
          <h1 class="title is-size-3">Le Match Parfait</h1>
          <h2
            class="subtitle is-size-6"
          >Avec Kick & Link, Nous offrons à nos joueurs de rugby semi-pro plus de visibilité face aux meilleurs clubs, grâce à leurs CVs sportifs et professionnels, et pour les clubs, un large choix de joueurs est garanti.</h2>
          <img style="width: 500px;" src="@/assets/img/draw.png" alt="Kick and Link">
        </div>
        <div class="columns">
          <div class="column grow">
            <h1 class="title is-spaced">Plus de visibilité, CV sportif & pro</h1>
            <h2 class="subtitle">L'offre parfaite pour toi</h2>
            <a
              href="https://kickandlink.typeform.com/to/nP1jdL"
              class="button is-primary is-medium"
            >Pour les Joueurs</a>
          </div>
          <div class="column grow">
            <h1 class="title is-size-3 is-spaced">Un large choix de joueurs</h1>
            <h2 class="subtitle">Un meilleur recrutement</h2>
            <a
              href="https://kickandlink.typeform.com/to/X6j5wE"
              class="button is-black is-medium"
            >Pour les Clubs</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";

export default {
  components: {
    AppLogo
  }
};
</script>

<style>
</style>

