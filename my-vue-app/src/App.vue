<script>
import AppTitle from "./components/AppTitle.vue"
import JumboMain from "./components/JumboMain.vue"
import Copyright from "./components/Copyright.vue"
export default {
  components: {
    AppTitle,
    JumboMain,
    Copyright
  }
}
</script>

<template>
  <JumboMain></JumboMain>
  <AppTitle></AppTitle>
  <Copyright></Copyright>
</template>

<style>

</style>