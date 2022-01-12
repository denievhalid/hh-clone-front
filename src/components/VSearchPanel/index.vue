<template>
  <div class="search">
    <div class="search__inner inner">
      <form class="search__form">
        <v-form-control placeholder="Профессия, должность или компания" />
      </form>
    </div>
  </div>
</template>

<script>
import VFormControl from "../VFormControl";

export default {
  components: { VFormControl },
};
</script>

<style lang="scss">
.search {
  &__form {
    width: 770px;
    margin: 20px 0;
  }
}
</style>
