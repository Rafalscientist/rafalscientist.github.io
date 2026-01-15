<style>
  /* 1. TWOJA MARKA - NUKLEARNA MORSKA ZIELEŃ TYLKO DLA GŁÓWNEGO TYTUŁU */
  :root, html, body, #main, [class*="page__inner"] {
    --primary-color: #16a085 !important;
  }
  
  /* Główny tytuł strony (Imię i Nazwisko) */
  h1.page__title { 
    color: #16a085 !important; 
    margin-bottom: 30px !important;
  }

  /* 2. ADAPTACYJNE NAGŁÓWKI SEKCJI (Czarny w Light / Biały w Dark) */
  .cv-style-header {
    /* var(--global-text-color) to inteligentna zmienna Jekylla */
    color: var(--global-text-color) !important;
    border-bottom: 1px solid #ccc;
    margin-top: 35px;
    margin-bottom: 15px;
    font-size: 1.1em; /* Mniejsza czcionka, bardziej elegancka */
    font-weight: bold;
    display: block;
    width: 100%;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  /* 3. SIATKA TREŚCI */
  .cv-content-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
    margin-bottom: 20px;
  }

  .lang-pl { text-align: justify; font-size: 0.9em; line-height: 1.5; }
  .lang-en { 
    text-align: justify; 
    font-size: 0.85em; 
    font-style: italic; 
    opacity: 0.7; 
    border-left: 1px solid #eee; 
    padding-left: 15px; 
  }

  /* Kropki list w kolorze akcentu dla smaku */
  ul.cv-list { list-style-type: none; padding-left: 0; margin: 0; }
  ul.cv-list li { margin-bottom: 8px; position: relative; padding-left: 15px; }
  ul.cv-list li::before { content: "•"; color: #16a085; position: absolute; left: 0; }
</style>

<div class="page-home">

  <!-- SEKCJA 1 -->
  <span class="cv-style-header">O mnie / About Me</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Jestem fizykiem teoretykiem i doktorantem na <b>Politechnice Wrocławskiej</b>. W badaniach dążę do matematycznej precyzji w opisie świata kwantowego, wierząc, że rzetelność jest fundamentem charakteru.
    </div>
    <div class="lang-en">
      Theoretical physicist and PhD student at <b>Wrocław University of Science and Technology</b>. I strive for mathematical precision in describing the quantum world, believing that integrity is the foundation of character.
    </div>
  </div>

  <!-- SEKCJA 2 -->
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

  <!-- SEKCJA 3 -->
  <span class="cv-style-header">Badania / Research</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Moja praca koncentruje się na optyce kwantowej ciała stałego, dynamice fononów oraz modelowaniu kwantowych układów otwartych.
    </div>
    <div class="lang-en">
      My work focuses on solid-state quantum optics, phonon dynamics, and modeling of open quantum systems.
    </div>
  </div>

  <!-- STOPKA -->
  <div style="margin-top: 50px; text-align: center; opacity: 0.6; font-style: italic; font-size: 0.85em;">
    <hr style="width: 30%; margin: 20px auto; border-top: 1px solid #eee;">
    "Pasjonat odkrywania świata, zarówno w równaniach, jak i dosłownie ;)"
  </div>

</div>
