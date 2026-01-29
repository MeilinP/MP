---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

## Algo-Trading

Systematic trading strategies with live execution capabilities.

{% for post in site.portfolio %}
  {% if post.category == "algo-trading" %}
  <div style="margin-bottom: 1.5em;">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}

---

## Signal Extraction

Research-focused work on extracting predictive signals from market data.

{% for post in site.portfolio %}
  {% if post.category == "signal-extraction" %}
  <div style="margin-bottom: 1.5em;">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}

---

## Sentiment Analysis

NLP applications for financial markets.

{% for post in site.portfolio %}
  {% if post.category == "sentiment-analysis" %}
  <div style="margin-bottom: 1.5em;">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}

---

## Volatility

Options pricing and volatility modeling.

{% for post in site.portfolio %}
  {% if post.category == "volatility" %}
  <div style="margin-bottom: 1.5em;">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}

---

## For Fun

Creative and experimental projects.

{% for post in site.portfolio %}
  {% if post.category == "for-fun" %}
  <div style="margin-bottom: 1.5em;">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}
