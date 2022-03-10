<template>
  <template v-if="!timerStart">
    <StartButton @click="timerStart = !timerStart"/>
  </template>
  <template v-else>
    <TimerButton @click="timerStart = !timerStart"/>
  </template>
</template>

<script>
import StartButton from '@/components/StartComponents/StartButton.vue'
import TimerButton from '@/components/StartComponents/TimerButton.vue'

export default {
  name: 'StartView',
  components: {
      StartButton, TimerButton
  },
  data(){
    return {
      timerStart: false
    }
  }
}
</script>

<style scoped>

</style>