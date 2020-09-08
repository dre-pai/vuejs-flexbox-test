<template>
  <div id="markets-row">
    <ImageTile class="col-sixth" imageName="datacomm.png" text="DataComm" link="#" />
    <ImageTile class="col-sixth" imageName="hvac.png" text="HVAC" link="#" />
    <ImageTile class="col-sixth" imageName="industrial.png" text="Industrial" link="#" />
    <ImageTile class="col-sixth" imageName="lighting.png" text="Lighting" link="#" />
    <ImageTile class="col-sixth" imageName="energy.png" text="Energy Efficiency" link="#" />
    <ImageTile class="col-sixth" imageName="utility.png" text="Utility" link="#" />
  </div>
</template>

<script>
import ImageTile from "@/components/ui/ImageTile";

export default {
  name: "MarketsRow",
  components: { ImageTile },
};
</script>

<style lang="scss" scoped>
a {
  margin: 0 10px;
  &:first-child {
    margin-left: 0;
  }
  &:last-child {
    margin-right: 0;
  }
}
#markets-row {
  display: flex;
}
</style>