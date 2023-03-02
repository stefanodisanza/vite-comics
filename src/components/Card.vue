<template>
    <li class="card">
        <img :src="src" alt="">
        <div>{{ thumb }}</div>
        <h5>{{ series }}</h5>
        <span>{{ price }}</span>
    </li>
</template>
  
<script>
export default {
    props: {
        thumb: String,
        series: String,
        price: String,
    }
}


</script>
  
<style scoped>
.card {

    padding: 20px;
    border: 2px solid red;
}
</style>