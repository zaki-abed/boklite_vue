<script setup>
import { ref } from "vue";
</script>

<template>
  <div>
    <header class="site-header">
      <div class="logo">
        <!-- <img src="@/assets/images/logo.png" alt="Logo"> -->
      </div>
      <nav>
        <ul>
          <li><a href="#">الرئيسية</a></li>
          <li><a href="#">الخدمات</a></li>
          <li><a href="#">عنّا</a></li>
          <li><a href="#">اتصل بنا</a></li>
        </ul>
      </nav>
    </header>

    <main>
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

.site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  padding: 10px 20px;
  color: white;
}

.site-header .logo img {
  height: 50px;
}

.site-header nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

.site-header nav ul li {
  margin-left: 20px;
}

.site-header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 16px;
}

.site-header nav ul li a:hover {
  text-decoration: underline;
}
</style>
