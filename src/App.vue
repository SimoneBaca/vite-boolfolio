<script>
import AppMain from './components/AppMain.vue';
import AppHeader from './components/AppHeader.vue';
export default {
  name: 'App',
  components: {
    AppMain,
    AppHeader

  },
}
</script>
<template>
    <header>
    <AppHeader />
    <router-view></router-view>
  </header>

    <main>
     <!-- <AppMain />-->

    </main>
 
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use 'bootstrap/scss/bootstrap' as *;
</style>