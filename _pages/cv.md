---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Curriculum Vitae

## Professional Leadership & Honors
* Technical Committee on Machine Learning, Chinese Association for Artificial Intelligence (CAAI)
  * Appointed member of invitation-only selective technical committee.
  * Contributing to global machine learning standards and recommendations.

## Open-Source Leadership & Technological Impact
* Omni One: High-Performance Data Synthesis Framework
  * GitHub: https://github.com/garyguo123456789/omni-one 
  * Pioneered novel data synthesis algorithms enabling real-time generation of queryable datasets from unstructured sources for AI model training, achieving 10x performance improvement over traditional ETL pipelines through optimized parallel processing and intelligent caching mechanisms.
  * Adopted across Finance, Real Estate, and Manufacturing sectors for intelligent data processing; validated by active community contributions and industrial deployments as foundational infrastructure for secondary software systems.

## Education
* Columbia University — New York, NY
  * B.A. in Computer Science, Dec. 2025
  * GPA: 3.8 / 4.0
  * Core focus: Applied Machine Learning, Distributed Systems, Operations Research.

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

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
