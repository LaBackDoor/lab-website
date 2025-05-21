---
---

# LaBackDoor's Website

LaBackDoor is a cybersecurity research lab focused on developing innovative machine learning solutions for network security challenges. We bridge the gap between advanced AI techniques and practical cybersecurity applications to defend against emerging threats in our increasingly connected world.

{% include section.html %}

## Highlights

{% capture text %}

Our research combines cutting-edge machine learning with cybersecurity to create novel approaches for threat detection and system resilience. We focus on adaptive neural network architectures, explainable AI, and secure data collection methodologies for challenging environments.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/byteflow.svg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our flagship projects include NetSpeech, which translates network traffic into natural language for better security analysis, and VulnScout, which uses Multi-Recurrent Neural Networks for software vulnerability forecasting. We're also developing TempoExplain to make temporal neural networks more transparent and MalwareRadar for advanced behavior-based malware detection.
{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/malreader.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our team brings together expertise in machine learning, network security, and cyber-physical systems. We collaborate with academic and industry partners to develop practical security solutions that address real-world challenges in our digital infrastructure.
{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}
