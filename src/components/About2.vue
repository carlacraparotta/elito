<!-- Amanda -->

<template>
    <div class="wpo-about-area-s2 section-padding undefined" id="about2">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-5 col-md-12 col-sm-12">
                    <div class="wpo-about-img">
                        <img src="../assets/about2.jpg" alt="">
                        <div class="icon-1 floating-item"><img src="../assets/photoshop.svg" alt=""></div>
                        <div class="icon-2 floating-item"><img src="../assets/illustrator.svg" alt=""></div>
                        <div class="icon-3 floating-item"><img src="../assets/diamond.svg" alt=""></div>
                        <div class="project floating-item"><div class="icon">><img src="../assets/shield-fill-check.svg" width="40px"></div>
                        <div class="p-text"><h3><span data-count="1500">1500</span>+</h3><p>Complete Project</p></div>
                    </div>
                </div>  
            </div>
            <div class="col-lg-6 offset-lg-1 col-md-12 col-sm-12">
                <div class="wpo-about-content">
                    <div class="wpo-about-title"><h2>My Advantage</h2><p>Must explain to you how all this mistaken idea of denouncing 
                        pleasure and praising pain was born and I will give you a complete account the system and expound the actual and praising pain was born.</p></div>
                        <div class="wpo-about-funfact"><div class="grid">
                            <div class="grid-inner"><h3><span data-count="98">98</span>%</h3><p>Figma</p></div>
                        </div>
                        <div class="grid">
                            <div class="grid-inner"><h3><span data-count="92">92</span>%</h3><p>Sketch</p></div>
                        </div>
                        <div class="grid">
                            <div class="grid-inner"><h3><span data-count="88">88</span>%</h3><p>Photoshop</p></div>
                        </div>
                        <div class="grid">
                            <div class="grid-inner"><h3><span data-count="72">72</span>%</h3><p>Illustrator</p></div>
                        </div>
                        <div class="grid">
                            <div class="grid-inner"><h3><span data-count="43">43</span>%</h3><p>WordPress</p></div>
                        </div>
                        <div class="grid">
                            <div class="grid-inner"><h3><span data-count="37">37</span>%</h3><p>ReactJS</p></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    name: 'About2'
}
</script>

<style scoped>

.wpo-about-area-s2 {
  position: relative;
}
.wpo-about-area, .wpo-about-area-s2 {
  background: #191919;
  overflow: hidden;
  z-index: 1;
  position: relative;
}

.wpo-about-area-s2 .wpo-about-img {
  position: relative;
  padding: 30px;
  background: #222121;
  border-radius: 6px;
}

img {
  max-width: 100%;
  border-radius: 300px;
}
img, svg {
  vertical-align: middle;
}

.wpo-about-area-s2 .wpo-about-img .icon-2 {
  left: auto;
  right: 0;
}
.wpo-about-area-s2 .wpo-about-img .icon-1, .wpo-about-area-s2 .wpo-about-img .icon-2, .wpo-about-area-s2 .wpo-about-img .icon-3 {
  position: absolute;
  left: 0;
  top: 2%;
  width: 110px;
  height: 110px;
  padding: 20px;
  background: #fff;
  border-radius: 25px;
}

.wpo-about-area-s2 .wpo-about-img .icon-2 {
  left: auto;
  right: 0;
}

.wpo-about-area-s2 .wpo-about-img .icon-1 img, .wpo-about-area-s2 .wpo-about-img .icon-2 img, .wpo-about-area-s2 .wpo-about-img .icon-3 img {
  border-radius: 0;
}

.wpo-about-area-s2 .wpo-about-img .icon-3 {
  left: auto;
  right: 0;
  top: auto;
  bottom: 2%;
}

.wpo-about-area-s2 .wpo-about-img .project {
  position: absolute;
  left: 0;
  bottom: 2%;
  padding: 5px 20px;
  background: #fff;
  border-radius: 40px;
  display: flex;
  align-items: center;
}

.wpo-about-area-s2 .wpo-about-img .project .p-text h3 {
  font-size: 25px;
  margin-bottom: 0;
  color: #202020;
}
h1, h2, h3, h4, h5, h6 {
  color: #fff;
  font-family: Inter,sans-serif;
  font-weight: 600;
}

.wpo-about-area-s2 .wpo-about-img .project .p-text p {
  font-size: 15px;
  margin-bottom: 0;
  color: #585858;
}

.section-padding {
  padding: 120px 0;
}

.align-items-center {
  align-items: center !important;
}
.row {
  --bs-gutter-x: 1.5rem;
  --bs-gutter-y: 0;
  display: flex;
  flex-wrap: wrap;
  margin-top: calc(-1 * var(--bs-gutter-y));
  margin-right: calc(-.5 * var(--bs-gutter-x));
  margin-left: calc(-.5 * var(--bs-gutter-x));
}

@media (min-width: 992px) {
  .col-lg-5 {
    flex: 0 0 auto;
    width: 41.66666667%;
  }
}

@media (min-width: 992px) {
  .offset-lg-1 {
    margin-left: 8.33333333%;
  }
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-title, .wpo-about-area .wpo-about-content .wpo-about-title {
  margin-bottom: 40px;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact, .wpo-about-area .wpo-about-content .wpo-about-funfact {
  display: flex;
  flex-wrap: wrap;
  margin: 0 -15px;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid {
  background: linear-gradient(180deg,rgba(255,230,0,.6),rgba(31,30,28,.6) 67.59%);
  flex-basis: 28.33%;
  border-radius: 12px;
  margin: 0 15px 30px;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid .grid-inner, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid .grid-inner {
  padding: 40px;
  background: #1f1e1d;
  margin: 3px 3px 0;
  text-align: center;
  border-radius: 120px;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid .grid-inner p {
  margin-bottom: 0;
  color: #ffe600;
}
p {
  font-size: 16px;
  color: #d8d8d8;
  line-height: 1.8em;
  margin-top: 0;
  margin-bottom: 1rem;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(2), .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(2) {
  background: linear-gradient(180deg,rgba(89,195,120,.6),rgba(31,30,28,.6) 67.59%);
}
.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid {
  background: linear-gradient(180deg,rgba(255,230,0,.6),rgba(31,30,28,.6) 67.59%);
  flex-basis: 28.33%;
  border-radius: 12px;
  margin: 0 15px 30px;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(2) .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(2) .grid-inner p {
  margin-bottom: 0;
  color: #59c378;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(3), .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(3) {
  background: linear-gradient(180deg,rgba(221,88,79,.6),rgba(31,30,28,.6) 67.59%);
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(3) .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(3) .grid-inner p {
  margin-bottom: 0;
  color: #dd584f;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(4), .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(4) {
  background: linear-gradient(180deg,rgba(255,154,0,.6),rgba(31,30,28,.6) 67.59%);
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(4) .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(4) .grid-inner p {
  margin-bottom: 0;
  color: #ff9a00;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(5), .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(5) {
  background: linear-gradient(180deg,rgba(0,169,255,.6),rgba(31,30,28,.6) 67.59%);
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(5) .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(5) .grid-inner p {
  margin-bottom: 0;
  color: #00a9ff;
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(6), .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(6) {
  background: linear-gradient(180deg,rgba(158,0,255,.6),rgba(31,30,28,.6) 67.59%);
}

.wpo-about-area-s2 .wpo-about-content .wpo-about-funfact .grid:nth-child(6) .grid-inner p, .wpo-about-area .wpo-about-content .wpo-about-funfact .grid:nth-child(6) .grid-inner p {
  margin-bottom: 0;
  color: #ad00ff;
}


</style>