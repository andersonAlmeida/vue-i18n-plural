<template>
  <q-page class="flex flex-center">
    {{ t("general.adult", 2) }}
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    />
  </q-page>
</template>

<script setup>
import { useI18n } from "vue-i18n";

const { t } = useI18n();
</script>
