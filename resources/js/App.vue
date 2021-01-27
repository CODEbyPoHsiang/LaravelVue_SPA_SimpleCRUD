<template>
  <div class="container">
     <div class="text-center" style="margin: 20px 0px 20px 0px;">
            <span class="text-secondary">Laravel & Vue CRUD Single Page Application (SPA) Tutorial</span>
        </div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="collapse navbar-collapse">
        <div class="navbar-nav">
          <router-link to="/" class="nav-item nav-link">產品清單</router-link>
          <router-link to="/create" class="nav-item nav-link">建立產品</router-link>
        </div>
      </div>
    </nav>
    <br />
    <router-view> </router-view>
  </div>
</template>
 
<script>
export default {};
</script>