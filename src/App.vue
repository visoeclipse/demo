<template>
  <div class="home">
    <topology />
  </div>
</template>

<script>
import topology from "topology-vue";
import "topology-vue/topology-vue.css";

export default {
  components: {
    topology
  },
};
</script>
<style lang="scss">
.home {
  height: calc(100vh - 80px);
}
</style>