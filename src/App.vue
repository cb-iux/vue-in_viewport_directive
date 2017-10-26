<template lang="html">
  <div id="app">
    <div class='box red' v-in-viewport.once>
      Interactively formulate sticky functionalities through accurate ideas. Enthusiastically provide access to principle-centered communities whereas future-proof sources. Quickly pursue business expertise before reliable potentialities. Rapidiously pontificate holistic potentialities before professional best practices. Credibly empower distributed growth strategies via prospective leadership. Assertively harness state of the.
    </div>
    <div class='box green' v-in-viewport.once>
      Conveniently benchmark ethical total linkage before synergistic scenarios. Distinctively matrix clicks-and-mortar catalysts for change with functionalized benefits. Rapidiously scale user-centric e-tailers with functional infrastructures. Enthusiastically.
    </div>
    <div class='box yellow' v-in-viewport.once>
      Competently restore vertical growth strategies after backward-compatible "outside the box" thinking. Proactively reinvent multifunctional methods of empowerment without distinctive quality vectors. Efficiently seize 24/365 total linkage through excellent architectures. Energistically fabricate technically sound deliverables and innovative e-tailers. Efficiently facilitate maintainable best practices for equity invested bandwidth.
    </div>
    <!-- <div class='box' v-in-viewport.once></div> -->
    <!-- <div class='box' v-in-viewport.once='{ top: 100; bottom: -100; }'></div> -->
  </div>
</template>

<script>
export default {
}
</script>

<style lang="sass">
body
  height: 3000px
  font-size: 1.6rem
  #app
    // margin-top: 1000px
    border: 1px dashed red

    .box
      border: 1px dashed red
      margin-bottom: 200px
      width: 400px
      opacity: 0
      transform: translate(0,150px)

    .box.in-viewport
      opacity: 1
      transition: all .8s
      transform: translate(0,0px)



</style>
