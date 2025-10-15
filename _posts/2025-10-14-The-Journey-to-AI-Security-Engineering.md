---
title: Starting the Journey to AI Security Engineering
image: images/security-data-model.jpg
author: Banny Orojo
tags:
  - ai-security
  - devsecops
  - llm-security
  - mlops
---

As a PhD student with a deep background in both AI and traditional security, I'm pivoting my focus to the practical, industry-driven field of **AI Security Engineering**. This post marks the beginning of my tracking journey, outlining the core distinction of this new discipline and my immediate plan.
This blog will serve as a bi-weekly tracker for my learning and practical application in the emerging domain of **AI Security Engineering**. Given my foundational expertise in both AI and traditional Security, my focus here is on understanding where the practical industry implementation and threat modeling are heading.

---

## AI Security Engineer vs. Traditional Security Engineer

The role of a **Traditional Security Engineer** is fundamentally about securing the environment around the application: the network, the operating system, the data layer, and the established code base (e.g., against OWASP Top 10). The threat landscape, while evolving, is relatively well-defined.

The **AI Security Engineer** takes a distinct step forward, focusing on securing the **Machine Learning (ML) lifecycle itself**—the data, the model, and the deployment pipeline (MLOps). While traditional security protects the infrastructure *hosting* the model, AI Security protects the model’s **integrity, confidentiality, and availability** from *model-specific attacks*.

| Focus Area | Traditional Security Engineering | AI Security Engineering |
| :--- | :--- | :--- |
| **Primary Target** | Networks, Endpoints, Applications, Databases | Training Data, ML Model Artifacts, MLOps Pipelines |
| **Core Threat Model** | Exploits, Vulnerabilities, Misconfigurations | **Adversarial Attacks** (Evasion, Poisoning), **Privacy Attacks** (Model Inversion, Membership Inference), **Prompt Injection** (for LLMs) |
| **Goal** | CIA Triad of Infrastructure/Data | Robustness and Trustworthiness of the ML System |

The discipline requires layering new ML-centric defenses over a robust foundation of cloud and application security.

---

## Resource Plan & Progress Tracker

My goal is to dedicate a focused effort to bridge the theoretical knowledge gap with industry practices, especially since most deployments will be cloud-native.

### 📚 Core Reading

I will be extracting practical insights from the following texts:

* The Developer's Playbook for Large Language Model Security
* Adversarial AI Attacks, Mitigations, and Defense Strategies
* Practicing Trustworthy Machine Learning

### 🎓 Courses & Certifications

I plan to examine the curriculum and key takeaways from these industry-recognized programs:

* Certified AI Security Professional - AI Security Certification - Practical DevSecOps
* AI security fundamentals - Training | Microsoft Learn

### 🎥 Daily Focus: The MLOps Foundation

To ensure I understand the operational context of AI deployment, I am dedicating **2 hours a day** to mastering the production lifecycle. My starting point is a deep dive into AWS deployment:

* **Resource:** **AWS Cloud Complete Bootcamp Course** by Jeff Hale
* **Link:** [https://www.youtube.com/watch?v=zA8guDqfv40](https://www.youtube.com/watch?v=zA8guDqfv40)

---

Looking forward to posting my first progress update / or lab deployment in two weeks!
