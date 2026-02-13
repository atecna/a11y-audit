<template>
  <aside class="sidebar">
        <h3 style="margin-top: 0">Nos services</h3>
        <ul>
          <li>Design Web</li>
          <li>Développement</li>
          <li>Branding</li>
          <li>Marketing</li>
          <li>Consulting UX</li>
        </ul>
        <div style="margin-top: 30px; padding: 15px; background: #e8f4f8; border-radius: 5px">
          <img src="/logo.svg" style="width: 100%; height: 80px; border-radius: 4px; margin-bottom: 10px" />
          <p style="font-size: 12px; color: #666">Nos derniers travaux</p>
        </div>
        <div style="margin-top: 20px">
          <p style="font-size: 13px; color: #999">Clients satisfaits: 500+</p>
          <p style="font-size: 13px; color: #999">Projets réalisés: 1200+</p>
        </div>
      </aside>
</template>

<style scoped>
/* Sidebar */
.sidebar {
  background: #f5f5f5;
  padding: 20px;
  border-radius: 8px;
  height: fit-content;
  position: sticky;
  top: 120px;
}

.sidebar h3 {
  margin: 0 0 15px 0;
  font-size: 16px;
  color: #333;
}

.sidebar ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.sidebar li {
  padding: 8px 0;
  font-size: 14px;
  color: #666;
}

@media (max-width: 768px) {
  .sidebar {
    position: static;
  }
}
</style>