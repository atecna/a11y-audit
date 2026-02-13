<template>
  <main class="portfolio-page">
    <h1>Notre Portfolio</h1>
    <p>Explorez nos projets récents et découvrez comment nous avons aidé nos clients à atteindre leurs objectifs.</p>
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
  </main>
</template>