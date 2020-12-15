<template>
  <Header title="Remember Me" />
  <ResourceList />
</template>

<script>
import Header from './components/Header.vue'
import ResourceList from './components/ResourceList.vue'

export default {
  name: 'App',
  components: {
    Header,
    ResourceList
  }
}
</script>
