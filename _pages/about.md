---
layout: single
title: "mgr inż. / MSc. Rafał A. Bogaczewicz"
permalink: /
author_profile: true
---

{% include base_path %}

<style>
  /* 1. ATOMOWA ZIELEŃ I TYPOGRAFIA CV */
  :root { --accent: #16a085; }
  
  h1, .page__title { color: var(--accent) !important; }

  /* Stylizacja nagłówków wzorowana na CV (Nagłówek + Linia) */
  .cv-style-header {
    color: var(--accent) !important;
    border-bottom: 1px solid #ccc;
    margin-top: 40px;
    margin-bottom: 20px;
    font-size: 1.4em;
    font-weight: bold;
    display: block;
    width: 100%;
  }

  .cv-content-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    margin-bottom: 20px;
  }

  .lang-pl { text-align: justify; font-size: 0.95em; }
  .lang-en { text-align: justify; font-size: 0.85em; font-style: italic; opacity: 0.75; border-left: 1px solid #eee; padding-left: 15px; }

  ul.cv-list { list-style-type: none; padding-left: 0; }
  ul.cv-list li { margin-bottom: 10px; position: relative; padding-left: 20px; }
  ul.cv-list li::before { content: "•"; color: var(--accent); position: absolute; left: 0; font-weight: bold; }
</style>

<div class="page-home">

  <!-- SEKCJA 1: BIO -->
  <span class="cv-style-header">O mnie / About Me</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Jestem fizykiem teoretykiem i doktorantem na <b>Politechnice Wrocławskiej</b>. W moich badaniach łączę matematyczną rygorystyczność z opisem procesów kwantowych, wierząc, że nauka to nie tylko zawód, ale i formacja charakteru.
    </div>
    <div class="lang-en">
      Theoretical physicist and PhD student at <b>Wrocław University of Science and Technology</b>. In my research, I combine mathematical rigor with quantum process descriptions, believing that science is both a profession and a character-building journey.
    </div>
  </div>

  <!-- SEKCJA 2: EDUKACJA (Skrócona z CV) -->
  <span class="cv-style-header">Edukacja / Education</span>
  <div class="cv-content-grid">
    <div>
      <ul class="cv-list lang-pl">
        <li><b>Doktorat (w trakcie)</b>, Fizyka Teoretyczna, PWr</li>
        <li><b>Magister Inżynier</b>, Fizyka Techniczna, PWr</li>
      </ul>
    </div>
    <div>
      <ul class="cv-list lang-en">
        <li><b>Ph.D. Candidate</b>, Theoretical Physics, WUST</li>
        <li><b>M.Sc. Eng.</b>, Technical Physics, WUST</li>
      </ul>
    </div>
  </div>

  <!-- SEKCJA 3: BADANIA / RESEARCH -->
  <span class="cv-style-header">Badania / Research</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Moja praca koncentruje się na optyce kwantowej ciała stałego, dynamice fononów oraz modelowaniu kwantowych układów otwartych.
    </div>
    <div class="lang-en">
      My work focuses on solid-state quantum optics, phonon dynamics, and modeling of open quantum systems.
    </div>
  </div>

  <!-- SEKCJA 4: PASJE (To, co przyciąga) -->
  <span class="cv-style-header">Poza nauką / Beyond Science</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Pasjonat gór i wspinaczki. Szukam wyzwań wymagających dyscypliny i wierności zasadom – zarówno w równaniach, jak i na szlaku.
    </div>
    <div class="lang-en">
      Mountain and climbing enthusiast. I seek challenges requiring discipline and integrity – both in equations and on the trail.
    </div>
  </div>

  <div style="margin-top: 60px; text-align: center; opacity: 0.6; font-style: italic;">
    "Pasjonat odkrywania świata, zarówno w równaniach, jak i dosłownie ;)"
  </div>

</div>
