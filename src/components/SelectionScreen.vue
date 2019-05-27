<template>
  <div id="selectionScreen">
    <h1>Coming Soon</h1>
  </div>
</template>

<script>
export default {
  name: "SelectionScreen"
};
</script>

<style>
#selectionScreen {
  position: absolute;
  background: #ebce04;
  min-width: 600px;
  height: 100%;
  animation: slide-in 1.1s ease-in;
  box-shadow: inset 1px 0 5px 0;
}

@keyframes slide-in {
  0% {
    left: -640px;
  }

  90% {
    left: 41px;
  }
  100% {
    left: 40px;
  }
}
</style>

