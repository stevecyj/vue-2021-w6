<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <a class="navbar-brand" href="#">前台導覽列</a>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
          <router-link class="nav-link" to="/">首頁</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/products">產品列表</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/cart">前台購物車</router-link>
        </li>
      </ul>
    </div>
  </div>
  </nav>
  <hr>
  <router-view></router-view>
</template>
