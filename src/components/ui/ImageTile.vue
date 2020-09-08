<template>
  <a :href="`${link}`" class="box-shadow">
    <div class="image-tile-wrap">
      <img class="img-fluid" :src="require(`@/assets/images/${imageName}`)" />
    </div>
    <div class="tile-text-container text-center">{{text}}</div>
  </a>
</template>

<script>
export default {
  name: "ImageTile",
  props: {
    imageName: {
      type: String,
      required: true,
    },
    text: {
      type: String,
      required: true,
    },
    link: {
      type: String,
    },
  },
};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  background-color: #fff;
  color: #000;
  font-weight: bold;
  font-size: 1.2em;
  display: flex;
  flex-direction: column;
}

.image-tile-wrap {
  overflow: hidden;
  height: 70%;
}

.tile-text-container {
  height: 30%;
  padding: 1em 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>