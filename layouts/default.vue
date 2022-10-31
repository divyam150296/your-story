<template>
  <div>
    <TheHeader @sidenavToggle="displaySidebar=!displaySidebar"/>
    <TheSidenav :show="displaySidebar" @close="displaySidebar =!displaySidebar" />
    <nuxt/> 
  </div>
</template>

<script>
import TheHeader from '~/components/Navigation/TheHeader'
import TheSidenav from '~/components/Navigation/TheSidenav'

export default {
  components: {
    TheHeader,
    TheSidenav
  },
  data () {
    return {
      displaySidebar: false
    }
  }
}
</script>


<style>
html {
  font-family: 'Open Sans', sans-serif;
}
body {
  margin: 20px;
}
</style>

