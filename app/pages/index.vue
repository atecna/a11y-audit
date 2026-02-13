<template>
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
  </main>
</template>

<style scoped>
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
</style>
