<template>
    <nav class="navbar">
      <ul class="navbar-list">
        <li class="navbar-item">
          <a href="#bienvenue" class="navbar-link">Bienvenue</a>
        </li>
        <li class="navbar-item">
          <a href="#realisations" class="navbar-link">Mes réalisations</a>
        </li>
        <li class="navbar-item">
          <a href="#quisuisje" class="navbar-link">Qui suis-je ?</a>
        </li>
        <li class="navbar-item">
          <a href="#contact" class="navbar-link">Me contacter</a>
        </li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar',
  };
  </script>
  
  <style scoped>
  .navbar {
    background-color: #333;
    padding: 1rem;
  }
  .navbar-list {
    list-style: none;
    display: flex;
    justify-content: space-around;
    margin: 0;
    padding: 0;
  }
  .navbar-item {
    margin: 0;
  }
  .navbar-link {
    color: #fff;
    text-decoration: none;
    padding: 0.5rem 1rem;
    transition: background-color 0.3s ease;
  }
  .navbar-link:hover {
    background-color: #555;
  }
  </style>