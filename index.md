---
layout: default
title: Inicio
---
<!-- Texto movido debajo del banner -->
<div class="banner-contenido">
  <h1>Des solutions rapides et efficaces</h1>
  <p>Nous sommes le partenaire idéal pour vous aider à atteindre vos objectifs</p>
</div>


<!-- ===== SECCIÓN ACERCA DE ===== -->
<section id="acerca">
  <div class="acerca-container">
    <!-- Imagen lateral -->
    <div class="acerca-img">
      <img src="/assets/img/nosotros.jpg" alt="Sobre nosotros">
    </div>
    <!-- Texto -->
    <div class="acerca-texto">
      <h2>À propos de nous</h2>
      <p>
        Chez CR-INNOV+, nous sommes spécialisés dans les secteurs de la plomberie et de l’électricité, avec trois années d’expérience au service de nos clients. 
		Nos valeurs fondamentales sont la qualité, la fiabilité et l’efficacité.<br>
        Notre philosophie repose sur la satisfaction du client et le travail bien fait, des principes qui nous motivent à dépasser les attentes. 
		Nous intervenons sur des projets locaux et régionaux, en proposant des solutions adaptées à chaque besoin.

      </p>
    </div>
  </div>
</section>



<!-- ===== SECCIÓN SERVICIOS ===== -->

<section id="servicios">
  <div class="servicios-container">
    <h2>Nos Services</h2>

    <!-- Sub-sección 1 -->
    <div class="subservicios">
      <h3>Plomberie</h3>
      <div class="grid">
        <div class="card card1">
          <p>Réparation fuite.</p>
        </div>
        <div class="card card2">
          <p>Remplacement de chauffe-eau.</p>
        </div>
        <div class="card card3">
          <p>Evacuation</p>
        </div>
        <div class="card card4">
          <p>Robineterie</p>
        </div>
        <div class="card card5">
          <p>Installation</p>
        </div>
        <div class="card card6 sin-capa">
          <p></p>
        </div>
      </div>
    </div>

    <!-- Sub-sección 2 -->
    <div class="subservicios">
      <h3>Électricité</h3>
      <div class="grid">
        <div class="card card7">
          <p>Installation de tableaux électriques</p>
        </div>
        <div class="card card8">
          <p>Installation d'éclairage</p>
        </div>
        <div class="card card9">
          <p>Installations d’appareils électriques</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== SECCIÓN PROYECTOS ===== -->
<section id="proyectos">
  <div class="proyectos-container">
    <h2>Points Forts</h2>
    <div class="grid proyectos">
      
      <!-- Proyecto 1 ---->
      <div class="proyecto-card proyecto1">
        <img src="/assets/img/proyecto1.jpg" alt="Projet 1" class="img-proyecto" loading="lazy">
        <h3>Fiabilité</h3>
        <p>Nous garantissons un travail bien fait, réalisé dans les délais et en parfaite adéquation avec vos attentes.</p>
      </div>

      <!-- Proyecto 2 -->
      <div class="proyecto-card proyecto2">
        <img src="/assets/img/proyecto2.jpg" alt="Projet 2" class="img-proyecto" loading="lazy">
        <h3>Satisfaction client</h3>
        <p>Nous plaçons vos priorités au cœur de chaque projet et bâtissons une relation de confiance durable.</p>
      </div>

      <!-- Proyecto 3 --->
      <div class="proyecto-card proyecto3">
        <img src="/assets/img/proyecto3.jpg" alt="Projet 3" class="img-proyecto" loading="lazy">
        <h3>Réactivité et expertise</h3>
        <p>Que ce soit pour un besoin urgent ou un projet à long terme, nous vous apportons des solutions efficaces et professionnelles.</p>
      </div>

      <!-- Proyecto 4 ---->
      <div class="proyecto-card proyecto4">
        <img src="/assets/img/proyecto4.jpg" alt="Projet 4" class="img-proyecto" loading="lazy">
        <h3>Disponibilité</h3>
        <p>Prêts à intervenir rapidement, nous nous adaptons à vos besoins pour des projets locaux ou régionaux.</p>
      </div>

    </div>
  </div>
