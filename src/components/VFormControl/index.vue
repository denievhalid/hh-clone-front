<template>
  <input
    class="form-control"
    type="text"
    :placeholder="placeholder"
    :value="value"
  />
</template>

<script>
export default {
  props: {
    placeholder: String,
    value: String,
  },
};
</script>

<style lang="scss">
.form-control {
  width: 100%;
  height: 40px;
  padding: 0 12px;
  margin: 0;
  color: #303233;
  border-radius: 4px;
  border: 1px solid #d4d7d9;
  font-size: 14px;
  display: block;
  background-color: #fff;
  line-height: 38px;
  outline: none;

  &:hover {
    border-color: #959799;
  }

  &:focus {
    border-color: #1785e5;
    box-shadow: inset 0 2px 1px rgb(48 50 51 / 17%);
  }
}
</style>
