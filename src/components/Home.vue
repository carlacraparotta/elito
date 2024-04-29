<!-- Carla -->

<template>

    <section class="home">
        <div class="container py-5">
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-12">
                    <div>
                        <h2>Hello,</h2>
                        <h1>I Am Ronald.</h1>
                    </div>

                    <div>
                        <h5>UI/UX Designer</h5>
                    </div>

                    <div>
                        <p>Must explain to how all this mistaken idea denouncing pleasure pain the system and expound the actua.</p>
                    </div>

                    <div>
                        <a class="rounded-pill">Hire Me</a>
                    </div>
                </div>
                <div class="col-xl-6 col-lg-6 col-12 contenitore">
                    <img class="immagine1" src="../assets/ragazzo-home.jpg" />
                    <img class="immagine2" src="../assets/photoshop.svg" alt="">
                    <img class="immagine3" src="../assets/diamond.svg" alt="">
                    <img class="immagine4" src="../assets/shield-fill-check.svg" alt="">
                    <img class="immagine5" src="../assets/illustrator.svg" alt="">
                </div>
            </div>
        </div>
    </section>

</template>

<script>
export default {
    name: 'Home'
}
</script>

<style scoped>

.home {
    background-color: #202020;
    color: white;
    line-height: 2.0;
    padding: 110px;
    background-image: linear-gradient(to right, #e121384c, #513e3e29, #2020203f), linear-gradient(to bottom, #3778d34c, #3e415129, #2020203f), radial-gradient(circle,  #e1d1214c, #514c3e29, #2020203f);
}
.contenitore {
    position: relative;
}

img.immagine1 {
    border-radius: 50%;
}

img.immagine2 {
    width: 130px;
    position: absolute;
    top: 40px;
    left: 20px;
}

img.immagine3 {
    width: 130px;
    position: absolute;
    top: 400px;
    left: 500px;
}

img.immagine4 {
    width: 100px;
    position: absolute;
    top: 400px;
    left: 0px;
    
}

img.immagine5 {
    width: 140px;
    position: absolute;
    top: 40px;
    left: 480px;
}

h1 {
    font-size: 100px;
}

h2 {
    color: yellow;
    font-size: 70px;
}

h5 {
    color: #41b362;
    font-size: 30px;
}

a {
    background-color: #41b362;
    padding: 15px;
    font-size: 18px;
    text-decoration: none;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

a:hover {
    background-color: #278141;
}
</style>