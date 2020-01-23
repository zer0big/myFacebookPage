<template>
  <div>
    <hearder></hearder>
    <leftbody></leftbody>
    <rightbody></rightbody>
    <footercomponent></footercomponent>
  </div>
</template>
<script>
import hearder from "./components/header.vue";
import leftbody from "./components/leftbody.vue";
import rightbody from "./components/rightbody.vue";
import footercomponent from "./components/footercomponent.vue";
export default {
  components: {
    hearder,
    leftbody,
    rightbody,
    footercomponent
  }
};
</script>
<style >
</style>
