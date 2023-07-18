<template>
  <div id="app">
  <TheHeader/>
    <DynamicMarketResponseBlock/>
  </div>
</template>

<script>
import TheHeader from "@/components/TheHeader";
import DynamicMarketResponseBlock from "@/components/DynamicMarketResponseBlock";

export default {
  name: 'App',
  components: {
    TheHeader,
    DynamicMarketResponseBlock,
  }
}
</script>

<style lang="sass">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap')
*
  box-sizing: border-box

#app
  background-color: var(--main-bg-color)
  min-height: 100vh
  color: var(--main-text-color)
body
  margin: 0
  font-family: Poppins, sans-serif

img
  object-fit: contain
</style>
