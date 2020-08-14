<template>
  <div id="app" class="app">
    <the-desktop-nav id="desktop-nav" />
    <the-mobile-nav id="mobile-nav" />
     <div class="view-container">
       <router-view/>      
     </div>
     <div class="nav">
       <router-link to="about">About</router-link>
       <router-link to="contact">Contact</router-link>
     </div>
  </div>
</template>

<script>
  import TheDesktopNav from '@/components/TheDesktopNav'
  import TheMobileNav from '@/components/TheMobileNav' 

  export default {
    components: {
      TheDesktopNav,
      TheMobileNav
    }  
  }
</script>

<style lang="sass" scoped>
  .app
    background-color: #E0E2DB
  .view-container
    width: 79vw
    padding: 1.5em
    margin-left: 20vw
    box-sizing: border-box 
    min-height: 100vh

  #mobile-nav 
    display: none

  @media screen and (max-width: 1096px)
    .view-container
      width: 100%
      margin-left: 0 
    #desktop-nav
      display: none  
    #mobile-nav
      display: flex
</style>
