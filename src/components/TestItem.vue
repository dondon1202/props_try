<template>
  <h1>{{ parentMsg }}</h1>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  data() {
    return {
      msg: '內層msg'
    }
  },
  props: ['parentMsg']
}
</script>

<style></style>
