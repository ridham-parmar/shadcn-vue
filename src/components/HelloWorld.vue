<script setup>
import { ref } from 'vue'
// import Button from '@/components/ui/button/Button.vue'
import { Button } from '@/components/ui/button'
import { AlertDialog } from '@/components/ui/alert-dialog';
import Alert from '@/components/Alert.vue';

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="flex flex-col">
    <h1>{{ msg }}</h1>

    <div class="card">
      <!-- <button type="button" @click="count++">count is {{ count }}</button> -->
      <Button type="button" variant="destructive" @click="count++">Count is {{ count }}</Button>

      <p>
        Edit
        <code>components/HelloWorld.vue</code> to test HMR
      </p>
    </div>
    <h1 class="select-none">Ridham</h1>
    <p>
      Check out
      <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank">create-vue</a>, the official Vue + Vite
      starter
    </p>
    <p>
      Learn more about IDE Support for Vue in the
      <a href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support" target="_blank">Vue Docs Scaling up
        Guide</a>.
    </p>
    <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>

    <Alert />
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.user-select {
  user-select: none;
}
</style>
