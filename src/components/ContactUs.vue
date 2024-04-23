<template>
    <section class="contactUs">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-sm-12">
                    <p><strong>Send me a message and make something together.</strong></p>
                </div>
                <div class="col-lg-6 col-sm-12 text-center">
                    <button type="button" class="btn btn-primary btn-lg"><a href="#talk">Contact Us </a><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8"/>
                    </svg></button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'ContactUs'
}
</script>

<style scoped>
.contactUs {
    background-color: #ff4155;
    padding: 55px;
}

p {
    color: white;
    font-size: 47px;
}


button {
    background-color: #202020;
    font-weight: 600;
    border: 0;
    padding: 15px 35px 15px 35px;
    margin-top: 15%;
}

button a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

button:hover {
    background-color: #202020;
}

</style>