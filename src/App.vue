<template>
  <div>
    <v-header />
    <v-search-panel />
    <div class="content inner">
      <div class="content__left">
        <v-my-events />
      </div>
      <div class="content__right">
        <v-recommended />
      </div>
    </div>
  </div>
</template>

<script>
import VHeader from "./components/VHeader";
import VMyEvents from "./components/VMyEvents";
import VRecommended from "./components/VRecommended";
import VSearchPanel from "./components/VSearchPanel";

export default {
  components: { VHeader, VMyEvents, VRecommended, VSearchPanel },
  mounted() {
    document.title =
      "Работа в Москве, поиск персонала и публикация вакансий - hh.ru";
  },
};
</script>
