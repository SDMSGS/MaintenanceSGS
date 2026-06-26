---
layout: default
title: Contact
permalink: /contact/
---
<section class="page-hero">
  <div class="container">
    <p class="eyebrow">Soumission gratuite</p>
    <h1>Parlez-nous de votre projet.</h1>
  </div>
</section>
<section class="content-section">
  <div class="container contact-grid">
    <div>
      <h2>Nous joindre</h2>
      <p>☎ {{ site.company.phone }}</p>
      <p>✉ {{ site.company.email }}</p>
      <p>⌖ {{ site.company.location }}</p>
      <p class="notice">Si vous utilisez le formulaire, n'oubliez pas d'inscrire correctement vos informations de contact afin qu'on puisse vous répondre.</p>
    </div>
    <form class="form" action="https://api.staticforms.dev/submit" method="POST">
      <input type="hidden" name="apiKey" value="sf_14698ec07b01d4ee884a5c56">
      <input type="hidden" name="redirectTo" value="https://maintenancesgs.com/merci/">
      <input type="text" name="name" placeholder="Nom complet" required>
      <input type="tel" name="phone" placeholder="Téléphone" required>
      <input type="email" name="email" placeholder="Courriel" required>
      <select name="service" required>
        <option>Type de service</option>
        <option>Aménagement</option>
        <option>Entretien</option>
        <option>Déneigement</option>
        <option>Autre</option>
      </select>
      <textarea name="message" placeholder="Décrivez votre projet" required></textarea>
      <button class="btn" type="submit">Envoyer la demande →</button>
    </form>
  </div>
</section>