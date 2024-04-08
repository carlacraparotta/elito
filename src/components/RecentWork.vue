<template>
    <div id="portfolio">
        <div class="container py-5">
            <div class="title-portfolio">
                <div class="row align-item-center">
                    <div class="col-lg-4 col-12">
                        <div class="title">
                            <h2>Recent Work.</h2>
                            <p>Must explain to you how all this mistaken idea pleasure born and give you a complete account.</p>
                        </div>
                    </div>

                    <div class="col-lg-6">
                        <img class="title-icon" src="../assets/self-growth.png" alt="icon">
                    </div>
                </div>
            </div>
            <div class="slide py-5">
                <Carousel :items-to-show="2.5" :wrap-around="true">
                    <Slide v-for="slide in ['portfolio1', 'portfolio2', 'portfolio3']" :key="slide">
                        <div class="carousel__item">
                            <img @src="getImgUrl(slide)" alt="" />
                        </div>
                    </Slide>

                    <template #addons>
                        <Navigation />
                        <Pagination />
                    </template>
                </Carousel>
            </div>
        </div>
    </div>
</template>

<script>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel'

export default {
    name: 'RecentWork',
    components: {
    Carousel,
    Slide,
    Navigation,
    Pagination
  },

    getImgUrl(name) {
        var images = require.context('../assets/', false, /\.jpg$/)
        return images('./' + name + ".jpg")
    }
}
</script>

<style scoped>
.title-icon {
    width: 130px;
    padding: 20px;
    margin-top: 20px;
    background-color: #303030;
    border-radius: 50%;
    margin-left: auto;
    border: 1px dashed #383838;
    justify-content: end;
    display: flex;
    overflow: visible;
}

.carousel__item {
  min-height: 300px;
  width: 100%;
  background-color: green;
  color: white;
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev,
.carousel__next {
  box-sizing: content-box;
  border: 5px solid white;
}

</style>