---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is **Zhang Junyan (张骏琰)**. I am currently a Master’s student at the **National University of Singapore**.  
Previously, I worked as a **Research Assistant** at the **Hong Kong University of Science and Technology (Guangzhou)**. Before that, I received my **B.Eng. degree in Mechatronic Engineering** from **Tongji University**.

I will join **HKUST (Guangzhou)** as a **PhD student in Artificial Intelligence** in **Fall 2026**. My research interests include **Natural Language Processing** and **Trustworthy AI**.

## Publications

*(In chronological order; my newest publications are also updated on my [Google Scholar](https://scholar.google.com/citations?user=zZNvwjgAAAAJ&hl=en).)*

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% for p in pubs limit: 5 %}
{% include archive-single.html type="list" %}
{% endfor %}
