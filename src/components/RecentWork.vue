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
            <div class="slide py-5 banner">
                <div class="row d-flex justify-content-around gap-3">
                    <div class="col-lg-3 col-md-6 col-12">
                        <div class="icon bg">
                            <img src="../assets/portfolio1.jpg" alt="">
                        </div>
                    
                        <div class="py-3">
                            <a href="">Follio - Multipurpose Portfolio HTML5 Template Project</a>
                        </div>
                    </div>

                    <div class="col-lg-3 col-md-6 col-12">
                        <div class="icon bg">
                            <img src="../assets/portfolio2.jpg" alt="">
                        </div>
                        
                        <div class="py-3">
                            <a href="">Elito - Creative Portfolio React Template Project</a>
                        </div>
                    </div>

                    <div class="col-lg-3 col-md-6 col-12">
                        <div class="icon bg">
                            <img src="../assets/portfolio3.jpg" alt="">
                        </div>
                        
                        <div class="py-3">
                            <a href="">Arkio - Architecture & Interior WordPress Theme Project</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'RecentWork',
}
</script>

<style scoped>
#portfolio {
    background-color: rgb(59, 56, 54);
}

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

a {
    color: white;
    text-decoration: none;
    font-size: 22px;
}

a:hover {
    color: rgb(85, 255, 0);
    text-decoration: none;
}

.banner {
    flex-basis: 30%;
    position: relative;
    overflow: hidden;
}

.bg {
    background-size: cover;
    background-position: 50% 20%;
    transition: transform .6s;
}

.bg:hover {
    transform: scale(1.1);
}
</style>