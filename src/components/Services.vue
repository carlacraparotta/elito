<!-- Carla -->

<template>
    <div id="service" class="popular">
        <div class="container py-5">
            <div class="d-flex row justify-content-center">
                <div class="col-lg-6 col-12">
                    <h2 class="text-center title">Popular Services</h2>
                    <p class="text-center p-title">
                        Must explain to you how all this mistaken idea 
                        of denouncing pleasure born and give you a complete 
                        account the system
                    </p>
                </div>
            </div>

            <div>
                <ul class="d-flex justify-content-around nav nav-tabs py-5">
                    <li class="nav-item rounded-pill">
                        <a :class="{ active: activeTab === 'tab1' }" class="nav-link" @click="activeTab = 'tab1'">Design</a>
                    </li>
                    <li class="nav-item rounded-pill">
                        <a :class="{ active: activeTab === 'tab2' }" class="nav-link" @click="activeTab = 'tab2'">Development</a>
                    </li>
                    <li class="nav-item rounded-pill">
                        <a :class="{ active: activeTab === 'tab3' }" class="nav-link" @click="activeTab = 'tab3'">Marketing</a>
                    </li>
                </ul>
            </div>

            <div class="tab-content">
                <div :class="{ active: activeTab === 'tab1' }" class="row d-flex justify-content-around gap-3">

                    <div class="col-lg-3 col-md-6 col-12 carta rounded">                  
                        <div class="icon-1">
                            <img src="../assets/044pen_101483.png" alt="">
                        </div>
                        <h2 class="text-center">Graphic Design</h2>
                        <p class="text-center">
                            Explain to you how all this mistaken idea of 
                            denouncing pleasure born and give you complete 
                            account the system.
                        </p>
                        <div class="text-center py-3">
                            <a href="#">LEARN MORE</a>
                        </div>
                    </div>
                
            
                    <div class="col-lg-3 col-md-6 col-12 carta rounded">
                        <div class="icon">
                            <img src="../assets/art.png" alt="">
                        </div>
                        <h2 class="text-center">Brand Identity</h2>
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
                            <img src="../assets/addon.png" alt="">
                        </div>
                        <h2 class="text-center">UI/UX Design</h2>
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

                <!-- tab2 -->
                <div :class="{ active: activeTab === 'tab2' }" class="row d-flex justify-content-around gap-3">
                    <div class="col-lg-3 col-md-6 col-12 carta rounded">                  
                        <div class="icon">
                            <img src="../assets/coding.png" alt="">
                        </div>
                        <h2 class="text-center">Web Development</h2>
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
                            <img src="../assets/app-development.png" alt="">
                        </div>
                        <h2 class="text-center">App Development</h2>
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
                            <img src="../assets/booking.png" alt="">
                        </div>
                        <h2 class="text-center">Softwere Development</h2>
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

                <!-- tab3 -->
                <div :class="{ active: activeTab === 'tab3' }" class="row d-flex justify-content-around gap-3">
                    <div class="col-lg-3 col-md-6 col-12 carta rounded">                  
                        <div class="icon">
                            <img src="../assets/social-media.png" alt="">
                        </div>
                        <h2 class="text-center">Social Media Marketing</h2>
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
                            <img src="../assets/promotion.png" alt="">
                        </div>
                        <h2 class="text-center">Digital Marketing</h2>
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
                            <img src="../assets/email-marketing.png" alt="">
                        </div>
                        <h2 class="text-center">Email Marketing</h2>
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
  name: 'Services',
  data() {
    return {
      activeTab: 'tab1',
      dialog: false
    };
  },
  methods: {
    openDialog() {
      this.dialog = true;
    },
  }
};
</script>

<style scoped>

li > a {
    border: none!important;
}

li > a.active {
    color: yellow!important;
    background-color: #373737!important;
    border: none!important;
}

.popular {
background-color: #202020;
color: white;
line-height: 2.0;
padding: 90px;
background-image: linear-gradient(to right bottom, #e1b4214c, #514d3e29, #1f1f1f44)
}

.title {
    font-size: 50px;
    font-weight: bold;
}

.p-title {
    font-size: 20px;
}

.tab-content > div {
  display: none !important;
}

.tab-content > div.active {
  display: flex !important;
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

a {
    color: white;
    text-decoration: none;
}

a:hover {
    color: yellow;
    text-decoration: none;
    cursor: pointer;
}


</style>