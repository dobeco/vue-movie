<template>
  <div id="main">
	  <Header title="喵喵影院"/>
	  <TabBar/>
 
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import TabBar from '@/components/TabBar.vue'
export default {
  name: 'cinema',
  components: {
	Header,
	TabBar
  }
}
</script>

<style scoped>

</style>

