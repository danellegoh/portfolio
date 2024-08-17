<template>
    <div class="container box">
        <div class="row align-items-center justify-content-center">
            <div class="col-lg-1 col-md-2 col-sm-3">
                <img class="projLogo" :src="projectLogo">
            </div>

            <div class="col-lg-8 col-md-7 col-sm-9">
                <a class="content1 link" target="_blank" :href="companyLink">{{ projectName }}</a>
                <p class="content2">{{ title }}</p>
                <p class="content2">{{ startDate }} - {{ endDate }}</p>
                <p class="content4">{{ description }}</p>
            </div>

            <div class="col-md-3">
                <div class="logoContainer">
                    <img v-for="(skillLogo, index) in skillLogos" :key="index" class="skillLogo" :src="skillLogo">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            projectLogo: {
                type: String,
                required: true,
            },
            companyLink: {
                type: String,
            },
            projectName: {
                type: String,
                required: true,
            },
            title: {
                type: String,
                required: true,
            },
            startDate: {
                type: String,
                required: true,
            },
            endDate: {
                type: String,
                required: true,
            },
            description: {
                type: String,
                required: true,
            },
            skillLogos: {
                type: Array,
                required: true,
            },
        },
    };
    
</script>

<style>
.box {
    border: 1px solid rgb(93, 135, 188);
    padding: 10px;
    border-radius: 12px;
    margin-left: auto;
    margin-bottom: 10px;
    width: 60%;
    vertical-align: middle;
}

.link {
    margin: 0px; 
    text-decoration: none;
}

.projLogo {
    width: 100%;
    display: block;
}

.skillLogo {
    display: block;
    margin: 5px;
    max-width: 40px;
}

.logoContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
</style>