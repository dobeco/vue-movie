<template>
      <div id="main">
	  <Header title="我的喵喵"/>
	  <TabBar/>
 
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import TabBar from '@/components/TabBar.vue'
export default {
  name: 'mine',
  components: {
	Header,
	TabBar
  }
}
</script>