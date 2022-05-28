<template>
  <h1>{{ message }}</h1>
</template>

<script lang="ts">
interface IData {
  message: string
}

export default {
  name: 'TheHeader',
  data(): IData {
    return {
      message: 'Zdarova )'
    }
  }
}
</script>
