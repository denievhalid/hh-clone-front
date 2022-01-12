<template>
  <div class="form-group">
    <slot />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.form-group {
  display: flex;

  & > * {
    border-radius: 0;
  }
}
</style>
