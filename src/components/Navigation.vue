<template>
  <nav class="navbar navbar-expand-md navbar-dark bg-dark mb-4">
    <div class="container-fluid">
      <ul class="navbar-nav me-auto mb-2 mb-md-0">
        <li class="nav-item">
          <router-link to="/" active-class="active">Home</router-link>
        </li>
        -
        <li class="nav-item">
          <router-link to="/create" active-class="active">Create Product</router-link>
        </li>
        -
        <li class="nav-item">
          <router-link to="/products" active-class="active">Products</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
import router from '../router';

export default {
    name: "Navigation",
    components: { router }
};
</script>

<style>
.active{
  color: aquamarine;
}
</style>