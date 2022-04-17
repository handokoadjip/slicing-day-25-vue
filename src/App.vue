<template>
  <HeaderComponent />
  <main>
    <router-view />
  </main>
  <FooterComponent />
  <SectionFooterComponent />
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue"
import FooterComponent from "@/components/FooterComponent.vue"
import SectionFooterComponent from "@/components/SectionFooterComponent.vue"

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    SectionFooterComponent
  },
}
</script>

<style>
/* Style Here */
</style>
