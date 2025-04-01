---
title: Getting started
abstract: A guide to quickly setting up your site with this theme.
slug: "chapter1"
---

## Определения

{% include definition.html num="1" content="
**Производная** функции в точке — это предел отношения приращения функции к приращению аргумента при стремлении приращения аргумента к нулю:

\\[ f'(x) = \\lim_{\\Delta x \\to 0} \\frac{f(x+\\Delta x) - f(x)}{\\Delta x} \\]
" %}

## Упражнения

{% include exercise.html content="
Найдите производную функции \\( f(x) = x^2 + 3x - 5 \\).
" %}

{% include exercise.html content="
Докажите, что производная суммы функций равна сумме производных.
" %}

## Вопросы

{% include question.html content="
Каков геометрический смысл производной?
" %}

{% include question.html content="
Как связаны непрерывность и дифференцируемость функции?
" %}

This is an example chapter page.

Рассмотрим формулу \\(\\forall x Sx\\)

{% include quiz.html 
  id="3" 
  type="single" 
  question="Чему равен интеграл \\(\\int e^x dx\\)?" 
  options="\\(e^x + C\\)|\\(x e^x + C\\)|\\(\\frac{e^{x+1}}{x+1} + C\\)" 
  answer="1" 
%}

{% include figure.html
    caption="Модель"
    url="/assets/demo/Kripke model.png"
    class="row"
%}

{% include quiz.html 
  id="4" 
  type="multiple" 
  question="В каких мирах мирах модели на рис. выше выполняется формула \\(\\Box p \wedge \neg p\\)?" 
  options="\\(w_1\\)|\\(w_2\\)|\\(w_3\\)|\\(w_4\\)|\\(w_5\\)" 
  answer="1|2|5" 
%}

{% include quiz.html 
  id="5" 
  type="single" 
  question="Что представляет собой формула \\(\\frac{d}{dx} \\left( \\frac{u}{v} \\right) = \\frac{v \\frac{du}{dx} - u \\frac{dv}{dx}}{v^2}\\)?" 
  options="Правило дифференцирования частного|Правило дифференцирования произведения|Цепное правило" 
  answer="1" 
%}

{% include quiz.html 
  id="6" 
  type="single" 
  question="Чему равна производная \\(\\frac{d}{dx} \\sin(x)\\)?" 
  options="\\(\\cos(x)\\)|\\(-\\cos(x)\\)|\\(\\sin(x)\\)" 
  answer="1" 
  hint="Вспомните основные правила дифференцирования тригонометрических функций. Производная синуса равна косинусу." 
%}

{% include quiz.html 
  id="7" 
  type="multiple" 
  question="Какие из этих утверждений верны для квадратных матриц?" 
  options="\\(\\det(A^T) = \\det(A)\\)|\\(\\det(AB) = \\det(A) + \\det(B)\\)|\\(\\det(A^{-1}) = 1/\\det(A)\\)" 
  answer="1|3" 
  hint="Определитель произведения матриц равен произведению определителей. Определитель транспонированной матрицы равен определителю исходной." 
%}

[Learn more about getting started with this theme.]({{ site.baseurl }}/index.html#getting-started)

---
```
This file is located at: {{ page.path }}
```
---
