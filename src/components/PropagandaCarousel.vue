<template>
    <v-carousel height="300" width="100">
        <v-carousel-item
            v-for="(propaganda, index) in propagandas"
            :key="index"
            cover
            :src="propaganda.image_url"
        >
        </v-carousel-item>
    </v-carousel>
</template>

<script>
export default {
    name: "PropagandaCarousel",
    
    data() {
        return {
            propagandas: [
                {
                    image_url: "https://img.freepik.com/vetores-gratis/conceito-de-boas-festas-de-ouro_23-2148772622.jpg?t=st=1735266557~exp=1735270157~hmac=e078a3ad4d7da749ec0d3852b1968e2ab5afd9c41af3e634f37e1534543e7540&w=740"
                    },
                {
                    image_url: "https://www.designi.com.br/images/preview/11059133.jpg"
                    }
            ],
        }
    }
}
</script>

<style>

</style>