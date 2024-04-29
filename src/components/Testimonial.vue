<template>
<section class="testimonial">
    <div class="container py-5">
        <div class="row align-items-center">
            
            <div class="col-xl-6 col-lg-6 col-12 contenitore">
                <div class="cerchio-esterno">
                    <div class="cerchio-interno">
                        <div class="cerchio-interno2">
                            <img class="immagine1" src="../assets/testimonial.jpg" />
                            <img class="immagine2" src="https://elito-next.netlify.app/images/testimonial/img-2.jpg" alt="">
                            <img class="immagine3" src="https://elito-next.netlify.app/images/testimonial/img-3.jpg" alt="">
                            <img class="immagine4" src="https://elito-next.netlify.app/images/testimonial/img-4.jpg" alt="">
                            <img class="immagine5" src="https://elito-next.netlify.app/images/testimonial/img-5.jpg" alt="">
                        </div>
                        
                    </div>
                </div>
            </div>

            <div class="col-xl-6 col-lg-6 col-12">

                <h4>Many desktop publishing packages and editors now use as their.</h4>
                <p>
                    It is a long established fact that a reader will be distracted by 
                    the readable content of page when looking at its layout point of 
                    using is that it has more-or-less normal distribution of letters, 
                    as opposed to using 'Content here, content here', 
                    making look like readable English.
                </p>

            
                <h3>Benjir Walton,</h3>
                <p>Marker</p>
                
            </div>

        </div>
    </div>
</section>

</template>

<script>
export default {
    name: 'Testimonial'
}
</script>

<style scoped>
.testimonial {
    background-color: rgb(33, 33, 33);
    color: white;
    background-image: radial-gradient(circle at 25% 50%, #6e6d6d4c, #514d3e29, #2020202e);
}

img.immagine1 {
    border-radius: 50%;
    width: 250px;
}

img.immagine2 {
    border-radius: 50%;
    width: 100px;
    position: absolute;
    top: -60px;
    left: 20px;
}

img.immagine3 {
    border-radius: 50%;
    width: 80px;
    position: absolute;
    top: 200px;
    left: -80px;
}

img.immagine4 {
    border-radius: 50%;
    width: 80px;
    position: absolute;
    top: 0px;
    left: 280px;
    
}

img.immagine5 {
    border-radius: 50%;
    width: 100px;
    position: absolute;
    top: 260px;
    left: 260px;
}

.cerchio-esterno {
    border-radius: 50%;
    width: 450px;
    height: 450px;
    background-color: transparent;
    border: 1px rgba(128, 128, 128, 0.299) solid;
    display: flex;
    align-items: center;
    justify-content: center;
}

.cerchio-interno {
    border-radius: 50%;
    width: 380px;
    height: 380px;
    background-color: transparent;
    border: 1px rgba(128, 128, 128, 0.499) solid;
    display: flex;
    align-items: center;
    justify-content: center;
}

.cerchio-interno2 {
    border-radius: 50%;
    width: 320px;
    height: 320px;
    background-color: transparent;
    border: 1px gray solid;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}

h3 {
    font-size: 37px;
}

h4 {
    font-size: 35px;
}

p {
    font-size: 18px;
}


</style>