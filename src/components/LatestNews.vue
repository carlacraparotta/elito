<template>
    <section class="news p-5">
        <div class="container">
            <div class="row">
                <div class="col top-title">
                    <h3 class="d-flex justify-content-center">Latest News</h3>
                    <p class="d-flex justify-content-center">Must explain to you how all this mistaken idea <br>
                        pleasure
                        born and give you a complete account.</p>
                </div>
            </div>
            <div class="row">
                <div class="col">
                    <!-- card carousel -->
                    <button id="left-button"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                            fill="currentColor" class="bi bi-arrow-down-left" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M2 13.5a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 0-1H3.707L13.854 2.854a.5.5 0 0 0-.708-.708L3 12.293V7.5a.5.5 0 0 0-1 0z" />
                        </svg></button>
                    <button id="right-button"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                            fill="currentColor" class="bi bi-arrow-up-right" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M14 2.5a.5.5 0 0 0-.5-.5h-6a.5.5 0 0 0 0 1h4.793L2.146 13.146a.5.5 0 0 0 .708.708L13 3.707V8.5a.5.5 0 0 0 1 0z" />
                        </svg></button>
                    <div class="card-group">
                        <div class="card">
                            <img src="https://elito-next.netlify.app/images/blog/img-1.jpg" class="card-img-top"
                                alt="blog">
                            <div class="card-body">
                                <h5 class="card-data">25 Dec, 2020</h5>
                                <p class="card-text"><strong>Have envolved hover the years sometimes accident.</strong>
                                </p>
                                <button type="button" class="btn">
                                    <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                            fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg> Post Details</a>
                                </button>
                            </div>
                        </div>
                        <div class="card">
                            <img src="https://elito-next.netlify.app/images/blog/img-2.jpg" class="card-img-top"
                                alt="ragazza al computer">
                            <div class="card-body">
                                <h5 class="card-data">13 Dec, 2020</h5>
                                <p class="card-text"><strong>The Internet tend to repeat predefined chuncks.</strong>
                                </p>
                                <button type="button" class="btn">
                                    <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                            fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg> Post Details</a>
                                </button>
                            </div>
                        </div>
                        <div class="card">
                            <img src="https://elito-next.netlify.app/images/blog/img-3.jpg" class="card-img-top"
                                alt="yoga">
                            <div class="card-body">
                                <h5 class="card-data">22 Dec, 2020</h5>
                                <p class="card-text"><strong>The standard chunk of used since the interested.</strong>
                                </p>
                                <button type="button" class="btn">
                                    <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                            fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg> Post Details</a>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'NewsComponent'
}

</script>

<style scoped>
.news,
.card {
    background-color: #262626;
    color: white;
    border: #262626;
}

#left-button,
#right-button {
    background-color: #333;
    border: none;
    border-radius: 100%;
    color: #fff;
    font-size: 18px;
    padding: 10px 20px;
    cursor: pointer;

}

#left-button:hover,
#right-button:hover {
    background-color: lightgreen;
}

#left-button {
    float: left;
    margin-top: 70px;

}

#right-button {
    float: right;
    margin-top: 70px;

}

.card {
    margin-right: 20px;
}

.card-data {
    font-size: 13px;
    padding: 10px;
    background-color: #3c3c3c;
    display: inline-block;
}

.card-text {
    font-size: 20px;

}

button {
    text-transform: uppercase;
    font-size: 20px;
}

.card button svg {
    margin-right: 10px;
}

.card button svg:hover {
    margin-left: 10px;
}

a {
    text-decoration: none;
    color: #fff;
}

a:hover {
    color: yellow;

}

.top-title h3 {
    font-size: 48px;
}

.top-title p {
    color: rgba(238, 237, 237, 0.794);
    font-size: 18px;
    line-height: 2.0;
    padding-bottom: 30px;
}

.card button {
    color: white;
}

</style>