<script setup>
import { ref } from "vue";
import Header from './components/Header.vue';
</script>

<template>
  <div>
    <Header />

    <main>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
      <p>هذا هو المحتوى الأساسي.</p>
    </main>

    <footer>
      <p>جميع الحقوق محفوظة © 2025</p>
    </footer>
  </div>
</template>

<style scoped>
@import "@/assets/css/main.css";
@import "@/assets/css/style-ltr.css";

p {
  color: red;
}
</style>
