<template>
  <div id="menu">
    <div class="menu-row menu-row-full">
      <MenuLink text="Shop all categories" icon="ic_categories.png" link="#" />
    </div>
    <div class="menu-row menu-row-thirds">
      <MenuLink text="My Catalog" icon="ic_playlist_add_check.png" link="#" />
      <MenuLink text="My List" icon="ic_list.png" link="#" />
      <MenuLink text="Live Help" icon="ic_chat.png" link="#" />
    </div>
    <div class="menu-row menu-row-thirds">
      <MenuLink text="PIM" icon="ic_check_circle.png" link="#" />
      <MenuLink text="Account" icon="ic_categories.png" link="#" />
      <MenuLink text="Branch Locations" icon="ic_place.png" link="#" />
    </div>
  </div>
</template>

<script>
import MenuLink from "@/components/layout/menu/MenuLink";
export default {
  name: "AppMenu",
  components: {
    MenuLink,
  },
};
</script>

<style lang="scss" scoped>
$border-color: #c9c9c9;
$border-width: 2px;

.menu-row {
  display: flex;
  a {
    border-bottom: $border-width solid $border-color;
  }
}
.menu-row-thirds a {
  flex-basis: 33.33%;
  &:nth-child(2) {
    border-left: $border-width solid $border-color;
    border-right: $border-width solid $border-color;
  }
}
.menu-row-full a {
  flex-basis: 100%;
  font-weight: bold;
  font-size: 1.1em;
}
</style>