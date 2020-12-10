<template>
  <div class="wrapper-content wrapper-content--fixed">
    <div class="container">
      <Promo />
      <Intro title="My last posts:" />
      <!-- posts -->
    </div>
  </div>
</template>

<script>
import Promo from "@/components/Promo.vue";
import Intro from "@/components/UI/Intro.vue";
export default {
  components: {
    Intro,
    Promo,
  },
};
</script>
