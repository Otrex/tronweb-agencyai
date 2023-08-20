<template>
  <div>
    <BaseMainHeader/>
    <index-hero />
    <frame-50 />
    <heyjv />
    <WelcomeAgencyAI />
    <YourCustomer />
    <FrameBoundGroupOne />
    <!-- <FrameContest /> -->
    <the-funnel />
    <huge-affiliates />
    <need-anything-sect />
    <copy-right />
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: false,
});

useHead({
  title: "AgencyAI JV",
  link: [
    {
      rel: "image_src",
      href: window.location.origin + '/meta/WebsitePreview.png'
    },
    { rel: "apple-touch-icon", href: "/apple-touch-icon.png" },
        { rel: "icon", type: "image/png", href: "/favicon-32x32.png" },
        { rel: "icon", type: "image/png", href: "/favicon-16x16.png" },
        { rel: "manifest", href: "/site.webmanifest" },
        { rel: "preconnect", href: "https://rsms.me/" },
        { rel: "stylesheet", href: "https://rsms.me/inter/inter.css" },
  ],
  meta: [
    {
      name: 'og:description',
      hid: 'og:description',
      content: "Launching Aug. 31st"
    },
    {
      name: 'og:title',
      hid: 'og:title',
      content: "AgencyAI JV"
    },
    {
      name: 'og:image',
      hid: 'og:image',
      content: window.location.origin + '/meta/WebsitePreview.png'
    }
  ]
})
</script>

<style></style>
