<template>
    <li class="card">
        <img :src="src" alt="">
        <span>{{ series }}</span>
        <span>{{ price }}</span>
    </li>
</template>
  
<script>
export default {
    props: {
        src: String,
        thumb: String,
        series: String,
        price: String,
    }
}


</script>
  
<style scoped>
.card {
    display: flex;
    flex-direction: column;
    border: 2px solid red;
}

img {
    width: 150px;
}
</style>