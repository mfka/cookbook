<template>
  <div class="container">
    <span>{{ message }}</span>
  </div>
</template>

<script lang="ts">
export default {
  setup () {
    const message:string = 'This is a message'

    return {
      message
    }
  }
}
</script>
