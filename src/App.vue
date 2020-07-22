<template>
  <Parent><Child></Child></Parent>
</template>

<script>
import Parent from './components/Parent.vue'
import Child from './components/Child.vue'

export default {
  name: 'App',
  components: { Parent, Child }
}
</script>
