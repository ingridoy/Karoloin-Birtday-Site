<template>
  <div class="container">
    <h1> 
        <span style='color: blue'>K</span>
        <span style='color: red'>a</span>
        <span style='color: yellow'>r</span>
        <span style='color: blue'>o</span>
        <span style='color: green'>l</span>
        <span style='color: red'>i</span>
        <span style='color: blue'>n</span>
        <span style='color: green'>e</span>
        <span style='color: red'> </span>
        <span style='color: yellow'> 2</span>
        <span style='color: red'>5 🎈💖💃</span>
      </h1>
    <img src="@/assets/img/karro25.png" id="cover">

 </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.container{
  position: relative;

}

h1{
  position: absolute;
  top: 70%;
  left: 20%;
  background-color: rgba(76, 175, 80, 0.1);
  padding-left: 20px;
  padding-right: 20px;
  font-size: 400%;
  z-index: 10;
}

h1 span{
  background-color: rgba(76, 175, 80, 0.3);

}

img{
  max-width: 1000px;
  overflow: hidden;
}

img:hover {
  animation: shake 0.5s;
  animation-iteration-count: infinite;
}

@keyframes shake {
  0% { transform: translate(1px, 1px) rotate(0deg); }
  10% { transform: translate(-1px, -2px) rotate(-1deg); }
  20% { transform: translate(-3px, 0px) rotate(1deg); }
  30% { transform: translate(3px, 2px) rotate(0deg); }
  40% { transform: translate(1px, -1px) rotate(1deg); }
  50% { transform: translate(-1px, 2px) rotate(-1deg); }
  60% { transform: translate(-3px, 1px) rotate(0deg); }
  70% { transform: translate(3px, 1px) rotate(-1deg); }
  80% { transform: translate(-1px, -1px) rotate(1deg); }
  90% { transform: translate(1px, 2px) rotate(0deg); }
  100% { transform: translate(1px, -2px) rotate(-1deg); }
}



</style>
