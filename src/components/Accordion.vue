<script setup>
import { ref } from 'vue';
import ArrowDown from './ArrowDown.vue';

  const props = defineProps({
    title: { type: String, required: true },
    ariaTitle: { type: String, required: true }
  });
  const showPanel = ref(false);
  const togglePanel = (event) => {
    showPanel.value = !showPanel.value;
  }
</script>

<template>
  <div class="panel">
    <button @click.prevent="togglePanel" class="accordion-button">
      {{ title }}
      <ArrowDown></ArrowDown>
    </button>
    <div class="content" v-if="showPanel">
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.accordion-button {
    font-family: 'Roboto condensed', sans-serif;
    display: flex;
    flex: row;
    border-bottom: 1px solid #e5e5e5;
    padding-bottom: 5px;
}
 
  .content {
    padding: 10px;
  }
</style>