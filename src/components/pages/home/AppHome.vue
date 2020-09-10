<template>
  <div id="home-container">
    <AppMenu />
    <div class="row break1-hide">
      <h2 class="text-center">Product Markets</h2>
      <MarketsRow />
    </div>
    <div class="row">
      <GetStarterdRow />
    </div>
    <div class="row d-flex banner-row-halves">
      <div class="col-half">
        <TodaysDeals />
      </div>
      <div class="col-half">
        <RecentlyViewed />
      </div>
    </div>
    <div class="tile-row-quarters row d-flex">
      <ImageTile
        class="col-quarter"
        imageName="super-tool-day.png"
        text="Super Tool Day & Dynamic Data Day"
        link="#"
      />
      <ImageTile
        class="col-quarter"
        imageName="ic_location_b.png"
        text="Branch Locations"
        link="#"
      />
      <ImageTile class="col-quarter" imageName="ic_helpcenter.png" text="Help Center" link="#" />
      <ImageTile class="col-quarter" imageName="ic_platt-u.png" text="Platt University" link="#" />
    </div>
    <div class="row">
      <AppBanner />
    </div>
  </div>
</template>

<script>
import AppMenu from "@/components/layout/menu/AppMenu";
import MarketsRow from "./MarketsRow";
import GetStarterdRow from "./GetStarterdRow";
import TodaysDeals from "./TodaysDeals";
import RecentlyViewed from "./RecentlyViewed";
import AppBanner from "./AppBanner";
import ImageTile from "@/components/ui/ImageTile";
export default {
  name: "AppHome",
  components: {
    AppMenu,
    MarketsRow,
    GetStarterdRow,
    TodaysDeals,
    RecentlyViewed,
    AppBanner,
    ImageTile,
  },
};
</script>

<style lang="scss">
.tile-row-quarters a {
  margin: 0 25px;

  &:first-child {
    margin-left: 0;
  }
  &:last-child {
    margin-right: 0;
  }
}

.tile-row-quarters .image-tile-wrap {
  padding: 2em 2em 1em;
}

.banner-row-halves .col-half {
  margin: 0 0.75em;
  &:first-child {
    margin-left: 0;
  }
  &:last-child {
    margin-right: 0;
  }
}
</style>