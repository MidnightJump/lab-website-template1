---
title: 项目
nav:
  order: 2
  tooltip: 软件、数据集等
---

# {% include icon.html icon="fa-solid fa-wrench" %}项目

我们开发各种创新项目，包括开源软件、数据集、工具和应用程序。这些项目体现了我们在技术研究和实际应用方面的能力。

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## 重点项目

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## 更多项目

{% include list.html component="card" data="projects" filter="!group" style="small" %}
