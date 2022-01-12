<template>
  <button class="btn" :class="classNames">
    <slot />
  </button>
</template>

<script>
export default {
  props: {
    primary: {
      type: Boolean,
      default: false,
    },
  },

  computed: {
    classNames() {
      return {
        "btn--primary": this.primary,
      };
    },
  },
};
</script>

<style lang="scss">
.btn {
  font-size: 14px;
  user-select: none;
  white-space: nowrap;
  background: transparent;
  border: 0;

  &--primary {
    color: #fff;
    border-color: #1785e5;
    background-color: #1785e5;
  }
}
</style>
