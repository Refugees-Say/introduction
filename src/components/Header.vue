<template>
  <div class="header">
    <h2>The Resettlement Service</h2>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.header {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: 60px;
  background-color: #336699;
  color: #fff;
  h2 {
    text-align: center;
    font-weight: 400;
  }
}
</style>