</section>



<!-- ===== Contacto ===== -->
<section id="contacto" class="contacto">
  <div class="container">
    <h2>Contactez-nous</h2>
    <p class="intro">À l'écoute de vos besoins et suggestions.</p>
    <!-- Formulario de contacto funcional con Formsubmit.co -->
<form
  action="https://formsubmit.co/43b1032b75a9581365524fb6b771eb99"
  method="POST"
  autocomplete="off"
  novalidate
  >

  <!-- Campo de texto para el nombre -->
  <label for="name">Nombre:</label>
  <input
    id="name"
    type="text"
    name="name"
    placeholder="Votre nom"
    required
    minlength="2"
  />

  <!-- Campo de texto para el correo electrónico -->
  <label for="email">Correo electrónico:</label>
  <input
    id="email"
    type="email"
    name="email"
    placeholder="Votre e-mail"
    required
  />

  <!-- Campo de texto para el mensaje -->
  <label for="message">Mensaje:</label>
  <textarea
    id="message"
    name="message"
    placeholder="Votre message"
    rows="5"
    required
  ></textarea>

  <!-- Campo "honeypot" para evitar spam: está oculto y nadie debe llenarlo -->
  <input
    type="text"
    name="_honey"
    style="display:none"
    tabindex="-1"
    autocomplete="off"
  />

  <!-- Campo oculto para redirigir a página de gracias tras envío -->
  <input
    type="hidden"
    name="_next"
    value="https://tusitio.com/gracias.html"
  />

  <!-- Campo opcional para desactivar captcha (usa con precaución) -->
  <!-- <input type="hidden" name="_captcha" value="false" /> -->

  <!-- Botón para enviar el formulario -->
  <button type="submit">Envoyer</button>
  <!-- Redirige tras envío a URL personalizada -->
<input type="hidden" name="_next" value="http://crinnovplusfr.fr" />

<!-- Personaliza el asunto del correo -->
<input type="hidden" name="_subject" value="Nuevo mensaje desde mi CRinnovplusfr" />

</form>

    <!--<form class="contacto-form">
      <div class="form-group">
        <input type="text" placeholder="Votre nom" required>
      </div>
      <div class="form-group">
        <input type="email" placeholder="Votre e-mail" required>
      </div>
      <div class="form-group">
        <textarea placeholder="Votre message" rows="5" required></textarea>
      </div>
      <button type="submit">Envoyer le message</button>
    </form>-->
  </div>
</section>

<!-- ===== SECCIÓN DATOS DE CONTACTO ===== -->
<section id="info-contacto">
  <div class="container">
    <h2>Coordonnées</h2>
    <div class="contacto-grid">
      
        <!--<a href="https://maps.google.com/?q=20+Rue+Louis+David+bat+B+93170" target="_blank" class="contacto-item">
		<i class="fas fa-map-marker-alt"></i>
        <p>20 Rue Louis David bat B 93170 Bagnolet</p>
		</a>-->
      <div class="contacto-item">
		<i class="fas fa-map-marker-alt"></i>
		<p>20 Rue Louis David 93170 Bagnolet</p>
	  </div>

	  
      <a href="https://wa.me/33768762249/?text=Bonjour,%20je%20souhaite%20avoir%20plus%20d'informations." target="_blank" class="contacto-item">
        <i class="fab fa-whatsapp"></i>
        <p>07.68.76.22.49</p>
	 </a>
     
      <a href="mailto:contact@crinnovplusfr.fr" class="contacto-item">
        <i class="fas fa-envelope"></i>
        <p>contact@crinnovplusfr.fr</p>
	  </a>
      
      <!--<div class="contacto-item">
        <i class="fas fa-clock"></i>
        <p>Lunes a Domingo – 24/7</p>
      </div>-->
    </div>
  </div>
</section>
