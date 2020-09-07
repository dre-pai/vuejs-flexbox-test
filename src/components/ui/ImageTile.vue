<template>
  <a :href="`${link}`">
    <img :src="require(`@/assets/images/${imageName}`)" />
    <div class="text-center">
      <span>{{text}}</span>
    </div>
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
  background-color: #fff;
  color: #000;
  font-weight: bold;
  font-size: 1.2em;
}
div {
  position: relative;
  background-color: #fff;
  height: 75%;
}

span {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
img {
  width: 100%;
}
</style>