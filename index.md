---
layout: page
title: "Уменьшаем"
excerpt: "От чего страдают животные и как можно им помочь. Редуктарианство, флекситарианство и веганство. Уменьшение потребления продуктов животного происхождения, таких как мясо, яйца, мех и молочные продукты. Эффективный активизм."
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
  .border {
    border: 2px solid;
  }
  .box, .card {
    padding: 10px;
    border-radius: 15px;
    background: #fafafa;
  }  
  .cards {
    display: flex;
    gap: 10px;
  }
  .subtitle {
    font-family: Angeme;
    font-size: 2em;
    color: black;
    padding-top: 10px;
  }
</style>

<div class="desktop">

<div class="cards box" style="background-color: white">
<table style="width: 33%"><tr style="padding: 0; margin: 0;"><td style="width: 50%; padding: 0; margin: 0"><div style="position: relative"><img src="assets/images/start.jpg"/></div></td><td style="width: 50%; padding: 0; margin: 0; vertical-align: bottom"><div class="over-r">начните<br>здесь</div></td></tr>
<tr><td colspan="2"><div class="cell">{% include list.html s="red" %}</div></td></tr></table>
{% include card.html s="basic" c1="grey" c2="white" %}
{% include card.html s="comm" c1="#82B4FF" c2="#EBF3FF" %}
</div>

<center class="subtitle">разве эти вещи того стоят?</center>

<div class="cards box" style="background-color: #FFDD82">
{% include card.html s="fur" c1="#FFDD82" c2="#FFF8E5" %}
{% include card.html s="beauty" c1="#FFDD82" c2="#FFF8E5" %}
{% include card.html s="zoo" c1="#FFDD82" c2="#FFF8E5" %}
</div>

<center class="subtitle">не всё так просто с мясом, молоком и кожей</center>

<div class="cards box" style="background-color: #664F4A">
{% include card.html s="cow" c1="#664F4A" c2="#FFE4E0" %}
{% include card.html s="pig" c1="#664F4A" c2="#FFE4E0" %}
{% include card.html s="sheep" c1="#664F4A" c2="#FFE4E0" %}
</div>

<center class="subtitle">а что у животных поменьше?</center>

<div class="cards box" style="background-color: white">
{% include card.html s="bird" c1="#FFB440" c2="#FFF8E5" %}
{% include card.html s="fish" c1="#222473" c2="#D4D5FF" %}
{% include card.html s="inv" c1="#236E25" c2="#C7FFC8" %}
</div>

<center class="subtitle">проблемы и решения</center>

<div class="cards box" style="background-color: white">
{% include card.html s="farm" c1="#C46400" c2="#FFE0D6" %}
{% include card.html s="veg" c1="#78FF84" c2="#DEFFE1" %}
{% include card.html s="tech" c1="#B73DFF" c2="#EFD4FF" %}
</div>

<center class="subtitle">что ещё?</center>

<div class="cards">
{% include card.html s="other" c1="grey" c2="white" %}
{% include card.html s="res" c1="grey" c2="white" %}
</div>

</div>

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
<br>

{% include section.html s="res" %}
{% include list.html s="res" %}

</div>

---

Подписаться: <a href="{{ site.vk }}">ВКонтакте</a>, <a href="{{ site.telegram }}">Telegram</a>
