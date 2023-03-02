<script>
import AppHeader from "./components/AppHeader.vue"
import AppContent from "./components/AppContent.vue"
import AppIcons from "./components/AppIcons.vue"

export default {
  components: {
    AppHeader,
    AppContent,
    AppIcons
  }
}

</script>

<template>
  <AppHeader />
  <AppContent />
  <AppIcons />
</template>

<style scoped></style>
