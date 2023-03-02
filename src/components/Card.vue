<template>
    <li class="card">
        <img :src="src" alt="">
        <span>{{ series }}</span>
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

}



img {
    width: 150px;
    margin-bottom: 10px;
}
</style>