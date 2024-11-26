<template>
  <header class="header">
    <div class="logo">購物網站</div>
    <nav>
      <ul>
        <li><router-link to="/">首頁</router-link></li>
        <li><router-link to="/about">關於我們</router-link></li>
        <li><router-link to="/cart">購物車</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #333;
  color: white;
}

.header .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav ul li {
  font-size: 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

nav ul li a:hover {
  text-decoration: underline;
}
</style>
