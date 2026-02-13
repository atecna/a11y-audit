<template>
  <main class="contact-page">
    <h1>Contactez-nous</h1>
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
</template>