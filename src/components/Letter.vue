<template>
    <div class="letter">
        <h2> {{letter}} </h2>

    </div>
</template>

<script>
export default {
    name: 'Letter',
    props: {
        letter: String,
        color: String
    }
}
</script>

<style scoped>

.letter{
  color: color;  
  size: 20px;
}

</style>