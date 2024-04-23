<template>
    <div class="carousel-container" :style="{ width: carouselWidth + 'px' }">
      <h2>Carosello immagini</h2>
      <div class="carousel">
        <div class="carousel-inner" :style="{ transform: 'translateX(' + translateX + 'px)' }">
          <div v-for="(image, index) in images" :key="index" class="carousel-item">
            <div>
                <img :src="image" alt="Carousel Image" />
                <a href="#">ciao</a>
            </div>
            
          </div>
        </div>
      </div>
      <div class="carousel-controls">
        <button @click="prevSlide" :disabled="currentIndex === 0">Prev</button>
        <button @click="nextSlide" :disabled="currentIndex === totalItems - itemsPerPage">Next</button>
      </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      currentIndex: 0,
      translateX: 0,
      images: [
        'https://cdn.pixabay.com/photo/2024/03/05/14/33/purple-8614655_640.jpg',
        'https://cdn.pixabay.com/photo/2023/01/10/16/23/hedgehog-7710053_640.jpg',
        'https://cdn.pixabay.com/photo/2022/11/07/18/29/bird-7576994_640.jpg',
        'https://cdn.pixabay.com/photo/2012/03/01/00/55/flowers-19830_960_720.jpg',
        'https://cdn.pixabay.com/photo/2024/02/15/15/29/crocus-8575610_640.jpg',
        'https://cdn.pixabay.com/photo/2015/04/10/01/41/fox-715588_960_720.jpg'
      ],
      itemsPerPage: 3, //sostituire con il numero di immagini desiderato
      itemWidth: 250, // Larghezza di ciascuna immagine
      margin: 20 // Margine delle immagini
    };
  },
  computed: {
    totalItems() {
      return this.images.length;
    },
    carouselWidth() {
      return (this.itemWidth + this.margin) * this.itemsPerPage;
    }
  },
  name: 'Carousel',
  methods: {
    nextSlide() {
      if (this.currentIndex < this.totalItems - this.itemsPerPage) {
        this.currentIndex++;
        this.translateX -= this.itemWidth + this.margin;
      }
    },
    prevSlide() {
      if (this.currentIndex > 0) {
        this.currentIndex--;
        this.translateX += this.itemWidth + this.margin;
      }
    }
  }
};
</script>

<style scoped>
.carousel-container {
  margin: 0 auto;
  overflow: hidden;
}

.carousel {
  display: flex;
  margin-bottom: 10px;
}

.carousel-inner {
  display: flex;
  overflow: visible;
  transition: transform 0.5s ease;
}

.carousel-item {
  display: contents;
  flex: 0 0 auto;
}

.carousel img {
  width: 250px;
  height: auto;
  margin: 0 10px;
}

.carousel-controls {
  display: flex;
  justify-content: center;
}

.carousel-controls button {
  margin: 0 5px;
}
</style>
