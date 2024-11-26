<template>
  <div style="margin-bottom: 20px;">
    pc popup
  </div>
  <Popup content="这是一个弹出框" attach="#teleported">
    <Button variant="outline">触发元素</Button>
  </Popup>
</template>

<script lang="ts" setup>
import { Popup, Button } from 'tdesign-vue-next';

</script>
