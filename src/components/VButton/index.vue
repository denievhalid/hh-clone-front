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
  appearance: none;
  -moz-appearance: none;
  -webkit-appearance: none;
  font-size: 14px;
  user-select: none;
  white-space: nowrap;
  background: transparent;
  border: 1px solid transparent;
  cursor: pointer;

  &--primary {
    color: #fff;
    border-color: #1785e5;
    background-color: #1785e5;
  }

  &:hover {
    border-color: #167ed8;
    background-color: #167ed8;
  }
}
</style>
