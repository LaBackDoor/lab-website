---
title: "AI Threat Hunting Lab: Week 1 Progress - Core Network & Visibility Online"
image: images/ai_sec_lab_week1.png
author: banny orojo
last_modified_at: "2025-10-21"
tags:
  - ai-security
  - threat-hunting
  - homelab
  - devsecops
---

A quick update on the AI Threat Hunting Lab! The core network backbone is now complete, featuring a Kali attacker, an Ubuntu client, pfSense for routing, and Splunk for centralized visibility.
Hello everyone, and welcome back! Following my initial post, I've decided to switch this tracking journey to a **weekly update** to better capture the rapid progress of building out the AI Threat Hunting Lab.

I'm happy to report that the **network backbone** is now fully operational! This initial phase was crucial for establishing the foundational security and visibility layers before we dive into the machine learning components. This is the solid footing we need.

---

## The Core Infrastructure is Online

As you can see in the provided diagram, the environment is now configured, establishing the **Untrusted Network / Internet** and the **Management Network**.

![AI Threat Hunting Lab Diagram: Backbone Network](images/ai_sec_lab_week1.png)

* **pfSense (192.168.1.1):** This acts as our crucial network boundary, firewall, and router, securely connecting the attacker/client zone (10.100.1.1/24) to the management zone (192.168.1.1/24).
* **Attacker/Client Endpoints (Kali & Ubuntu):** We have **Kali Linux** (10.100.1.20) as the dedicated attacker machine and an **Ubuntu Client** (10.100.1.30) to simulate a standard user endpoint—perfect for practicing penetration testing and defense scenarios against our future AI application.
* **Splunk (192.168.1.10):** The centerpiece of our visibility strategy is now online. Splunk is collecting logs from all relevant endpoints, giving us the centralized monitoring needed to analyze and hunt for threats from the attacker environment.

---

## What's Next: The AI Layer

With the traditional security foundation set, the next phase will be the most exciting—integrating the **AI/LLM components**.

The bottom section of the diagram—the **LiteLLM Gateway**, **Local LLM Inference Server**, **MCP**, and **Vector Database**—represents the core architecture for our *target application* we will be securing. The coming weeks will be spent deciding on the specific software/models for these roles and getting them wired into the network.

This was a short but important update. The lab has a heartbeat! Stay tuned for next week as we start configuring the first AI component.
