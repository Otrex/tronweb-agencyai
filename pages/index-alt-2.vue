<template>
  <main>
    <BaseHeaderThree />
    <Type2HeroT2/>
    <Type2HelpYouT2/>
    <SharedOurServices />
    <SharedBenefits />
    <SharedAboutUs :image="'/images/about_team_2.png'" :header-text-color="'text-[#232323]'" :button-bg="'bg-[#3B57F4]'" />
    <SharedReviews :header-text-color="'text-[#000]'" />
  </main>
</template>

<script setup lang="ts">
definePageMeta({
  layout: false,
});
</script>

<style></style>
