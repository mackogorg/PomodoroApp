<template>
  <div class="startButton">
    <img :src="PlayCircle"/>
  </div>
</template>

<script>
  import PlayCircle from "@/assets/play-circle.svg";

  export default {
  name: 'StartButton',
  setup() {
      return {
        PlayCircle
      }
    }
  }
</script>

<style scoped lang="scss">
.startButton {
  height: 285px;
  width: 285px;
  background-color: #ff6042;
  border-radius: 50%;
  transition-duration: 0.4s;
  display: flex;
  justify-content: center;
  align-items: center;

  &:hover {
    background-color: #da533c;
  }
}
</style>