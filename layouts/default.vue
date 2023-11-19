<script setup lang="ts">
const { t } = useI18n({
  useScope: 'local'
})
</script>

<template>
  <div>
    <p>{{ t("welcome") }}</p>
    <slot />
  </div>
</template>

<i18n lang="yaml">
en:
  welcome: "Welcome"
fr:
  welcome: "Bienvenue"
</i18n>
