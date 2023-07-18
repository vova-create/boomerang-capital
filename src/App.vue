<template>
  <div>
  <TheHeader/>
    <DynamicMarketResponseBlock/>
    <MarketInfoBlock/>
    <DefineBlock/>
    <FeatureList/>
  </div>
</template>

<script>
import TheHeader from "@/components/TheHeader";
import DynamicMarketResponseBlock from "@/components/DynamicMarketResponseBlock";
import MarketInfoBlock from "@/components/MarketInfoBlock";
import DefineBlock from "@/components/DefineBlock";
import FeatureList from "@/components/FeatureList";

export default {
  name: 'App',
  components: {
    TheHeader,
    DynamicMarketResponseBlock,
    MarketInfoBlock,
    DefineBlock,
    FeatureList
  }
}
</script>

<style lang="sass">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap')
*
  box-sizing: border-box
  font-family: Poppins, sans-serif
  margin: 0
  padding: 0

#app
  min-height: 100vh
  color: var(--main-text-color)
  width: 100%
  margin: 0 auto
  max-width: 1464px
  padding: 0 20px
  position: relative

body
  background-color: var(--main-bg-color)
  overflow-x: hidden

img
  object-fit: contain
</style>
