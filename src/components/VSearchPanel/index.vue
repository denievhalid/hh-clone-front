<template>
  <div class="search">
    <div class="search__inner inner">
      <form class="search__form">
        <v-form-group>
          <v-form-control placeholder="Профессия, должность или компания" />
          <v-button primary>Найти</v-button>
        </v-form-group>
      </form>
    </div>
  </div>
</template>

<script>
import VButton from "../VButton";
import VFormControl from "../VFormControl";
import VFormGroup from "../VFormGroup";

export default {
  components: { VButton, VFormControl, VFormGroup },
};
</script>

<style lang="scss">
.search {
  background: #fafafa;
  padding: 20px 0;

  &__form {
    display: block;
    width: 770px;
  }

  button {
    width: 101px;
  }
}
</style>
