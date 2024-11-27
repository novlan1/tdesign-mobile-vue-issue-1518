<template>
  moible popup
  <Popup v-model="visible" placement="bottom" attach="#teleported" style="padding: 100px" />
</template>

<script lang="ts" setup>
import { ref, onMounted } from 'vue';
import { Popup } from 'tdesign-mobile-vue';
const isLoaded = ref(false);
const visible = ref(true)

onMounted(() => {
    isLoaded.value = true;
});
</script>
