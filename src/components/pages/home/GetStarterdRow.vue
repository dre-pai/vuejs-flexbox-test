<template>
  <div class="box-shadow d-flex" id="get-started-row">
    <div class="col-half">
      <img class="img-fluid" src="@/assets/images/platt-plus.png" />
    </div>
    <div class="col-half text-center text-container d-flex">
      <div class="get-started-text get-started-text-lg">Get Started Today</div>
      <div class="get-started-text">
        Become a
        <span class="text-green">Platt Plus</span>
        Member.
      </div>
      <div>
        <ButtonLink text="Learn More" link="#" />
      </div>
    </div>
  </div>
</template>

<script>
import ButtonLink from "@/components/ui/ButtonLink";
export default {
  name: "GetStartedRow",
  components: {
    ButtonLink,
  },
};
</script>

<style lang="scss" scoped>
#get-started-row {
  background-color: #fff;
}
.col-half {
  padding: 3em 5em;
}
.text-container {
  flex-direction: column;
  justify-content: center;
}
.get-started-text {
  font-size: 1.25em;
  font-weight: bold;
}

.get-started-text-lg {
  font-size: 1.5em;
}
</style>