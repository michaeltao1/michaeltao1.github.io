---
layout: default
title: M&A Weekly
permalink: /ma-weekly/
---

# M&A Weekly

Weekly commentary on mergers and acquisitions across Pharma, Biotech, and Healthcare. Each edition rounds up the biggest transactions of the week, then takes one deal apart in detail: why it happened, what each side gains, and where the synergies actually sit.

June 2026 was an unusually good month to start. Global biopharma M&A had already crossed roughly $130 billion for the first half of the year, comfortably ahead of the same point in 2025, and June alone produced two separate transactions above $10 billion in a single week. The month is a clean case study in the force driving most of this activity: a wave of patent expirations bearing down on Big Pharma, and a scramble to buy the pipeline that replaces it.

## June 2026 at a glance

The full slate of acquisitions covered across the four editions, largest first:

| Date | Acquirer | Target | Value | Area |
|------|----------|--------|-------|------|
| Jun 25 | Merck KGaA | Bio-Techne | ~$11.3B | Life science tools |
| Jun 22 | AbbVie | Apogee Therapeutics | ~$10.9B | Immunology |
| Jun 9 | GSK | Nuvalent | ~$10.6B | Oncology (lung) |
| Jun 1 | Servier | Edgewise (muscular dystrophy unit) | up to $2.65B | Rare disease |
| Jun 8 | Incyte | Vega Therapeutics | up to $2.0B | Hematology |
| Jun 29 | Ipsen | Kartos Therapeutics | up to $1.75B | Hemato-oncology |
| Jun 17 | Biogen | RayThera | up to $1.0B | Immunology |
| Jun 8 | Johnson & Johnson | Firefly Bio | ~$1.0B | Oncology |
| Jun 29 | Zymeworks | Theravance Biopharma | ~$929M | Respiratory (COPD) |
| Jun 12 | Medtronic | Scientia Vascular | ~$550M | Medtech (neurovascular) |
| Jun 1 | ResMed | Noctrix Health | ~$340M | Medtech (sleep) |

*Values are total potential consideration, including milestones where disclosed. Figures are sourced from company press releases and sector reporting, cited inside each edition.*

## Editions

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%d %B %Y" }}

{{ post.excerpt }}
{% endfor %}
