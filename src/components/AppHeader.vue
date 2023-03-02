<script>
export default {

}
</script>

<template>
    <header>
        <div class="container">
            <div>
                <img src="/dc-logo.png" alt="" class="logo">
            </div>
            <div>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: white;
}

.container {
    display: flex;
    justify-content: space-between;
    align-content: center;
    padding: 20px;
}

ul {
    display: flex;
}

.logo {
    width: 60px;
}

li {
    margin: 10px;
}</style>
