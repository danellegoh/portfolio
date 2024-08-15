<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-body-secondary fixed-top">
            <div class="container-fluid">
                <div class="collapse navbar-collapse">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <RouterLink to="/" class="nav-link">Home</RouterLink>
                        </li>
                        <li class="nav-item">
                            <RouterLink to="/projects" class="nav-link">Projects</RouterLink>
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