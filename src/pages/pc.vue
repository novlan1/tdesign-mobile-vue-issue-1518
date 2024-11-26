<template>
  pc popup
  <Popup v-if="isLoaded" attach="#teleported" style="padding: 100px" />
</template>

<script lang="ts" setup>
import { ref, onMounted } from 'vue';
import { Popup } from 'tdesign-vue-next';
const isLoaded = ref(false);
onMounted(() => {
    isLoaded.value = true;
});
</script>
