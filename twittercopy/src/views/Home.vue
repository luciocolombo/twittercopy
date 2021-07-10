<template>
  <div>
    <Navbar />
    <div class="home row">
      <LeftContent />
      <CentralContent />
      <RightContent />
    </div>
  </div>
</template>

<script>
import LeftContent from "../components/LeftContent.vue";
import CentralContent from "../components/CentralContent.vue";
import RightContent from "../components/RightContent.vue";
import Navbar from "../components/Navbar.vue";
export default {
  name: "Home",
  components: { LeftContent, CentralContent, RightContent, Navbar },
};
</script>
