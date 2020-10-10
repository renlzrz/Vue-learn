<template>
  <div>
    <cmtbox :id="$route.params.id"></cmtbox>
    <div>22222222</div>
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
