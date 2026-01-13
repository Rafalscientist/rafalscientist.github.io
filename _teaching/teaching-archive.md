---
layout: archive
title: "Dydaktyka / Teaching"
permalink: /teaching-archive/
author_profile: true
---

{% include base_path %}

<style>
  /* Pancerne style tytułu */
  .page__title, .archive__title, h1, .page-teaching h1 { color: #0e7a3a !important; }
  @media (prefers-color-scheme: dark) {
    .page__title, .archive__title, h1, .page-teaching h1 { color: #11ee4a !important; }
  }
  
  /* Pancerne style linków w archiwum */
  .page-teaching .teaching-list a { color: #0e7a3a !important; text-decoration: none !important; border-bottom: 1px solid transparent !important; }
  @media (prefers-color-scheme: dark) {
    .page-teaching .teaching-list a { color: #11ee4a !important; }
  }
  .page-teaching .teaching-list a:hover { color: #11ee88 !important; border-bottom: 1px solid #11ee88 !important; }
</style>

<div class="page-teaching">
  <!-- Twój cytat JP2 -->
  <div class="values-header" style="font-size: 0.8em; margin-bottom: 35px; border-left: 2px solid var(--global-text-color); padding-left: 15px; line-height: 1.3;">
    <div style="font-style: italic; color: var(--global-text-color);">„Musicie od siebie wymagać, nawet gdyby inni od was nie wymagali”.</div>
    <div style="font-weight: bold; margin-top: 2px; color: var(--global-text-color); opacity: 0.55;">— Jan Paweł II</div>
  </div>

  <div class="teaching-list">
    <h2 style="border-bottom: 1px solid #ccc; padding-bottom: 10px;">Archiwum zajęć / Past Semesters</h2>
    {% for post in site.teaching %}
      {% unless post.title contains "2025/2026" %}
        <div style="margin-bottom: 20px;">
          <div style="font-size: 1.2em; font-weight: bold;">{{ post.title }}</div>
          <div>{{ post.content }}</div>
          <a href="{{ post.url }}">Szczegóły przedmiotu / Course details</a>
        </div>
      {% endunless %}
    {% endfor %}
  </div>
</div>
