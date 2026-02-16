<template>
  <footer class="footer">
      <div class="footer-content">
        <div>
          <h4>DigitalVision</h4>
          <p>Créateurs d'expériences numériques exceptionnelles</p>
        </div>
        <div>
          <h4>Navigation</h4>
          <ul>
            <li><NuxtLink to="/services">Services</NuxtLink></li>
            <li><NuxtLink to="/portfolio">Portfolio</NuxtLink></li>
            <li><NuxtLink to="/about">À propos</NuxtLink></li>
            <li><NuxtLink to="/contact">Contact</NuxtLink></li>
          </ul>
        </div>
        <div>
          <h4>Infos</h4>
          <p>Email: hello@digitalvision.com</p>
          <p>Tél: +33 1 234 567 890</p>
          <p>Adresse: 123 Rue de la Tech, Paris 75001</p>
        </div>
      </div>
      <div style="border-top: 1px solid #555; margin-top: 30px; padding-top: 20px; text-align: center; font-size: 13px">
        <p>&copy; 2026 DigitalVision Studio. Tous droits réservés.</p>
      </div>
    </footer>
</template>

<style scoped>

/* Footer */
.footer {
  background: #2d2d2d;
  color: #f0f0f0;
  padding: 40px 20px;
  margin-top: auto;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
}

.footer-content h4 {
  color: white;
  margin-top: 0;
  margin-bottom: 10px;
}

.footer-content p {
  font-size: 13px;
  margin: 5px 0;
  color: #ccc;
}

.footer-content ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer-content li {
  margin: 8px 0;
}

.footer-content a {
  color: #ccc;
  text-decoration: none;
  font-size: 13px;
}

.footer-content a:hover {
  color: white;
}

@media (max-width: 768px) {
  .footer-content {
    grid-template-columns: 1fr;
  }
}
</style>