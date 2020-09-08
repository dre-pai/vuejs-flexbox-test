<template>
  <div>
    <a class="d-flex" href="#">
      <img src="@/assets/images/icons/black/ic_comment.png" />Live Help
    </a>
  </div>
</template>

<script>
export default {
  name: "LiveHelpButton",
};
</script>

<style scoped>
a {
  color: #000;
  background: #fff;
  text-decoration: none;
  font-weight: bold;
  padding: 0.75em 3.5em;
  font-size: 1.15em;
  border-radius: 25px;
  font-size: 0.85em;
  align-items: center;
  justify-content: center;
}
img {
  padding-right: 8px;
}
div {
  display: inline-block;
}
</style>