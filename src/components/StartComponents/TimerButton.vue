<template>
  <div class="timerButton">
    XX:XX
  </div>
</template>

<script>
  export default {
  name: 'TimerButton'
  }
</script>

<style scoped lang="scss">
  .timerButton {
    height: 285px;
    width: 285px;
    background-color: #ff6042;
    border-radius: 50%;
    transition-duration: 0.4s;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;

    font-family: Roboto;
    font-weight: 600;
    font-size: 64px;
    color: #FFFFFF;

    -webkit-user-select: none;       
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;

    &:hover {
      background-color: #da533c;
    }
  }
</style>