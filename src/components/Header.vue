<template>
  <header>
    <nav class="navbar">
      <div class="site">
        <img src="/src/assets/chef-hat (2) 1.png" alt="Logo"> Foo
      </div>
      
      <div class="navbar-burger" @click="toggleMenu">
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div :class="{'navbar-links': true, 'is-active': isMenuOpen}">
        <a class="nav-link" href="#">Home</a>
        <a class="nav-link" href="#">Menu</a>
        <a class="nav-link" href="#">Contact</a>
        <a class="nav-link" href="#">Shop</a>
      </div>
      <div class="search-container">
        <input type="text" placeholder="Search...">
      </div>
    </nav>
    <HeroSection />
  </header>
</template>s

<script setup>
import { ref } from 'vue';

const isMenuOpen = ref(false);

function toggleMenu() {
  isMenuOpen.value = !isMenuOpen.value;
}
</script>

<style scoped>


header {
  padding: 10px 20px;
}

.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  
}

.site {
  display: flex;
  align-items: center;
  color: #000;
  font-size: 20px;
  font-weight: 700;
}

.site img {
  margin-right: 10px;
}

.navbar-burger {
  display: none;
  cursor: pointer;
  flex-direction: column;
  justify-content: center;
}

.navbar-burger span {
  display: block;
  width: 25px;
  height: 3px;
  background-color: #000;
  margin: 4px 0;
}

.navbar-links {
  display: flex;
  align-items: center;
  
    

}

.nav-link {
  color: #000;
  text-decoration: none;
  font-weight: 300;
  font-size: 20px;
  width: 90px;
}

.search-container {
  margin-right: 200px;
  
}
.search-container input {
  padding: 5px;
  border-radius: 4px;
  border: none;
}

@media (max-width: 768px) {
  .navbar-burger {
    display: flex;
  }
  .navbar-links {
    display: none;
    flex-direction: column;
    align-items: flex-start;
    width: 100%;
  }
  .navbar-links.is-active {
    display: flex;
  }
  .nav-link {
  }
  .search-container {
    width: 100%;
    margin-top: 10px;
  }
  .search-container input {
    width: 100%;
    box-sizing: border-box;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .navbar {
    flex-direction: row;
    justify-content: space-between;
  }
  .navbar-links {
    flex-direction: row;
    align-items: center;
  }
  .search-container {
    margin-left: auto;
  }
}
</style>