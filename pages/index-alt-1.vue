<template>
  <main>
    <Type1HeroT1 />
    <Type1HelpYouT1 />
    <SharedOurServices />
    <SharedBenefits />
    <SharedAboutUs
      showEclipse
      bgColor="bg-[#F5F7FF]"
      :image="'/images/about_team.png'"
      :header-text-color="'bg-clip-text text-transparent bg-gradient-to-b from-[#AB3ADD] via-[#AB3ADD] to-[#3B57F4]'"
      :button-bg="'bg-[#AB3ADD]'"
    />
    <SharedReviews :header-text-color="'text-[#AB3ADD]'" />
  </main>
</template>

<script setup lang="ts"></script>

<style></style>
