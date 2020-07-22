<template>
  <div class="child">
    <slot></slot>
  </div>
</template>

<script>
import { inject } from 'vue';
import { instance } from './Parent.vue';

export default {
  name: 'Child',
  setup() {
    inject(instance);
  }
}
</script>
