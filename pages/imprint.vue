<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <UPageHeader :title="t('imprint')" />
  <div>
    <ContentDoc path="/imprint" />
  </div>
</template>
