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

<style lang="scss">
@import "@/assets/css/global-vars.scss";

body {
  margin: 0;
  background-color: #ededed;
  font-family: Arial, Helvetica, sans-serif;
}

.row {
  max-width: 960px;
  margin: 1.5em auto;
}

.text-center {
  text-align: center;
}

.box-shadow {
  box-shadow: 2px 2px 5px #999;
}

.d-flex {
  display: flex;
}
h1,
h2 {
  letter-spacing: 0.15em;
}
.text-green {
  color: #009642;
}
.col-half {
  flex: 50%;
}
.col-third {
  flex: 33.33%;
}
.col-quarter {
  flex: 25%;
}
.col-sixth {
  flex: 16.66%;
}

.img-fluid {
  width: 100%;
}

@media (max-width: $break1) {
  .row {
    margin: 1.5em 0.75em;
  }
  .break1-hide {
    display: none;
  }
}
</style>
