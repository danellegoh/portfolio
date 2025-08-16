<template>
    <div>
        <nav class="navbar navbar-expand-md bg-body-secondary fixed-top">
            <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <RouterLink to="/" class="nav-link">Home</RouterLink>
                        </li>
                        <li class="nav-item">
                            <RouterLink to="/experience" class="nav-link">Experience</RouterLink>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
    
</template>

<style scoped>
    .container-fluid {
        padding: 20px;
    }

    li {
        margin-right: 20px;
    }

    nav {
        font-weight: 600;
    }

    .nav-link {
        color: rgb(70, 80, 90);
    }

    .nav-link:hover {
        color: rgb(93, 135, 188);
    }

</style>