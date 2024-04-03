<template>
    <section id="about">
        <div class="container py-5">
            <div class="row align-items-center">
                <div class="col-lg-5 col-md-12 col-sm-12">
                    <div class="experience">
                        <h2 class="yellow">08</h2>
                        <span>Years of Experience</span>
                    </div>

                    <div class="client">
                        <h3 class="green">100%</h3>
                        <p>Clients sotisfections</p>
                    </div>
                </div>

                <div class="col-lg-6 col-md-12 col-sm-12">
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

#about {
    background-color: darkslateblue;
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
</style>