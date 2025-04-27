---
layout: post
title: "Eðlisfræðikeppnir"
date: 2025-02-24
categories: jekyll update
---

## Forkeppnin

Á hverju ári er haldin forkeppni til að skera úr um hverjum eigi að bjóða í úrslitakeppnina.

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: center;
  }
  th {
    background-color: #f4f4f4;
  }
  @media screen and (max-width: 600px) {
    table {
      display: block;
      overflow-x: auto;
      white-space: nowrap;
    }
  }
</style>

<table>
  <tr>
    <th>Keppni</th>
    <th>Lausnir</th>
  </tr>

  {% assign years = (3..25) | reverse %}

  {% for i in years %}
    {% assign year = i | plus: 2000 %}
    {% assign file_number = i %}
    {% if i < 10 %}
      {% assign file_number = "0" | append: i %}
    {% endif %}
    {% assign file = "/assets/pdfs/forkeppnir/undankeppni" | append: file_number | append: ".pdf" %}
    {% assign solution_file = "/assets/pdfs/forkeppnir/Lausnir/undankeppni" | append: file_number | append: "-lausn.pdf" %}

    <tr>
      <td><a href="{{ file }}" target="_blank">Forkeppni {{ year }}</a></td>
      <td>
        {% if i >= 19 %}
          <a href="{{ solution_file }}" target="_blank">Lausnir</a>
        {% else %}
          -
        {% endif %}
      </td>
    </tr>
  {% endfor %}
</table>

## Lokakeppnin

Efstu 16 keppendum í forkeppninni er boðið í fræðilega og verklega úrslitakeppni. Efstu keppendum verður síðan boðið lið í Ólympíuliði Íslands í eðlisfræði það sumarið.

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: center;
  }
  th {
    background-color: #f4f4f4;
  }
  @media screen and (max-width: 600px) {
    table {
      display: block;
      overflow-x: auto;
      white-space: nowrap;
    }
  }
</style>

<table>
  <tr>
    <th>Keppni</th>
    <th>Lausnir</th>
  </tr>

  {% assign years = (3..25) | reverse %}

  {% for i in years %}
    {% assign year = i | plus: 2000 %}
    {% assign file_number = i %}
    {% if i < 10 %}
      {% assign file_number = "0" | append: i %}
    {% endif %}
    {% assign file = "/assets/pdfs/lokakeppnir/fraedileg" | append: file_number | append: ".pdf" %}
    {% assign solution_file = "/assets/pdfs/lokakeppnir/lausnir/fraedileg" | append: file_number | append: "-lausn.pdf" %}

    <tr>
      <td><a href="{{ file }}" target="_blank">Lokakeppni {{ year }}</a></td>
      <td>
        {% if i >= 16 %}
          <a href="{{ solution_file }}" target="_blank">Lausnir</a>
        {% else %}
          -
        {% endif %}
      </td>
    </tr>
  {% endfor %}
</table>

## IPhO

Næstu alþjóðlegu Ólympíuleikar í eðlisfræði (IPhO) verða í:

- Kólumbíu 2026
- Ungverjalandi 2027
- Suður-Kóreu 2028
- Ekvador 2029

Hér má sjá gamlar keppnir ásamt lausnum:


## EuPhO

Hér má sjá gamlar keppnir ásamt íslenskum þýðingum og lausnum:

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: center;
  }
  th {
    background-color: #f4f4f4;
  }
  @media screen and (max-width: 600px) {
    table {
      display: block;
      overflow-x: auto;
      white-space: nowrap;
    }
  }
</style>

<table>
  <tr>
    <th>Ár</th>
    <th>Fræðilegt</th>
    <th>Verklegt</th>
    <th>Lausnir</th>
  </tr>

  {% assign years = (17..24) | reverse %}
  {% for year in years %}
    {% assign path = "/assets/pdfs/eupho/" %}
    {% assign solution_path = "/assets/pdfs/eupho/lausnir/" %}
    <tr>
      <td>20{{ year }}</td>
      <td>
        <a href="{{ path }}eupho{{ year }}-t-isl.pdf" target="_blank">[IS]</a> /
        <a href="{{ path }}eupho{{ year }}-t-eng.pdf" target="_blank">[EN]</a>
      </td>
      <td>
        <a href="{{ path }}eupho{{ year }}-e-isl.pdf" target="_blank">[IS]</a> /
        <a href="{{ path }}eupho{{ year }}-e-eng.pdf" target="_blank">[EN]</a>
      </td>
      <td>
        <a href="{{ solution_path }}eupho{{ year }}-t-sol.pdf" target="_blank">[Fræðilegt]</a> /
        <a href="{{ solution_path }}eupho{{ year }}-e-sol.pdf" target="_blank">[Verklegt]</a>
      </td>
    </tr>
  {% endfor %}
</table>

Fyrir verklega hlutana frá 2020 og 2021 bendum við á eftirfarandi forrit:

<table>
  <tr>
    <th>Verkefni</th>
    <th>Windows</th>
    <th>MacOS</th>
    <th>Linux</th>
  </tr>

  <tr>
    <td>E1 - Hidden Charge (2020)</td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E1-hidden-charge-WIN.exe" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E1-hidden-charge-OSX" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E1-hidden-charge-Linux" download>Download</a></td>
  </tr>

  <tr>
    <td>E2 - Black Box (2020)</td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E2-black-box-WIN.exe" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E2-black-box-OSX" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2020/E2-black-box-Linux" download>Download</a></td>
  </tr>

  <tr>
    <td>E1 - Hidden Wire (2021)</td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E1_hidden_wire_win.exe" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E1_hidden_wire_osx" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E1_hidden_wire_linux" download>Download</a></td>
  </tr>

  <tr>
    <td>E2 - Hot Cylinder (2021)</td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E2_hot_cylinder_win.exe" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E2_hot_cylinder_osx" download>Download</a></td>
    <td><a href="/assets/pdfs/eupho/exp-eupho2021/E2_hot_cylinder_linux" download>Download</a></td>
  </tr>

</table>

Forritin eru skipanalínuforrit og eru aðgengileg fyrir Linux, MacOS og Windows. Hafið samband við mig ef ykkur tekst ekki að keyra forritin (á Mac og Linux gæti þurft að nota **chmod +x nafn-á-skrá** skipun).


## Aðrar keppnir

Það eru fleiri keppnir sem að fólk getur tekið þátt í og getur verið gagn í að skoða nokkrar af þeim eru (í engri sérstakri röð)

- OPhO 
- APhO
- BCAUPC
- INPhO
- USAPhO





