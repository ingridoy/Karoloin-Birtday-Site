<template>
    <div class="words">
        <h2> {{msg}} </h2>

    </div>
</template>

<script>


export default {
    name: 'WordPlay',

    props: {
        msg: String,
        color: String
    }
}
</script>

<style scoped>

.words::first-letter{
  color: #ff8ba7;
  font-size: 200%;
}

.words{
    padding: 10px;
    position: sticky;
    top: 0px;
}

</style>