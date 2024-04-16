---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
---
layout: page
title: Przekraczaj granice możliwości z technologiami Imago3D
permalink: /home/
---

# Witaj w Imago3D
Twoim partnerze w tworzeniu innowacyjnych rozwiązań z zakresu widzenia komputerowego i uczenia maszynowego. Oferujemy kompleksowe usługi od modelowania danych po dedykowane rozwiązania sprzętowe, które pomagają firmom przekształcać branże.
## Nasze Produkty

<div class="grid__wrapper">
{% for product in site.data.products %}
  <div class="column">
    <a href="{{ product.url }}">
      <img src="{{ product.image }}" alt="{{ product.name }}" style="width:100%">
      <h3>{{ product.name }}</h3>
    </a>
    <p>{{ product.description }}</p>
  </div>
{% endfor %}
</div>

<style>
.grid__wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.column {
  text-align: center;
}
</style>

## Nasze Kompetencje
### Widzenie Komputerowe
Rozwój zaawansowanych algorytmów do analizy i interpretacji obrazów w czasie rzeczywistym.

### Głębokie Uczenie i Klasyfikacja Obrazów
Projektowanie modeli AI do automatycznego rozpoznawania wzorców i obiektów.

### Dedykowane Rozwiązania Sprzętowe
Tworzenie niestandardowych modułów i systemów sprzętowych na potrzeby specyficzne klientów.

## Opinie Klientów
"Zobacz, jak inne firmy zrewolucjonizowały swoje operacje dzięki naszym rozwiązaniom. [Wstaw tutaj opinie klientów i studia przypadków]."

## Skontaktuj się z nami
Chcesz dowiedzieć się więcej? Skontaktuj się z nami już dziś, aby omówić, jak możemy pomóc Twojej firmie osiągnąć nowe horyzonty technologiczne.
[Skontaktuj się z nami](#)
[Odwiedź nasze produkty](#)
