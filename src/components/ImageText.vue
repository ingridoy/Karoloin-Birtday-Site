<template>
    <div class="ImageBox">
        <h2> {{msg}} </h2>
        <img :src="require(`@/assets/img/${path}`)" alt="">
    </div>
</template>

<script>
export default {
    name: 'ImageBox',
    props: {
        msg: String,
        path: String
    }
}
</script>

<style scoped>

.ImageBox{
  position: relative;
  overflow: hidden;
  height: 400px;
  width: 1000px;
  stroke: khaki;
  stroke-width: 2px;
      position: sticky;
    top: 30px;

}

h2{
  position: absolute;
  left: 25%;
  background-color: rgba(76, 175, 80, 0.3);
  color: white;
  padding-left: 5px;
  padding-right: 5px;
  font-size: 250%;
  top: 60%;
  left: 40%;
  z-index: 10;
}

.ImageBox img{
    width: 500px;
    position: absolute;
    left: 20%;
    clip: rect(60px,600px,700px,30px);
}


</style>