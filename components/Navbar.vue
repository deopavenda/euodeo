<template>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <span class="logo">deopavenda</span>
        </div>
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="#about" class="nav-link">About</router-link>
          </li>
          <li class="nav-item">
            <router-link to="#projects" class="nav-link">Projects</router-link>
          </li>
          <li class="nav-item">
            <router-link to="#contact" class="nav-link">Contact</router-link>
          </li>
        </ul>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
  .navbar {
    background-color: #343a40;
    color: white;
    padding: 10px 0;
    font-size: 1.2em;
  }
  
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .navbar-brand {
    font-weight: bold;
    color: #ffffff;
  }
  
  .navbar-nav {
    display: flex;
    list-style-type: none;
    padding: 0;
    margin: 0;
    flex-direction: row; /* Menyusun item dari kiri ke kanan */
  }
  
  .nav-item {
    margin-left: 20px;
  }
  
  .nav-link {
    color: #ffffff;
    text-decoration: none;
    transition: opacity 0.3s;
  }
  
  .nav-link:hover {
    opacity: 0.8;
  }
  </style>
  