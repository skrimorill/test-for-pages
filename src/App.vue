<template>
  <child type='submit' @click='handleClick'/>
</template>

<script>
import child from './components/child.vue'

export default {
  name: 'App',
  components: {
    child
  },
  methods: {
    handleClick () {
      console.log('click')
    }
  }
}
</script>