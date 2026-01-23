<div style="
  position: sticky; 
  top: 0; 
  background: #1a1a1a; 
  padding: 15px; 
  z-index: 1000; 
  border-bottom: 2px solid #0066cc;
">

<center>
<a href="#accueil" style="color:white; font-size:20px; margin:10px; text-decoration:none">🏠 Accueil</a>
<a href="#projets" style="color:white; font-size:20px; margin:10px; text-decoration:none">⚡ Projets</a>
<a href="#competences" style="color:white; font-size:20px; margin:10px; text-decoration:none">🛠️ Compétences</a>
<a href="#contact" style="color:white; font-size:20px; margin:10px; text-decoration:none">📧 Contact</a>
</center>

<div class="content">

<h1 id="accueil">Bonjour et bienvenue !</h1>

<p>Voici mon <strong>portfolio</strong> : vous y trouverez mon parcours, mes réalisations scolaires et professionnelles.</p>
<p>L'électronique étant aussi mon <strong>hobby personnel</strong>, il est agrémenté de projets domestiques.</p>

## Mon parcours {#parcours}

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2024</h2>
      <p>Étudiant ESEO Angers<br>Alternant Groupe Atlantic</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2023</h2>
      <p>BTS Electronique<br>Premiers projets DIY</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2022</h2>
      <p>Bac Pro Electronique<br>Découverte soudure/PCB</p>
    </div>
  </div>
</div>

<style>
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #0066cc;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #0066cc;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}
.left {
  left: 0;
}
.right {
  left: 50%;
}
.right::after {
  left: -16px;
}
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
@media screen and (max-width: 600px) {
  .timeline::after { left: 31px; }
  .container { width: 100%; padding-left: 70px; padding-right: 25px; }
  .container::before { left: 60px; border: medium solid white; border-width: 10px 10px 10px 0; }
  .right::after { left: 15px; }
  .right::before { left: 30px; border: medium solid white; border-width: 10px 0 10px 10px; }
}
</style>


<h2 id="projets">Mes projets</h2>
<!-- Ajoute tes projets ici -->

<h2 id="contact">Contact</h2>
<p>✉️ pierre.papin@example.com<br>
🔗 <a href="https://linkedin.com/in/pierre-papin">LinkedIn</a><br>
📍 Chennevières-sur-Marne, Île-de-France</p>

</div>
