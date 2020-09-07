<template>
  <div id="markets-row">
    <ImageTile imageName="datacomm.png" text="DataComm" link="#" />
    <ImageTile imageName="hvac.png" text="HVAC" link="#" />
    <ImageTile imageName="industrial.png" text="Industrial" link="#" />
    <ImageTile imageName="lighting.png" text="Lighting" link="#" />
    <ImageTile imageName="energy.png" text="Energy Efficiency" link="#" />
    <ImageTile imageName="utility.png" text="Utility" link="#" />
  </div>
</template>

<script>
import ImageTile from "@/components/ui/ImageTile";

export default {
  name: "MarketsRow",
  components: { ImageTile },
};
</script>

<style scoped>
#markets-row {
  display: flex;
}

a {
  flex-basis: 16.66%;
  margin: 0 10px;
}
</style>