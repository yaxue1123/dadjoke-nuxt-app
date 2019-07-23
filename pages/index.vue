<template>
  <div class="container">
    <div>
     <h2>Welcome to the dad joke app.</h2>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

 export default {
  head() {
    return {
      title: 'Welcome to the dad joke app.',
      meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Best place for dad jokes'
      }]
    } 
  }
}
</script>
