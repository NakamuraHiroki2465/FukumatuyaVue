<template>
  <div id="app">
    <TopHeader v-if="!loading"></TopHeader>
      <router-view></router-view>
    <TopFooter v-if="!loading"></TopFooter>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style scoped lang="scss">
@import '@/assets/variables.scss';
#app{
  width:100%;
}

</style>
