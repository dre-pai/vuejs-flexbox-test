<template>
  <div>
    <input placeholder="What are you looking for?" />
    <img src="@/assets/images/icons/black/ic_search.png" draggable="false" />
  </div>
</template>

<script>
export default {
  name: "SearchBar",
};
</script>

<style scoped>
input {
  width: 100%;
  border-radius: 4px;
  border: solid 1px #eee;
  padding: 6px 10px;
  line-height: 24px;
  box-sizing: border-box;
  outline: none;
}

div {
  position: relative;
  margin-top: 15px;
  width: 100%;
}

img {
  position: absolute;
  top: 50%;
  right: 15px;
  transform: translateY(-50%);
}
</style>