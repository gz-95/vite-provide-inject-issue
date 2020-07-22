<template>
  <div class="parent">
    <slot></slot>
  </div>
</template>

<script>
import { provide } from 'vue';

export const instance = Symbol();

export default {
  name: 'Parent',
  setup() {
    provide(instance, {});
  }
}
</script>
