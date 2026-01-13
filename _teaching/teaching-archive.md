---
layout: archive
title: "Dydaktyka / Teaching"
permalink: /teaching-archive/
author_profile: true
---

{% include base_path %}

<style>
  /* 2. ATOMOWE WYMUSZENIE ZIELENI DLA TYTUŁU STRONY - BRAK KOMPROMISÓW */
  
  /* Jasny tryb */
  .page__title, .archive__title, h1, .page-teaching h1, 
  header h1, .archive h1 {
    color: #0e7a3a !important;
  }

  /* Bezwzględne wymuszenie dla trybu ciemnego */
  @media (prefers-color-scheme: dark) {
    html, body, html.dark, [data-theme='dark'] {
      --any-header-color: #11ee4a !important;
    }
    .page__title, .archive__title, h1, .page-teaching h1, 
    header h1, .archive h1, .page__content h1 {
      color: #11ee4a !important;
    }
  }

  /* Dodatkowe uderzenie w specyficzne klasy Jekylla 2026 */
  html.dark .page__title, 
  [data-theme='dark'] .page__title,
  html.dark h1,
  [data-theme='dark'] h1 {
    color: #11ee4a !important;
  }
</style>


<div class="page-teaching">
  <!-- Twój cytat JP2 -->
  <div class="values-header" style="font-size: 0.8em; margin-bottom: 35px; border-left: 2px solid var(--global-text-color); padding-left: 15px; line-height: 1.3;">
    <div style="font-style: italic; color: var(--global-text-color);">„Musicie od siebie wymagać, nawet gdyby inni od was nie wymagali”.</div>
    <div style="font-style: italic; margin-top: 2px; color: var(--global-text-color); opacity: 0.75;">"You must demand of yourselves even if others do not demand of you."</div>
    <div style="font-weight: bold; margin-top: 2px; color: var(--global-text-color); opacity: 0.55;">— Jan Paweł II / John Paul II</div>
  </div>

  <div class="teaching-list">
    <h2 style="border-bottom: 1px solid #ccc; padding-bottom: 10px;">Archiwum zajęć / Past Semesters</h2>
    {% for post in site.teaching %}
      {% unless post.title contains "2025/2026" or post.title contains "Archive" %}
        <div style="margin-bottom: 20px;">
          <div style="font-size: 1.2em; font-weight: bold; color: var(--global-text-color);">{{ post.title }}</div>
          <div style="color: var(--global-text-color); opacity: 0.9;">{{ post.content }}</div>
          <a href="{{ post.url }}">Szczegóły przedmiotu / Course details</a>
        </div>
      {% endunless %}
    {% endfor %}
  </div>
</div>
