---
title: ""
---

<!-- GOOGLE FONT: SOURCE SERIF PRO -->
<link href="https://fonts.googleapis.com/css2?family=Source+Serif+Pro:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
  font-family: 'Source Serif Pro', serif;
}

/* Otsikko pienemmäksi mutta edelleen vahva */
h2 {
  font-size: 1.6rem;
  font-weight: 600;
  letter-spacing: -0.2px;
  margin-bottom: 16px;
}

/* Kirjoitukset/projektit -otsikko pienemmäksi */
h3 {
  font-size: 1.25rem;
  font-weight: 600;
  margin-top: 20px;
  margin-bottom: 8px;
}

/* Pinkki projektilinkki */
.project-link {
  font-size: 1.05em;
  font-weight: 500;
  color: hotpink;
  text-decoration: none;
  display: block;
  margin: 6px 0;
}

.project-link:hover {
  text-decoration: underline;
}

/* Pinkki viiva */
.divider {
  width: 100%;
  height: 2px;
  background-color: hotpink;
  margin: 8px 0 12px 0;
  position: relative;
}

/* Työkalurivi oikeaan alakulmaan */
.tools {
  position: absolute;
  right: 0;
  bottom: -22px;
  font-size: 0.9rem;
  font-weight: 600;       /* lihavoitu */
  color: black;           /* musta teksti */
}

.tools span {
  color: hotpink;         /* pinkit pystyviivat */
  font-weight: 600;
}
</style>

<!-- YHTEYSTIEDOT OIKEALLE YLÖS -->
<div style="position:absolute; top:10px; right:10px; text-align:right; font-size:0.9em;">
  <strong>📬 Yhteystiedot</strong><br>
  leenaeleino@gmail.com<br>
  0443390314
</div>

<h2>Hei! Olen Leena, ekonomisti.<br>Tervetuloa portfolioni sivuille.</h2>

<!-- KUVA + TEKSTI VIEREKKÄIN -->
<div style="display:flex; align-items:flex-start; gap:20px;">

  <img src="kuva.jpg" width="90" style="border-radius:10px;">

  <div style="max-width:600px; font-size:0.95rem; line-height:1.45;">
    <p>
      Rehellisesti, minua eivät kiinnosta valmiit narratiivit. Haluan tarkistaa faktat itse ja muodostaa näkemykseni datan perusteella.
    </p>

    <p>
      Mutta aina datakaan ei kerro kaikkea. Yksittäinen mittari voi antaa taloudesta hyvin erilaisen kuvan riippuen siitä, millä tavoin se on mitattu.
    </p>

    <p>
      <strong>Esimerkiksi Suomen työllisyysaste</strong> kertoo, kuinka suuri osuus väestöstä on työllisiä, mutta ei kerro tehtyjen työtuntien määrästä, työn laadusta tai työmarkkinoiden rakenteellisista muutoksista.
    </p>

    <p>
      Siksi haluan mennä lukujen taakse. Mitä olennaista voi datasta jäädä puuttumaan, ja miten se vaikuttaa siihen, mitä siitä voi oikeasti päätellä.
    </p>
  </div>

</div>

<div class="divider">
  <div class="tools">
    <strong>R <span>|</span> SAS <span>|</span> Power BI <span>|</span> SQL <span>|</span> Tableau</strong>
  </div>
</div>

<h3>📁 Kirjoitukset/projektit</h3>

<p><a class="project-link" href="opinion.html">📝 Ekonomistin näkemyksiä</a></p>
<p><a class="project-link" href="korkoy.pdf">📈 Korkoympäristön normalisoituminen ja tuottovaatimus</a></p>
<p><a class="project-link" href="asuntorahasto_portfolio.pdf">🏢 Kiinteistörahastojen riskien tarkastelu R:llä</a></p>
<p><a class="project-link" href="EDP_portfolio.pdf">📉 EDP‑velan analyysi</a></p>
