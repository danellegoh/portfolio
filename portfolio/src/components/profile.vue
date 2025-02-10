<template>
    <div id="home" class="app">
        <div class="container">
            <div class="row gy-4">
                <div class="col-lg-2"></div>

                <div class="col-lg-5 col-md-6 d-flex flex-column justify-content-center">
                    <div class="row title">
                        <h1 class="content1">Hey, I'm Danelle Goh!</h1>
                    </div>
                    <div class="row">
                        <h3 class="content2">Problem solver with a passion for driving meaningful solutions</h3>
                    </div>
                    <div class="row">
                        <!-- <router-link to="/about" class="btn button">About Me</router-link> -->
                        <a href="#about-section" class="btn button">About Me</a>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 d-flex justify-content-center">
                    <img src="../assets/profile.jpg" class="img-fluid rounded profile-image">
                </div>

                <div class="col-lg-2"></div>
            </div>
            
        </div>

    </div>
</template>

<script>
</script>

<style scoped>
    .container {
        margin-top: 200px;
    }
    
    img {
        max-width: 100%;
        max-height: 100%;
        object-fit: cover; 
    }
    
    h1 {
        font-weight: bolder;
    }

    .title {
        margin-bottom: 15px;
    }

    @media (max-width: 767px) {
        .profile-image {
            width: 60%; 
            height: 60%;
        }
    }

</style>