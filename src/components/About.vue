<template>
    <section id="about" class="about-section">
        <div class="container py-5">
            <div class="row align-items-center">
                <div class="col-lg-4 col-md-12 col-sm-12 exp-cli">
                    <div class="experience">
                        <h2 class="yellow">08</h2>
                        <span>Years of Experience</span>
                    </div>

                    <div class="client">
                        <span class="green2">100%</span>
                        <span class="client-satisf">Clients Satisfections</span>
                    </div>
                </div>

                <div class="col-lg-6 col-md-12 col-sm-12 blocchetti">
                    <div class="about-content">
                        <div class="about-title">
                            <h2>My Advantage</h2>
                            <p>Must explain to you how all this mistaken 
                            idea of denouncing pleasure and praising pain 
                            was born and I will give you a complete account 
                            the system and expound the actual and praising 
                            pain was born.</p>
                        </div>
                    </div>

                    <div class="row d-flex justify-content-between gap-3">
                        <div class="col-3 card border-3 border-bottom-0 border-warning rounded-4 py-3">
                            <h3>98%</h3>
                            <p class="yellow">Figma</p>
                        </div>
                        <div class="col-3 card border-3 border-bottom-0 border-success rounded-4 py-3">
                            <h3>92%</h3>
                            <p class="green">Sketch</p>
                        </div>
                        <div class="col-3 card border-3 border-bottom-0 border-danger rounded-4 py-3">
                            <h3>88%</h3>
                            <p class="red">Photoshop</p>
                        </div>
                        <div class="col-3 card border-3 border-bottom-0 border-color-orange rounded-4 py-3">
                            <h3>72%</h3>
                            <p class="orange">Illustrator</p>
                        </div>
                        <div class="col-3 card border-3 border-bottom-0 border-primary rounded-4 py-3">
                            <h3>43%</h3>
                            <p class="blue">WordPress</p>
                        </div>
                        <div class="col-3 card border-3 border-bottom-0 border-color-violet rounded-4 py-3">
                            <h3>37%</h3>
                            <p class="purple">ReactJS</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style scoped>

.about-section {
    background-color: #141414;
    color: white;
    line-height: 2.0;
    padding: 90px;
    background-image: linear-gradient(to top right, #e1bb214c, #181716b5, #1a1a1aec), linear-gradient(to left, #320951d8, #372b43a3, #202020f1);
}

#about {
    background-color: rgb(59, 56, 54);
}

.exp-cli {
    background: linear-gradient(to bottom, #826d183d, #2623179d, #1a1a18);
    padding: 50px 50px 180px;
    border-radius: 10%;
    max-width: 350px;
    text-align: center;
    position: relative;
}

.client {
    display: flex;
    position: absolute;
    left: 80px;
    top: 300px;
    width: 300px;
    height: 100px;
    content: "";
    background: #2d2b1f;
    opacity: .85;
    z-index: 10;
    border-radius: 12px;
    align-items: center;
    justify-content: center;
}

.client-satisf {
    font-size: 22px;
    line-height: 30px;
    margin-left: 10px;
    text-align: left;
}

.blocchetti {
    margin-left: 300px;
}

.card {
    background-color: rgb(41, 41, 41);
    color: white;
    text-align: center;
}

.yellow {
    color: yellow;
}

.green {
    color: green;
}

.green2 {
    color: green;
    font-weight: bold;
    font-size: 40px;
}

.red {
    color: red;
}

.blue {
    color: dodgerblue;
}

.purple {
    color: blueviolet;
}

.border-color-violet {
    border-color: blueviolet;
}

.orange {
    color: rgb(255, 136, 0);
}

.border-color-orange {
    border-color: rgb(255, 136, 0);
}

.experience > h2 {
    font-size: 130px;
}

.about-title > h2 {
    font-size: 50px;
}
</style>