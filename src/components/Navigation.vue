<template>
  <div id="navigation">
    <i class="fas fa-home"></i>
    <i class="fas fa-briefcase"></i>
    <i class="fab fa-blogger-b"></i>
  </div>
</template>


<script>
export default {
  name: "Navigation"
};
</script>

<style>
#navigation {
  width: 40px;
  height: 100vh;
  position: fixed;
  left: 0;
  background-color: #3d3d3d;
  box-shadow: 2px 0px 5px rgba(0, 0, 0, 0.5);
}

#navigation i {
  font-size: 1.7em;
  color: #ebce04;
  width: 40px;
  padding-top: 15px;
  padding-bottom: 15px;
  border-radius: 50%;
  transition: color 0.1s, background-color 0.1s, border-radius 0.1s linear;
}

#navigation i:hover {
  color: rgb(36, 36, 36);
  background-color: #ebce04;
  border-radius: 5px;
}

@media screen and (max-width: 650px) {
  #navigation {
    top: 0;
    width: 100vw;
    height: 45px;
  }

  #navigation i {
    padding-left: 10%;
    padding-right: 10%;
    padding-top: 10px;
    padding-bottom: 9px;
    border-radius: 10%;
  }
}

@media screen and (min-width: 651px) {
  #navigation {
    padding-top: 20px;
    top: 0;
  }
}
</style>

