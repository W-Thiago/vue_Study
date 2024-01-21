<template>
  <TheHeader></TheHeader>
  <HelloWorld msg="Thiago" />
</template>

<style></style>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TheHeader from './components/TheHeader.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TheHeader
  }
}
</script>
