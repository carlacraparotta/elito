<!-- Header.vue -->
<template>
  <section class="experience-top red-shadow">
    <div class="container">
      <div class="contact-row">
          <div class="justify-content-center">
              <div class="col-lg-6 col-12">
                  <div class="contact-title">
                      <h2>Let's Talk</h2>
                      <p>Must explain to you how all this mistaken idea of denouncing pleasure born and give you a complete account the system</p>
                  </div>
              </div>
          </div>
      </div>
      <div class="wpo-work-wrap">
        <div class="wpo-work-item">
          <ul>
            <li class="date">2015 - 2016</li>
            <li class="logo"><img src="../assets/1.png" alt=""></li>
            <li class="position">Junior Visual Designer<!-- --> <span>Trapeza Group, USA.<!-- --> <span></span></span></li>
            <li class="link"><a href="/">Go to website</a></li>
          </ul>
        </div>
        <div class="wpo-work-item">
          <ul>
            <li class="date">2017 - 2018</li>
            <li class="logo"><img src="../assets/2.png" alt=""></li>
            <li class="position">UI/UX Designer<!-- --> <span>Gallerie Ontario, Canada<!-- --> <span> (Remote)</span></span></li>
            <li class="link"><a href="/">Go to website</a></li>
          </ul>
        </div>
        <div class="wpo-work-item">
          <ul>
            <li class="date">2019 - 2020</li>
            <li class="logo"><img src="../assets/3.png" alt=""></li>
            <li class="position">Seinor UI/UX Desinger<!-- --> <span>Morson Hybrid, Canada<!-- --> <span></span></span></li>
            <li class="link"><a href="/">Go to website</a></li>
          </ul>
        </div>
        <div class="wpo-work-item">
          <ul>
            <li class="date">2019 - Present</li>
            <li class="logo"><img src="../assets/4.png" alt=""></li>
            <li class="position">Product Designer<!-- --> <span>Myant Inc. Etobicoke, ON<!-- --> <span> (Remote)</span></span></li>
            <li class="link"><a href="/">Go to website</a></li>
          </ul>
        </div>
    </div>
  </div>
  </section>
  
</template>

<script>
export default {
name: 'Experience'
}
</script>

<style scoped>

.errorMessage {
color: red;
}

.experience-top {
background-color: #202020;
color: white;
line-height: 2.0;
padding: 90px;
}

.red-shadow {
background-image: radial-gradient(circle, #84090959, #49383857, #20202089);
}

.wpo-contact-area {
background: #131313;
padding-bottom: 40px !important;
position: relative;
overflow: hidden;
z-index: 1;
}

.offset-lg-1 {
margin-left: 20%;
}

.contact-row {
justify-content: center; /* Centra orizzontalmente il contenuto */
align-items: center; /* Centra verticalmente il contenuto */
--bs-gutter-x: 1.5rem;
--bs-gutter-y: 0;
display: flex;
flex-wrap: wrap;
margin-top: calc(-1 * var(--bs-gutter-y));
margin-right: calc(-.5 * var(--bs-gutter-x));
margin-left: calc(-.5 * var(--bs-gutter-x));
}

.justify-content-center {
display: flex;
justify-content: center !important;
}

.contact-title, .wpo-section-title-s2 {
margin-bottom: 60px;
text-align: center;
}

.contact-title h2 {
font-size: 48px;
line-height: 55px;
font-family: Inter,sans-serif;
font-weight: 700;
color: #fff;
display: inline-block;
padding-bottom: 20px;
position: relative;
margin: 10px 0 0;
}

.contact-title p {
font-size: 18px;
color: #d8d8d8;
margin-bottom: 0;
}

.contact-title {
margin-bottom: 60px;
text-align: center;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item .wpo-work-area, .wpo-work-wrap .wpo-work-item {
padding: 20px 70px;
background: #282828;
border-radius: 8px;
margin-bottom: 30px;
position: relative;
border: 1px solid transparent;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul .wpo-work-area, .wpo-work-wrap .wpo-work-item ul {
list-style: none;
display: flex;
justify-content: space-between;
align-items: center;
padding-left: 0;
}
ul {
padding-left: 0;
margin: 0;
}
dl, ol, ul {
margin-top: 0;
margin-bottom: 1rem;
}
ol, ul {
padding-left: 2rem;
}
dl, ol, ul {
margin-top: 0;
margin-bottom: 1rem;
}
ol, ul {
padding-left: 2rem;
}
*, ::after, ::before {
box-sizing: border-box;
}
*, ::after, ::before {
box-sizing: border-box;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.date .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.date {
font-weight: 700;
font-size: 30px;
line-height: 36px;
color: #fff;
flex-basis: 20%;
display: flex;
align-items: center;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.position .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.position {
font-weight: 700;
font-size: 24px;
line-height: 29px;
color: #fff;
flex-basis: 30%;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.position span .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.position span {
display: block;
font-weight: 400;
font-size: 15px;
line-height: 18px;
margin-top: 10px;
color: #dd584f;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.link, .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.link {
text-align: right;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.link a, .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.link a {
display: flex;
align-items: center;
justify-content: center;
color: #fff;
font-weight: 700;
font-size: 16px;
line-height: 19px;
padding-left: 30px;
position: relative;
display: inline-block;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.link a::before, .wpo-work-area .wpo-work-wrap .wpo-work-item ul li.link a::before {
position: absolute;
left: -5px;
top: 1px;
content: "";
font-family: Flaticon;
transition: all .3s;
}

a {
color: #fff !important;
text-transform: uppercase;
text-decoration: none !important;
padding: 20px;
border: 4px solid #494949 !important;
display: inline-block;
transition: all 0.4s ease 0s;
}
a:hover {
color: #ffffff !important;
background: #f6b93b;
border-color: #f6b93b !important;
transition: all 0.9s ease 0s;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.position span span, .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.position span span {
color: #727272;
display: inline-block;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li {
flex-basis: 18%;
}

.wpo-work-area-s2 .wpo-work-wrap .wpo-work-item ul li.logo .wpo-work-area, .wpo-work-wrap .wpo-work-item ul li.logo {
flex-basis: 15%;
}
</style>