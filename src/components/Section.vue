<template>
  <div class="section">
    <slot />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section {
  padding-top: 2 * $spacer;
  padding-bottom: 2 * $spacer;
}
</style>