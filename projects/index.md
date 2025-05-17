---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Explore my innovative cybersecurity research projects focusing on advanced neural networks, explainability, and cutting-edge threat detection. My work bridges the gap between machine learning and network security to address emerging challenges in the digital landscape.

{% include tags.html tags="cybersecurity, research, software, ml" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}