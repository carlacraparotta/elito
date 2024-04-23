<template>
    <section id="PricingPlan" class="yellow-shadow">
        <div class="container">
            <div class="row">
                <div class="col lg-12">
                    <div class="title-area">
                        <h3 class="d-flex justify-content-center">Pricing Plan</h3>
                        <p class="d-flex justify-content-center">Must explain to you how all this mistaken idea of
                            denouncing <br>pleasure born and give you a complete account the system</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <!-- basic -->
                <div class="col-lg-4 col-md-12">
                    <div class="box-pricing">
                    
                        <div class="container">
                            <div class="plan text-center">BASIC</div>
                            <h3><strong>$120</strong> <sup>/PER MONTH</sup></h3>
                            <p>Determine the Best Pricing Strategy For Your Business.</p>
                            <div class="divider"></div>
                            <ul class="advantage">
                                <li>Softwere Development</li>
                                <li>Web Development</li>
                                <li>Digital Marketing</li>
                                <li>Graphic Design</li>
                                <li>24/Support</li>
                            </ul>
                            <button>CHOOSE PLAN</button>
                        </div>
                    </div>
                </div>
                <!-- premium -->
                <div class="col-lg-4 col-md-12">
                    <div class="box-pricing">
                    
                        <div class ="container">
                            <div class="plan text-center">PREMIUM</div> 
                            <h3><strong>$210</strong><sup>/PER MONTH</sup></h3>
                            <p>Determine the Best Pricing Strategy For Your Business.</p>
                            <div class="divider"></div>
                            <ul class="advantage">
                                <li>Softwere Development</li>
                                <li>Web Development</li>
                                <li>Digital Marketing</li>
                                <li>Graphic Design</li>
                                <li>24/Support</li>
                            </ul>
                            <button>CHOOSE PLAN</button>
                        </div>
                    </div>
                </div>
                <!-- advanced -->
                <div class="col-lg-4 col-md-12">
                    <div class="box-pricing">
                        
                        <div class="container fuid">
                            <div class="plan text-center">ADVANCED</div>
                            <h3><strong>$373</strong> <sup>/PER MONTH</sup></h3>
                            <p>Determine the Best Pricing Strategy For Your Business.</p>
                            <div class="divider"></div>
                            <ul class="advantage">
                                <li>Softwere Development</li>
                                <li>Web Development</li>
                                <li>Digital Marketing</li>
                                <li>Graphic Design</li>
                                <li>24/Support</li>
                            </ul>
                            <button>CHOOSE PLAN</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>

</template>

<script>
export default {
    name: 'PricingPlan'
}
</script>

<style scoped>
#PricingPlan {
    padding: 90px;
    background-color: #191919;
    color: white;
}

/* title-area */
.title-area h3 {
    font-size: 48px;
}

.title-area p {
    color: rgba(238, 237, 237, 0.794);
    font-size: 18px;
    line-height: 2.0;
    padding-bottom: 30px;
}

.yellow-shadow {
    background-image: radial-gradient(circle, #514c28, #191919b3, #191919);
}

/* box */
.box-pricing .container {
    padding-right: 30px;
    padding-left: 30px;
    background-color: #262626;
    color: rgba(238, 237, 237, 0.794);
    text-align: center;
}

ul li {
    color: rgba(238, 237, 237, 0.794);
    list-style-type: none;
    line-height: 2.5;

}
.box-pricing h3 {
    font-size: 15px;
}

strong {
    font-size: 42px;
    color: white;
}

sup {
    font-size: 15px;
}

.box-pricing p{
    line-height: 1.5;
    padding-bottom: 30px;
    max-width: 282px;
    border-bottom: 1px solid #496451;
}

.box-pricing p::after {
    content: " ";
    border: #59c378, solid, 1px;
}

button {
    border: 1px solid #496451;
    color: #59c378;
    background-color: #262626;
    padding: 10px 25px;
    font-size: 16px;
    font-weight: 500;
    margin-bottom: 30px;
}

button:hover {
    background-color: #59c378;
    color: #d8d8d8;
    transition: all .2s
}

/* plan box */
.plan {
    padding: 5px 15px 5px; 
    background-color: #59c378;
    color: #d8d8d8;
    border-radius: 0px 0px 10px 10px;
    display: inline-block;
    margin-bottom: 30px;
    right: 50%;
}

</style>