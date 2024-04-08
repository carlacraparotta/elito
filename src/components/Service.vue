<template>
    <div id="service">
        <div class="container py-5">
            <div class="d-flex row justify-content-center">
                <div class="col-lg-6 col-12">
                    <h2 class="text-center">Popular Services</h2>
                    <p class="text-center">
                        Must explain to you how all this mistaken idea 
                        of denouncing pleasure born and give you a complete 
                        account the system
                    </p>
                </div>
            </div>

            <div>
                <ul class="d-flex justify-content-around nav nav-tabs py-5">
                    <li class="nav-item rounded-pill">
                        <a class="nav-link" href="">Design</a>
                    </li>
                    <li class="nav-item rounded-pill">
                        <a class="nav-link" href="">Development</a>
                    </li>
                    <li class="nav-item rounded-pill">
                        <a class="nav-link" href="">Marketing</a>
                    </li>
                </ul>
            </div>

            <div class="content">
                <div class="row d-flex justify-content-around gap-3">
                    <div class="col-lg-3 col-md-6 col-12 carta rounded">
                        <div class="icon">
                            <img src="../assets/044pen_101483.png" alt="">
                        </div>
                        <h2 class="text-center">Graphic Design</h2>
                        <p class="text-center">
                            Explain to you how all this mistaken idea of 
                            denouncing pleasure born and give you complete 
                            account the system.
                        </p>
                        <div class="text-center py-3">
                            <a href="">LEARN MORE</a>
                        </div>
                    </div>
                

            
                    <div class="col-lg-3 col-md-6 col-12 carta rounded">
                        <div class="icon">
                            <img src="../assets/044pen_101483.png" alt="">
                        </div>
                        <h2 class="text-center">Graphic Design</h2>
                        <p class="text-center">
                        Explain to you how all this mistaken idea of 
                        denouncing pleasure born and give you complete 
                        account the system.
                        </p>
                        <div class="text-center py-3">
                            <a href="">LEARN MORE</a>
                        </div>
                    </div>

        

        

                    <div class="col-lg-3 col-md-6 col-12 carta rounded">
                        <div class="icon">
                            <img src="../assets/044pen_101483.png" alt="">
                        </div>
                        <h2 class="text-center">Graphic Design</h2>
                        <p class="text-center">
                        Explain to you how all this mistaken idea of 
                        denouncing pleasure born and give you complete 
                        account the system.
                        </p>
                        <div class="text-center py-3">
                            <a href="">LEARN MORE</a>
                        </div>
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Service'
}
</script>

<style scoped>
#service {
    background-color: rgb(34, 31, 29);
}

.nav-item {
    background-color: #373737;
}

.nav-item:hover {
    border: none;
}
.nav-link:hover {
    border: none;
}

.nav-tabs {
    border-bottom: 0;
}

li {
    padding: 10px;
    font-size: 22px;
}

a {
    color: white;
    text-decoration: none;
}

a:hover {
    color: yellow;
    text-decoration: none;
}

img {
    width: 130px;
    padding: 20px;
    margin-top: 20px;
    background-color: #303030;
    border-radius: 50%;
    display: flex;
    margin-left: auto;
    margin-right: auto;
    overflow: visible;
}

.carta {
    background-color: #262626;
    border: 2px solid rgb(125, 125, 125);
    padding: 20px;
}
</style>