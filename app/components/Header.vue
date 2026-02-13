<template>
  <header class="header">
      <div class="header-content">
        <NuxtLink to="/" style="display: block; text-decoration: none;">
          <img src="/logo.svg" style="width: 50px;" />
        </NuxtLink>
        <div>
          <h1 style="margin: 0; font-size: 28px"><NuxtLink to="/">DigitalVision Studio</NuxtLink></h1>
          <p style="margin: 5px 0 0 0; font-size: 14px; color: #888">Agence Web & Design</p>
        </div>
        <nav style="display: flex; gap: 25px; margin-left: auto">
          <NuxtLink to="/services">Services</NuxtLink>
          <NuxtLink to="/portfolio">Portfolio</NuxtLink>
          <NuxtLink to="/about">À propos</NuxtLink>
          <NuxtLink to="/contact">Contact</NuxtLink>
        </nav>
      </div>
    </header>
</template>

<style scoped>

/* Header */
.header {
  background: white;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
  position: sticky;
  top: 0;
  z-index: 100;
  border-bottom: 3px solid #667eea;
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 16px 20px;
  display: flex;
  align-items: center;
  gap: 20px;
}

.header-content h1 {
  margin: 0;
  font-size: 24px;
  color: #333;

  a {
    color: inherit;
    text-decoration: none;
  }
}

.header-content nav {
  margin-left: auto;
}

.header-content nav a {
  color: #333;
  text-decoration: none;
  font-size: 14px;
  font-weight: 500;
  transition: color 0.3s;

  :global(&.router-link-active) {
    color: #667eea;
  }
}

.header-content nav a:hover {
  color: #667eea;
}

@media (max-width: 768px) {
  .header-content {
    flex-wrap: wrap;
  }

  .header-content nav {
    margin-left: 0;
    flex: 1;
    order: 3;
  }
}


</style>