<template>
  <div class="container">
    <header class="header">
      <div class="header-content">
        <img src="/logo.svg" style="width: 50px;" />
        <div>
          <h1 style="margin: 0; font-size: 28px">DigitalVision Studio</h1>
          <p style="margin: 5px 0 0 0; font-size: 14px; color: #888">Agence Web & Design</p>
        </div>
        <nav style="display: flex; gap: 25px; margin-left: auto">
          <a href="#services">Services</a>
          <a href="#portfolio">Portfolio</a>
          <a href="#about">À propos</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <div class="main-wrapper">
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

      <main class="content">
        <!-- Hero section -->
        <section style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 60px 30px; border-radius: 10px; margin-bottom: 40px">
          <button style="position: absolute; right: 20px; top: 20px; background: #667eea; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer">Menu</button>
          <h2 style="color: white; font-size: 36px; margin: 0 0 15px 0">Transformez vos idées en réalité</h2>
          <p style="color: #f0f0f0; font-size: 16px; line-height: 1.8; text-justify: justify">Nous créons des expériences numériques exceptionnelles qui engagent vos clients et font croître votre entreprise. Notre équipe de designers et développeurs expérimentés travaille à vos côtés pour donner vie à votre vision.</p>
          <button style="margin-top: 20px; padding: 12px 30px; background: white; color: #667eea; font-weight: bold; border: none; border-radius: 5px; cursor: pointer; font-size: 16px">Démarrer un projet</button>
        </section>

        <!-- Services section -->
        <section id="services">
          <h3 style="font-size: 28px; margin-bottom: 30px">Nos services</h3>
          <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px">
            <div style="border: 1px solid #ddd; padding: 20px; border-radius: 8px">
              <img src="/logo.svg" style="width: 100%; height: 150px; object-fit: cover; border-radius: 5px; margin-bottom: 15px" />
              <h4 style="margin-top: 0; color: #667eea">Design Web</h4>
              <p style="font-size: 14px; color: #666; line-height: 1.6">Création d'interfaces modernes et intuitives qui fascinent vos utilisateurs.</p>
            </div>
            <div style="border: 1px solid #ddd; padding: 20px; border-radius: 8px">
              <img src="/logo.svg" style="width: 100%; height: 150px; object-fit: cover; border-radius: 5px; margin-bottom: 15px" />
              <h4 style="margin-top: 0; color: #667eea">Développement</h4>
              <p style="font-size: 14px; color: #666; line-height: 1.6">Solutions techniques robustes et performantes pour tous vos besoins.</p>
            </div>
            <div style="border: 1px solid #ddd; padding: 20px; border-radius: 8px">
              <img src="/logo.svg" style="width: 100%; height: 150px; object-fit: cover; border-radius: 5px; margin-bottom: 15px" />
              <h4 style="margin-top: 0; color: #667eea">Branding</h4>
              <p style="font-size: 14px; color: #666; line-height: 1.6">Identités visuelles fortes qui marquent et restent mémorables.</p>
            </div>
          </div>
        </section>

        <!-- Portfolio section -->
        <section id="portfolio" style="margin-top: 50px">
          <h3 style="font-size: 28px; margin-bottom: 30px">Derniers projets</h3>
          <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px">
            <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 30px; border-radius: 8px; cursor: pointer; position: relative; height: 200px">
              <img src="/logo.svg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 8px; opacity: 0.3" />
              <div style="position: relative; z-index: 1">
                <h4 style="color: white; margin: 0">Projet A</h4>
                <p style="color: #f0f0f0; font-size: 13px">E-commerce Mode</p>
              </div>
            </div>
            <div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); padding: 30px; border-radius: 8px; cursor: pointer; position: relative; height: 200px">
              <img src="/logo.svg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 8px; opacity: 0.3" />
              <div style="position: relative; z-index: 1">
                <h4 style="color: white; margin: 0">Projet B</h4>
                <p style="color: #f0f0f0; font-size: 13px">Application Fitness</p>
              </div>
            </div>
            <div style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); padding: 30px; border-radius: 8px; cursor: pointer; position: relative; height: 200px">
              <img src="/logo.svg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 8px; opacity: 0.3" />
              <div style="position: relative; z-index: 1">
                <h4 style="color: white; margin: 0">Projet C</h4>
                <p style="color: #f0f0f0; font-size: 13px">Site Immobilier</p>
              </div>
            </div>
            <div style="background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); padding: 30px; border-radius: 8px; cursor: pointer; position: relative; height: 200px">
              <img src="/logo.svg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 8px; opacity: 0.3" />
              <div style="position: relative; z-index: 1">
                <h4 style="color: white; margin: 0">Projet D</h4>
                <p style="color: #f0f0f0; font-size: 13px">Plateforme SaaS</p>
              </div>
            </div>
          </div>
        </section>

        <!-- About section -->
        <section id="about" style="margin-top: 50px; background: #f9f9f9; padding: 40px; border-radius: 10px">
          <h3 style="font-size: 28px; margin-top: 0">À propos de DigitalVision</h3>
          <p style="font-size: 15px; text-justify: justify; line-height: 1.8">Depuis 2015, DigitalVision Studio accompagne les entreprises dans leur transformation numérique. Notre philosophie repose sur l'innovation, la qualité et l'écoute client. Nous travaillons avec des startups comme avec des grands groupes, en adaptant notre approche à chaque enjeu unique. Notre équipe multidisciplinaire combine expertise technique, créativité et stratégie pour livrer des solutions qui dépassent les attentes. Qu'il s'agisse de redéfinir une présence web ou de concevoir une application mobile révolutionnaire, nous mettons tout en œuvre pour transformer vos défis en opportunités.</p>
          <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; margin-top: 30px">
            <div style="text-align: center">
              <div style="font-size: 32px; font-weight: bold; color: #667eea">50+</div>
              <p style="margin: 5px 0 0 0; color: #999">Membres d'équipe</p>
            </div>
            <div style="text-align: center">
              <div style="font-size: 32px; font-weight: bold; color: #667eea">150+</div>
              <p style="margin: 5px 0 0 0; color: #999">Clients mondiaux</p>
            </div>
            <div style="text-align: center">
              <div style="font-size: 32px; font-weight: bold; color: #667eea">15</div>
              <p style="margin: 5px 0 0 0; color: #999">Années d'expérience</p>
            </div>
          </div>
        </section>

        <!-- Contact section -->
        <section id="contact" style="margin-top: 50px; background: white; padding: 40px; border: 2px solid #e0e0e0; border-radius: 10px">
          <h3 style="font-size: 28px; margin-top: 0">Parlons de votre projet</h3>
          <form style="max-width: 500px">
            <div style="margin-bottom: 15px">
              <input type="text" placeholder="Votre nom" style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-family: inherit" />
            </div>
            <div style="margin-bottom: 15px">
              <input type="email" placeholder="votre.email@exemple.com" style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-family: inherit" />
            </div>
            <div style="margin-bottom: 15px">
              <select style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-family: inherit">
                <option>-- Sélectionnez un service --</option>
                <option>Design Web</option>
                <option>Développement</option>
                <option>Branding</option>
                <option>Autre</option>
              </select>
            </div>
            <div style="margin-bottom: 15px">
              <textarea placeholder="Décrivez brièvement votre projet..." style="width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-family: inherit; min-height: 100px; resize: vertical"></textarea>
            </div>
            <div style="margin-bottom: 20px">
              <input type="checkbox" />
              <span style="margin-left: 8px; font-size: 14px">J'accepte les conditions d'utilisation</span>
            </div>
            <button type="submit" style="width: 100%; padding: 12px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; border: none; border-radius: 5px; font-size: 16px; font-weight: bold; cursor: pointer">Envoyer ma demande</button>
          </form>
        </section>
      </main>
    </div>

    <footer class="footer">
      <div class="footer-content">
        <div>
          <h4>DigitalVision</h4>
          <p>Créateurs d'expériences numériques exceptionnelles</p>
        </div>
        <div>
          <h4>Navigation</h4>
          <ul>
            <li><a href="#services">Services</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#about">À propos</a></li>
            <li><a href="#contact">Contact</a></li>
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
  </div>
</template>

<script setup lang="ts">
// Pas de logique particulière nécessaire
</script>

<style scoped>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}

.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  color: #333;
  background: #fff;
}

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
}

.header-content nav a:hover {
  color: #667eea;
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

/* Content */
.content {
  padding: 0;
}

.content h2 {
  font-size: 32px;
  margin: 40px 0 20px 0;
  color: #333;
}

.content h3 {
  font-size: 24px;
  margin: 30px 0 15px 0;
  color: #333;
}

.content h4 {
  margin: 15px 0 10px 0;
  color: #333;
}

.content p {
  line-height: 1.6;
  color: #555;
  margin: 10px 0;
}

.content section {
  margin-bottom: 40px;
}

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

/* Responsive */
@media (max-width: 768px) {
  .main-wrapper {
    grid-template-columns: 1fr;
  }

  .sidebar {
    position: static;
  }

  .header-content {
    flex-wrap: wrap;
  }

  .header-content nav {
    margin-left: 0;
    flex: 1;
    order: 3;
  }

  .footer-content {
    grid-template-columns: 1fr;
  }
}
</style>
