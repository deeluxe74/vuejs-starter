<template>
  <div id="app">
    <v-icon>{{ icons.mdiAccount }}</v-icon>
    <router-view />
  </div>
</template>

<script>
import { mdiAccount } from '@mdi/js'
export default {
  data() {
    return {
      icons: {
        mdiAccount
      }
    }
  }
}
</script>

<style lang="scss"></style>
