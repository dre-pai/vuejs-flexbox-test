<template>
  <a :href="`${link}`">
    <img :src="require(`@/assets/images/icons/black/${icon}`)" />
    <span>{{text}}</span>
  </a>
</template>

<script>
export default {
  name: "MenuLink",
  props: {
    text: {
      type: String,
      required: true,
    },
    icon: {
      type: String,
      required: true,
    },
    link: {
      type: String,
      required: true,
    },
  },
};
</script>

<style lang="scss" scoped>
a {
  display: flex;
  justify-content: center;
  text-decoration: none;
  padding: 15px 0;
  background-color: #fff;
  transition: all 0.5s;

  &:hover {
    background-color: #eee;
  }
  &:visited {
    color: #000;
  }
}
img {
  margin: auto 0;
  padding-right: 10px;
}
</style>