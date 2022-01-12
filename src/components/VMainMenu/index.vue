<template>
  <ul class="header__menu main-menu">
    <li class="main-menu__item">
      <a class="main-menu__link" href="">Мои резюме</a>
    </li>
    <li class="main-menu__item">
      <a class="main-menu__link" href="">Отклики</a>
    </li>
    <li class="main-menu__item">
      <a class="main-menu__link" href="">Помощь</a>
    </li>
  </ul>
</template>

<script>
export default {};
</script>

<style lang="scss">
.main-menu {
  display: flex;

  &__item {
    & + * {
      margin-left: 20px;
    }
  }

  &__link {
    color: #fff;
    font-size: 16px;
  }
}
</style>
