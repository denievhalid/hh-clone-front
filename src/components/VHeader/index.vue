<template>
  <header class="header">
    <div class="header__top">
      <div class="header__inner"></div>
    </div>
    <div class="header__bottom">
      <div class="header__inner inner">
        <!-- Логотип -->
        <v-logo />
        <!-- Главное меню -->
        <v-main-menu />
      </div>
    </div>
  </header>
</template>

<script>
import VLogo from "../VLogo";
import VMainMenu from "../VMainMenu";

export default {
  components: { VLogo, VMainMenu },
};
</script>

<style lang="scss">
.header {
  &__top {
    height: 40px;
  }

  &__bottom {
    background-color: #222324;

    .inner {
      height: 80px;
    }
  }

  &__inner {
    display: flex;
    align-items: center;
  }

  &__logo {
    margin-right: 30px;
  }
}
</style>
