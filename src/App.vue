<template>
  <div id="app">
    <Navigation/>
    <SelectionScreen/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <h1 id="title">Hello World !</h1> -->
    <Globe/>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Navigation from "./components/Navigation.vue";
import Globe from "./components/Globe.vue";
import SelectionScreen from "./components/SelectionScreen.vue";
export default {
  name: "app",
  components: {
    Navigation,
    Globe,
    SelectionScreen
  }
};
</script>

<style>
@font-face {
  font-family: Acratica;
  src: url("./assets/font/Acratica-demo-font-FFP.otf");
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* background-image: url("./assets/images/space-wallpaper-1.jpg"); */
  background: #2a2e3d url("./assets/images/space-wallpaper-1.jpg");
  box-shadow: inset 10px 10px 50vw 6vw;
  min-height: 100vh;
  padding-top: 20px;
  padding-left: 40px;
  animation: warp-space 10s ease-in-out infinite;
}

#title {
  margin-top: 200px;
  font-family: Acratica;
  font-size: 10.4em;
  color: aliceblue;
  font-weight: 300;
  text-shadow: 3px 2px 5px #000000;
}

/* @keyframes warp-space {
  0% {
    box-shadow: inset 10px 10px 20vw 5vw;
  }
  50% {
    box-shadow: inset 10px 10px 20vw 10vw;
  }
  100% {
    box-shadow: inset 10px 10px 20vw 5vw;
  }
} */
</style>
