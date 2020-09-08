<template>
  <header>
    <div class="row header-row">
      <img src="@/assets/images/logo.png" />
      <HeaderIcons />
    </div>
    <div class="row header-row">
      <SearchBar />
    </div>
  </header>
</template>

<script>
import SearchBar from "./SearchBar";
import HeaderIcons from "./HeaderIcons";

export default {
  name: "AppHeader",
  components: {
    SearchBar,
    HeaderIcons,
  },
};
</script>

<style scoped>
header {
  background-color: #008733;
  padding: 15px;
}

.header-row {
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}
</style>