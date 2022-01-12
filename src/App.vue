<template>
  <div>
    <v-header />
    <v-search-panel />
  </div>
</template>

<script>
import VHeader from "./components/VHeader";
import VSearchPanel from "./components/VSearchPanel";

export default {
  components: { VHeader, VSearchPanel },
  mounted() {
    document.title =
      "Работа в Москве, поиск персонала и публикация вакансий - hh.ru";
  },
};
</script>
