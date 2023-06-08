<script setup>
import NavbarHero from "../components/LandingPage/NavbarHero.vue";
import HeroList from "../components/LandingPage/HeroLists.vue";
import NavbarSection from "../components/LandingPage/NavbarSection.vue";
import verifedCompanies from "../components/LandingPage/verifedCompanies.vue";
import PersonalCard from "../components/LandingPage/PersonalCard.vue";
import GetGiftCard from "../components/LandingPage/GetGiftCard.vue";
</script>


<template>
  <Hearder class="header">
    <NavbarHero  />
    <HeroList />
    <NavbarSection />
    <verifedCompanies />
    <PersonalCard />
    <GetGiftCard />
  </Hearder>
</template>

<style scoped>
  .header{
    width: 100vh;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>