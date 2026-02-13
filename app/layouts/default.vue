<template>
  <div class="container">
    <Header />
    <div class="main-wrapper">
      <Sidebar />
      <slot />
    </div>
    <Footer />
  </div>
</template>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}
</style>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  color: #333;
  background: #fff;
}



/* Main wrapper */
.main-wrapper {
  display: grid;
  grid-template-columns: 220px 1fr;
  max-width: 1200px;
  margin: 0 auto;
  width: 100%;
  gap: 30px;
  padding: 30px 20px;
  flex: 1;
}



@media (max-width: 768px) {
  .main-wrapper {
    grid-template-columns: 1fr;
  }
}
</style>