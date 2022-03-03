<template>
  <div class="startButton">
    <div class="startButtonInner">
      <svg class="startButtonTriangle" width="53" height="70" viewBox="0 0 53 70" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1.33331 1.66667L51.3333 35L1.33331 68.3333V1.66667Z" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StartButton'
}
</script>

<style scoped>
.startButton {
  height: 300px;
  width: 300px;
  background-color: #ff6042;
  border-radius: 50%;
  transition-duration: 0.4s;
  display: flex;
  justify-content: center;
  align-items: center;
}

.startButton:hover {
  background-color: #da533c;
}

.startButtonInner {
  height: 175px;
  width: 175px;
  border-radius: 50%;
  outline: 2px solid white;
  display: flex;
  justify-content: center;
  align-items: center;
}

.startButtonTriangle {
  margin-left: 8.34%;
}
</style>