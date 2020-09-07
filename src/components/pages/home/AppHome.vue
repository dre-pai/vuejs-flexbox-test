<template>
  <div id="home-container">
    <AppMenu />
    <div class="row">
      <h2 class="text-center">Product Markets</h2>
      <MarketsRow />
    </div>
  </div>
</template>

<script>
import AppMenu from "@/components/layout/menu/AppMenu";
import MarketsRow from "@/components/pages/home/MarketsRow";
export default {
  name: "AppHome",
  components: {
    AppMenu,
    MarketsRow,
  },
};
</script>

<style scoped>
</style>