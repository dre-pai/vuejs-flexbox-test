<template>
  <footer>
    <div class="footer-section footer-text-lg">Support Center</div>
    <div class="footer-section">
      <div class="footer-text-lg">800-25-Platt</div>
      <div>800-257-5288</div>
    </div>
    <div class="footer-section footer-text-lg" id="footer-hours">
      <div>4 a.m. - 12 a.m. (pst)</div>
      <div>7 Days a week</div>
    </div>
    <div class="footer-section">
      <LiveHelpButton />
    </div>
    <div class="footer-section">
      <FooterLinks />
    </div>
  </footer>
</template>

<script>
import FooterLinks from "./FooterLinks";
import LiveHelpButton from "./LiveHelpButton";
export default {
  name: "AppFooter",
  components: {
    FooterLinks,
    LiveHelpButton,
  },
};
</script>

<style scoped>
footer {
  background-color: #666;
  color: #fff;
  text-align: center;
  padding: 15px;
}

.footer-text-lg {
  font-size: 1.3em;
}
#footer-hours {
  color: #ccc;
}
.footer-section {
  padding: 10px;
}
</style>