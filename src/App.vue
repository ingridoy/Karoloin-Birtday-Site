<template>
  <div id="app">
    
    <Home msg="Karoloin 25 år!! 🎈💖💃 "/>
    
    <ImageBox msg ="Gratulerer så mye med dagen!!!" path="bilde4.png" />
    <ImageBoxR msg ="håper du har en superduper fin dag" path="bilde6n.png" />
    <ImageBox msg ="og at Damien disker opp noe digg mat" path="food3n.png" />
    <ImageBoxR msg ="Savner dokker masse" path="bilde9n.png" />
    <ImageBox msg ="Sees plutselig 👀👀 om litt " path="bilde8.png" />
    <ImageBoxR msg ="Cheese and L❤️ve" path="2012n.png" />
    <ImageBox msg ="- Kingrid" path="bilde2n.png" />

    <h1> Du er </h1>

    <div id="Karoline">
        <WordPlay msg="Kool"/>
        <WordPlay msg="Attraktiv" />
        <WordPlay msg="Raus"  />
        <WordPlay msg="Omsorgsfull"  />
        <WordPlay msg="Lekker" />
        <WordPlay msg="Innovativ "  />
        <WordPlay msg="Nydelig"  />
        <WordPlay msg="Extra" />
    </div>
    <ImageBox msg ="Keep grinding💯🔥👊" path="2012-5.png" />
    <ImageBoxR msg ="ps! hils kidsa" path="dog1n.png" />


  </div>
</template>

<script>
import Home from './components/Home.vue'
import WordPlay from './components/WordPlay.vue'
import ImageBox from './components/ImageText.vue'
import ImageBoxR from './components/ImageTextR.vue'


export default {
  name: 'App',
  components: {
    Home,
    WordPlay,
    ImageBox,
    ImageBoxR
  }
}


</script>

<style>

*{
  background-color: #faeee7;
}
#app {
  font-family: "Comic Sans MS", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #33272a;
  margin-top: 60px;
  width: 1200px;
  margin: 0 auto;
  
}

#Karoline{
  
 
  margin: 0 auto;
  
}



</style>
