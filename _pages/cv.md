---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Curriculum Vitae (NIW-focused)

## Professional Leadership & Honors
* Technical Committee on Machine Learning, Chinese Association for Artificial Intelligence (CAAI)
  * Appointed member of invitation-only selective technical committee.
  * Contributing to global machine learning standards and recommendations.

## Open-Source Leadership & Technological Impact
* Omni One: High-Performance Data Synthesis Framework
  * GitHub: impact 50+ stars, 30+ forks
  * Cross-industry adoption in Finance, Real Estate, and Manufacturing for queryable intelligence from raw data.
  * Community contribution validated by 30 forks; foundational infrastructure for industrial secondary software.

## Education
* Columbia University — New York, NY
  * B.A. in Computer Science, Dec. 2025
  * GPA: 3.8 / 4.0
  * Core focus: Applied Machine Learning, Distributed Systems, Operations Research.

## Peer-Reviewed Research
* Yang, Y., ..., Guo, H., et al. (2022). "Semantic segmentation supervised deep-learning algorithm for welding-defect detection." Neural Computing and Applications. [Cited by 21]
* Yuan, L., Guo, H., et al. (2024). "Machine-Learning-Assisted Material Discovery of Pyridine-Based Polymers." Environmental Science & Technology. [Cited by 20]

## Professional Experience
* Meta Platforms, Inc. — Menlo Park, CA
  * Software Engineer (Applied AI & CRM Systems), Feb. 2026 – Present
    * Architecting Generative AI features in global CRM to enhance digital economic vitality across millions of enterprises.
    * Engineering distributed backend services in C++ and GraphQL for high-concurrency AI inference.

* Meta Platforms, Inc. — Menlo Park, CA
  * Software Engineer Intern (Enterprise Infrastructure), May 2025 – Aug. 2025
    * Built lead-engagement infrastructure for Meta Business Suite; enabled real-time commerce for global SMBs.
    * Optimized analytics with Apache Hive for enterprise-scale mobile systems.

* Meta Platforms, Inc. — Menlo Park, CA
  * Software Engineer Intern (AI Systems), May 2024 – Aug. 2024
    * Integrated Llama 3 into Messenger at 100k+ user scale for US-led AI deployment.
    * Designed storage schemas with SQLite and used LangChain for model integration/tuning.

## Technical Expertise
* Applied AI: Generative AI, LLM fine-tuning (Llama 3), Semantic Segmentation, Material Informatics.
* Systems/Full-stack: C++, Python, Go, Java, Swift, Kotlin, PHP, SQL, GraphQL, React, Node.js, LangChain.
* Infrastructure: Docker, Kubernetes, AWS, Apache Hive, gRPC, Distributed Systems, RPC.

## Additional Publications, Talks, Teaching
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
