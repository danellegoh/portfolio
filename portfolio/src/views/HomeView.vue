<template>
  <main>
    <profile />
    <!-- <bubbles /> -->
    <about />
    <contact />
    <div class="bottomBtn">
      <button class="btn button" id="backToTopBtn" @click="scrollToTop">Back to Top</button>
    </div>
  </main>
</template>

<script setup>
import { onMounted } from 'vue';
import profile from '../components/profile.vue'
// import bubbles from '../components/bubbles.vue'
import about from '../components/about.vue'
import contact from '../components/contact.vue'

// scroll to top function
const scrollToTop = () => {
  window.scrollTo({ top: 0, behavior: 'smooth' });
};

// set up the back-to-top button behaviour
onMounted(() => {
  const backToTopBtn = document.getElementById('backToTopBtn');
});

</script>

<style>
  .button {
    background-color: rgb(165, 189, 213);
    color: white;
    padding: 10px;
    text-align: center;
    border-radius: 12px;
    width: 200px;
    transition-duration: 0.2s;
    margin-left: 10px;
    margin-top: 30px;
  }

  .button:hover {
    background-color: rgb(93, 135, 188);
    color: white;
  }

  .bottomBtn {
    display: flex;
    justify-content: center;
    margin-bottom: 50px;
  }

</style>
