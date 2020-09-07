<template>
  <div id="app">
    <AppHeader />
    <AppHome />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "@/components/layout/header/AppHeader";
import AppHome from "@/components/pages/home/AppHome";
import AppFooter from "@/components/layout/footer/AppFooter";

export default {
  components: {
    AppHeader,
    AppFooter,
    AppHome,
  },
};
</script>

<style>
body {
  margin: 0;
  background-color: #ededed;
}
.row {
  max-width: 960px;
  margin: 0 auto;
}
.text-center {
  text-align: center;
}
</style>
