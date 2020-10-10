<template>
  <div>
    <cmtbox :id="$route.params.id"></cmtbox>
    <div>ffffff</div>
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
