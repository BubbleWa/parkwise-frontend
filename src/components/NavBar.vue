<template>
  <header class="navbar-header">
    <div class="navbar-container">
      <div class="navbar-left">
        <img src="../assets/logo.png" alt="ParkWise logo" class="logo" />
        <span class="brand">ParkWise</span>
      </div>
      <nav class="navbar-nav">
        <a href="#">Home</a>
        <a href="#">Smart Parking</a>
        <a href="#">Eco comute</a>
        <a href="#">Ownership trends</a>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.navbar-header {
  background: #e6eef7;
  padding: 0;
}

.navbar-container {
  max-width: 1300px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  padding: 16px 32px;
  justify-content: space-between;
}

.navbar-left {
  display: flex;
  align-items: center;
}

.logo {
  width: 60px;
  height: 60px;
  margin-right: 10px;
}

.brand {
  font-size: 2.9rem;
  font-weight: 800;
  color: #212121;
  margin-right: 24px;
  font-family: 'Georgia', serif;
}

.navbar-nav {
  display: flex;
  gap: 32px;
}

.navbar-nav a {
  font-size: 1.6rem;
  color: #222;
  text-decoration: none;
  font-weight: 500;
  font-family: 'Georgia', serif;
  transition: color 0.2s;
}

.navbar-nav a:hover {
  color: #2563eb;
  text-decoration: underline;
}
</style>
