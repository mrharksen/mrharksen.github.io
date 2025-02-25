---
layout: post
title: "Lokakeppnir"
date: 2025-02-24
categories: jekyll update
---

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

  {% assign years = (3..24) | reverse %}

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
