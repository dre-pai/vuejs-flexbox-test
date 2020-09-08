<template>
  <a :href="`${link}`">{{text}}</a>
</template>

<script>
export default {
  name: "ImageTile",
  props: {
    imageName: {
      type: String,
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

<style scoped>
a {
  padding: 0.5em 3em;
  font-size: 1.15em;
  border-radius: 25px;
  text-decoration: none;
  color: #000;
  background: #ededed;
  margin: 1em 0;
  display: inline-block;
}
</style>