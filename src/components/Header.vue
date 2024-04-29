<!-- Carla -->

<template>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light fixed-top" data-bs-theme="dark">
            <div class="container">

                <a class="navbar-brand" id="title-logo" href="#">
                    <img src="../assets/logo.png" alt="Logo" class="d-inline-block align-text-top">
                Elito.
                </a>


                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>


                <div class="collapse navbar-collapse justify-content-center" id="navbarNav">

                    <ul class="navbar-nav nav-underline">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#service">Service</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#portfolio">Portfolio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#blog">Blog</a>
                        </li>
                    </ul>

                </div>

                <button type="button" class="btn btn-color rounded-pill">Resume</button>

            </div>
        </nav>
    </header>

</template>
  
<script>
export default {
    name: 'Header'
}
</script>

<style scoped>

#title-logo {
    font-size: 45px;
    font-weight: 700;
    display: flex;
    align-items: center;
    color: #fff;
    justify-content: center;
    cursor: pointer;
}

.btn {
    padding: 15px;
    font-size: 18px;
    background-color: #41b362;
}

.btn:hover {
    background-color: #278141;
}

nav {
    background-color: rgb(34, 31, 29);
}
</style>