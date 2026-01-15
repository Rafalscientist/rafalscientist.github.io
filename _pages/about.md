<style>
  /* 1. TYTUŁ GŁÓWNY - MORSKA ZIELEŃ */
  h1.page__title { 
    color: #16a085 !important; 
    margin-bottom: 30px !important;
  }

  /* 2. ADAPTACYJNE NAGŁÓWKI SEKCJI */
  .cv-style-header {
    color: var(--global-text-color) !important;
    border-bottom: 1px solid #ccc;
    margin-top: 35px;
    margin-bottom: 15px;
    font-size: 1.1em; 
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

  /* RWD dla urządzeń mobilnych */
  @media (max-width: 600px) {
    .cv-content-grid { grid-template-columns: 1fr; }
  }

  /* WSPÓLNY STYL DLA OBU JĘZYKÓW */
  .lang-pl, .lang-en { 
    text-align: justify; 
    font-size: 0.9em; 
    line-height: 1.5; 
  }

  /* RÓŻNICA TYLKO W KOLORZE/PRZEZROCZYSTOŚCI DLA EN */
  .lang-en { 
    opacity: 0.7; 
    border-left: 1px solid #eee; 
    padding-left: 15px; 
  }
</style>
