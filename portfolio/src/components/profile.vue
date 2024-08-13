<template>
    <div id="home" class="app">
        <div class="container">
            <div class="row">
                <div class="col-2"></div>

                <div class="col-5">
                    <div class="row title">
                        <h1 class="content1">Hey, I'm Danelle Goh!</h1>
                    </div>
                    <div class="row">
                        <h3 class="content2">An aspiring Software Engineer</h3>
                    </div>
                    <div class="row">
                        <!-- <router-link to="/about" class="btn button">About Me</router-link> -->
                        <a href="#about-section" class="btn button">About Me</a>
                    </div>
                </div>

                <div class="col-3 d-flex justify-content-center">
                    <img src="../assets/profile.jpg" class="img-fluid rounded">
                </div>

                <div class="col-2"></div>
            </div>
            
        </div>

    </div>
</template>

<script>
</script>

<style scoped>
    .container {
        margin-top: 100px;
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
        margin-top: 100px;
        margin-bottom: 15px;
    }

</style>