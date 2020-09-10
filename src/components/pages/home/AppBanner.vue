<template>
  <div class="box-shadow">
    <a class="download-app-image d-flex" href="#">
      <img class="img-fluid" src="@/assets/images/panel/app-get-banner.png" />
    </a>
    <div class="download-app-text">Shop better, download the Platt App today</div>
  </div>
</template>

<script>
export default {
  name: "AppBanner",
};
</script>

<style scoped>
img {
  min-width: 700px;
}
div {
  overflow: hidden;
}
a {
  justify-content: flex-end;
}
.download-app-text {
  background-color: #fff;
  text-align: center;
  padding: 1em;
  font-weight: bold;
}
.download-app-image {
  background-color: #fff;
}
</style>