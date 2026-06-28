---
layout: page
title: "Уменьшаем"
excerpt: "Как помочь животным."
---
Подписаться: <a href="{{ site.vk }}">ВКонтакте</a>, <a href="{{ site.telegram }}">Telegram</a>

---

<style>
  table {
    table-layout: fixed;
  }
  tr {
    height: 200px;
    margin: 0.5em;
    padding: 0.5em;
  }
  td {
    vertical-align: top;
    overflow: auto;
    margin: 0.5em;
    padding: 0.5em;
  }
  .cell {
    height: 400px;
    overflow: auto;
    margin: 0;
    padding: 0;
  }
  h3 {
    margin: 0;
  }
  img {
    margin: 0;
    padding: 0;
  }
  .over {
    font-family: Angeme;
    position: absolute;
    bottom: 0.2em;
    left: 0.4em;
    color: white;
    font-size: 2em;
    text-shadow: 2px 0 #000, -2px 0 #000, 0 2px #000, 0 -2px #000,
             1px 1px #000, -1px -1px #000, 1px -1px #000, -1px 1px #000;
  }
  .over-r {
    font-family: Angeme;
    color: black;
    font-size: 2em;
    text-align: center;
    margin-bottom: 0.2em;
    margin-right: 3em;
  }
  .start {
    font-family: Angeme;
    color: black;
    font-size: 2em;
  }
  .mobile {
    display: none;
  }
  .desktop {
    display: block;
  }
  @media (max-width: 768px) {
    .desktop {
      display: none;
    }
    .mobile {
      display: block;
    }
  }
</style>

<table class="desktop" style="margin-bottom: 0; padding-bottom: 0">

<tr>
<td style="width: 30%">
<table><tr style="padding: 0; margin: 0;"><td style="width: 50%; padding: 0; margin: 0"><div style="position: relative"><img src="assets/images/start.jpg"/></div></td><td style="width: 50%; padding: 0; margin: 0; vertical-align: bottom"><div class="over-r">начните<br>здесь</div></td></tr></table>
</td>
<td style="width: 30%">{% include section.html s="basic" %}</td>
<td style="width: 30%">{% include section.html s="comm" %}</td>
</tr>

</table>

<table class="desktop" style="padding-top: 0; margin-top: 0">

<tr>
<td style="width: 30%"><div class="cell">{% include list.html s="red" %}</div></td>
<td style="width: 30%"><div class="cell">{% include list.html s="basic" %}</div></td>
<td style="width: 30%"><div class="cell">{% include list.html s="comm" %}</div></td>
</tr>

<tr>
<td>{% include section.html s="fur" %}</td>
<td>{% include section.html s="beauty" %}</td>
<td>{% include section.html s="zoo" %}</td>
</tr>

<tr>
<td><div class="cell">{% include list.html s="fur" %}</div></td>
<td><div class="cell">{% include list.html s="beauty" %}</div></td>
<td><div class="cell">{% include list.html s="zoo" %}</div></td>
</tr>

<tr>
<td>{% include section.html s="cow" %}</td>
<td>{% include section.html s="pig" %}</td>
<td>{% include section.html s="sheep" %}</td>
</tr>

<tr>
<td><div class="cell">{% include list.html s="cow" %}</div></td>
<td><div class="cell">{% include list.html s="pig" %}</div></td>
<td><div class="cell">{% include list.html s="sheep" %}</div></td>
</tr>

<tr>
<td>{% include section.html s="bird" %}</td>
<td>{% include section.html s="fish" %}</td>
<td>{% include section.html s="inv" %}</td>
</tr>

<tr>
<td><div class="cell">{% include list.html s="bird" %}</div></td>
<td><div class="cell">{% include list.html s="fish" %}</div></td>
<td><div class="cell">{% include list.html s="inv" %}</div></td>
</tr>

<tr>
<td>{% include section.html s="farm" %}</td>
<td>{% include section.html s="veg" %}</td>
<td>{% include section.html s="tech" %}</td>
</tr>

<tr>
<td><div class="cell">{% include list.html s="farm" %}</div></td>
<td><div class="cell">{% include list.html s="veg" %}</div></td>
<td><div class="cell">{% include list.html s="tech" %}</div></td>
</tr>

<tr>
<td style="width: 30%">{% include section.html s="other" %}</td>
</tr>

<tr>
<td><div class="cell">{% include list.html s="other" %}</div></td>
</tr>

</table>

<div class="mobile">

<div class="start">начните здесь</div>
{% include list.html s="red" %}
<br>

{% include section.html s="basic" %}
{% include list.html s="basic" %}
<br>

{% include section.html s="comm" %}
{% include list.html s="comm" %}
<br>

{% include section.html s="fur" %}
{% include list.html s="fur" %}
<br>

{% include section.html s="beauty" %}
{% include list.html s="beauty" %}
<br>

{% include section.html s="zoo" %}
{% include list.html s="zoo" %}
<br>

{% include section.html s="cow" %}
{% include list.html s="cow" %}
<br>

{% include section.html s="pig" %}
{% include list.html s="pig" %}
<br>

{% include section.html s="sheep" %}
{% include list.html s="sheep" %}
<br>

{% include section.html s="bird" %}
{% include list.html s="bird" %}
<br>

{% include section.html s="fish" %}
{% include list.html s="fish" %}
<br>

{% include section.html s="inv" %}
{% include list.html s="inv" %}
<br>

{% include section.html s="farm" %}
{% include list.html s="farm" %}
<br>

{% include section.html s="veg" %}
{% include list.html s="veg" %}
<br>

{% include section.html s="tech" %}
{% include list.html s="tech" %}
<br>

{% include section.html s="other" %}
{% include list.html s="other" %}

</div>

---

Подписаться: <a href="{{ site.vk }}">ВКонтакте</a>, <a href="{{ site.telegram }}">Telegram</a>

---

### Рекомендуемые ресурсы

- [Голоса за животных](http://voicesforanimals.ru/) ([ВКонтакте](https://vk.com/voicesforanimals), [Telegram](https://t.me/voicesforanimals))
- Вегетарианцы и веганы ([ВКонтакте](https://vk.com/vegetarians), [Telegram](https://t.me/russian_vegans))
- [Едим лучше](https://vk.com/eatingbetter)
- [WhyAnimals](https://whyanimals.ru/)
- [Центр защиты прав животных "ВИТА"](http://www.vita.org.ru/) ([ВКонтакте](https://vk.com/club3349701), [Telegram](https://t.me/vita_russia))
- [Уменьшение страданий](https://reducingsuffering.github.io/) ([ВКонтакте](https://vk.com/reducing_suffering), [Telegram](https://t.me/reducing_suffering))
- [80000 часов. Как построить успешную карьеру и принести пользу миру](https://80000hours.ru/)
- [Animal Charity Evaluators](https://animalcharityevaluators.org/)
- [Anima International](https://animainternational.org/)
- Our World in Data: [Animal Welfare](https://ourworldindata.org/animal-welfare)
- [Reducetarian Foundation](https://www.reducetarian.org/)
- [One Step for Animals](https://www.onestepforanimals.org/)
