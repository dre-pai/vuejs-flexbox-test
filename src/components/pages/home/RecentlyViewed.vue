<template>
  <div href="#" class="box-shadow d-flex" id="recently-viewed">
    <div class="d-flex" id="recently-viewed-text-container">
      <div class="col-half">Recently Viewed</div>
      <div class="col-half text-green d-flex" id="recently-viewed-view-all">View All</div>
    </div>
    <div class="d-flex" id="recently-viewed-image-container">
      <div class="col-third">
        <img class="img-fluid" src="@/assets/images/recent/11.png" />
      </div>
      <div class="col-third">
        <img class="img-fluid" src="@/assets/images/recent/22.png" />
      </div>
      <div class="col-third">
        <img class="img-fluid" src="@/assets/images/recent/22.png" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RecentlyViewed",
};
</script>

<style lang="scss" scoped>
#recently-viewed {
  flex-direction: column;
  background-color: #fff;
  height: 100%;
}
#recently-viewed-text-container {
  font-size: 1.1em;
  flex: 1;
  font-weight: bold;
  padding: 0.75em 0.5em;
}

#recently-viewed-view-all {
  justify-content: flex-end;
}

#recently-viewed-image-container img {
  padding: 1em;
  box-sizing: border-box;
}
</style>