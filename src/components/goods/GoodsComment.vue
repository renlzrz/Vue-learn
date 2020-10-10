<template>
  <div>
    <cmtbox :id="$route.params.id"></cmtbox>
    <div>2追追</div>
  </div>
</template>

<script>
import cmtbox from "../subcomponents/comment.vue";

export default {
  components: {
    cmtbox
  }
};
</script>

<style lang="scss" scoped>

</style>
