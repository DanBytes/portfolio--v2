<template>
  <div id="globe">
    <h1 id="title">Hello World !</h1>
  </div>
</template>

<script>
export default {
  name: "Globe"
};
</script>


<style>
#globe {
  margin: auto;
  margin-top: -30px;
  width: 450px;
  height: 450px;
  background-image: url("../assets/images/globe4.png");
  /* border-style: solid; */
  border-radius: 50%;
  /* border-width: 10px; */
  background-size: cover;
  box-shadow: -10px -20px 50px 2px #000 inset, 0 0 50px 2px #000 inset;
  animation: spin 35s linear infinite;
}
@keyframes spin {
  0% {
    background-position: 0;
    transform: rotate(-10deg);
  }
  50% {
    transform: rotate(2deg);
  }
  100% {
    background-position: -199.99%;
    transform: rotate(-10deg);
  }
}
</style>


