<template>
  <div class="d-flex">
    <a class="col-third" href="#">Contact Us</a>
    <a class="col-third" href="#">What's New</a>
    <a class="col-third" href="#">FAQs</a>
  </div>
</template>

<script>
export default {
  name: "FooterLinks",
};
</script>

<style lang="scss" scoped>
div {
  flex-direction: row;
  padding: 1em;
}
a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.15em;
}
</style>