<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar w/ text</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <router-link class="nav-link" to="/">
            Home
            <span class="sr-only">(current)</span>
          </router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="login">Login</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="register">Register</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="profile">Profile</router-link>
        </li>
      </ul>
      <span class="navbar-text">Navbar text with an inline element</span>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>
</style>