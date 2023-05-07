<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <TestItem :parent-msg="msg" />
</template>

<script>
import TestItem from '../components/TestItem.vue'
export default {
  data() {
    return {
      msg: '外面msg'
    }
  },
  components: {
    TestItem
  }
}
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
