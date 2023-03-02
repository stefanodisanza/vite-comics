<template>
    <main class="content">
        <div class="container">
            <ul class="grid">
                <Card class="col" v-for="(comic, i) in comics" :key="i" :thumb="comic.thumb" :series="comic.series"
                    :price="comic.price" :src="comic.src" />
            </ul>
        </div>
    </main>
</template>

<script>
import Card from './Card.vue'
export default {
    components: {
        Card
    },
    data() {
        return {
            comics: [
                {
                    src: "/public/fumetto01.jpeg",
                    price: "$19.99",
                    series: "Action Comics",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto02.jpeg",
                    price: "$3.99",
                    series: "American Vampire 1976",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto03.jpeg",
                    price: "$16.99",
                    series: "Aquaman",
                    type: "graphic novel"
                },
                {
                    src: "/public/fumetto04.jpeg",
                    price: "$2.99",
                    series: "Batgirl",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto05.jpeg",
                    price: "$3.99",
                    series: "Batman",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto06.jpeg",
                    price: "$2.99",
                    series: "Batman Beyond",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto07.jpeg",
                    price: "$3.99",
                    series: "Batman/Superman",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto08.jpeg",
                    price: "$4.99",
                    series: "Batman/Superman Annual",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto09.jpeg",
                    price: "$5.99",
                    series: "Batman: The Joker War Zone",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto10.jpeg",
                    price: "$6.99",
                    series: "Batman: Three Jokers",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto11.jpeg",
                    price: "$4.99",
                    series: "Batman: White Knight Presents: Harley Quinn",
                    type: "comic book"
                },
                {
                    src: "/public/fumetto12.jpeg",
                    price: "$16.99",
                    series: "Catwoman",
                    type: "graphic novel"
                }
            ]
        }
    }

}
</script>



<style lang="scss" scoped>
.content {
    background-color: black;

}

.container {
    display: flex;
    color: white;
    padding: 20px;
}

.card {
    padding: 20px;
}

.card_title {
    font-size: 18px;
}
</style>