<!-- Header.vue -->
<template>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light" data-bs-theme="dark">
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
                            <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Service</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Portfolio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contact</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Blog</a>
                        </li>
                    </ul>

                </div>

                <button type="button" class="btn btn-success">Resume</button>

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

</style>