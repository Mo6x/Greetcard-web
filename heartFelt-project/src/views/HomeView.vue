<script setup>
import NavbarSection from "../components/LandingPage/NavbarSection.vue";
import NavbarItems from "../components/LandingPage/NavbarItems.vue";
import HeroSection from "../components/LandingPage/HeroSection.vue";
import verifedCompanies from "../components/LandingPage/verifedCompanies.vue";
import PersonalCard from "../components/LandingPage/PersonalCard.vue";
import GetGiftCard from "../components/LandingPage/GetGiftCard.vue";
import ChooseHeartfelt from "../components/LandingPage/ChooseHeartFelt.vue";
</script>


<template>
  <Hearder class="header">
    <NavbarSection  />
    <NavbarItems />
    <HeroSection />
    <verifedCompanies />
    <PersonalCard />
    <GetGiftCard />
    <ChooseHeartfelt />
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