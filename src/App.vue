<template>
  <div id="app">{{ message }}</div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      message: "Hello Stranger!"
    };
  }
};
</script>

<style lang="scss">
#app {
  font-size: 40px;
  color: #1aa7b9;
}
</style>