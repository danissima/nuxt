<!-- Please remove this file from your project -->
<template>
  <h1>{{ message }}</h1>
</template>

<script lang="ts">
interface IData {
  message: string
}

export default {
  name: 'NuxtTutorial',
  data(): IData {
    return {
      message: 'Здарова )'
    }
  }
}
</script>
