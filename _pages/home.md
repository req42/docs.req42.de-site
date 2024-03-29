---
title: "arc42 Documentation"
layout: single
classes: wide
header:
  overlay_color: "#004F94"
  caption: "Need [**support**](https://arc42.de)?"
permalink: /
excerpt: "The info you need. Your questions answered."

sidebar:
  nav: "template-nav"
---


{% assign nr_sec01_tips = site.tips | where: "category", "requirements" | size %}
{% assign nr_sec02_tips = site.tips | where: "category", "constraints" | size %}
{% assign nr_sec03_tips = site.tips | where: "category", "context" | size %}
{% assign nr_sec04_tips = site.tips | where: "category", "solution-strategy" | size  %}
{% assign nr_sec05_tips = site.tips | where: "category", "building-block" | size %}
{% assign nr_sec06_tips = site.tips | where: "category", "runtime" | size %}
{% assign nr_sec07_tips = site.tips | where: "category", "deployment" | size %}
{% assign nr_sec08_tips = site.tips | where: "category", "concepts"  | size %}
{% assign nr_sec09_tips = site.tips | where: "category", "decisions" | size %}
{% assign nr_sec10_tips = site.tips | where: "category", "quality" | size %}
{% assign nr_sec11_tips = site.tips | where: "category", "risks" | size %}
{% assign nr_sec12_tips = site.tips | where: "category", "glossary" | size %}



Check out  **[ practical tips](/keywords)** for using arc42, organized by template sections:

1. [**Introduction and goals**](/section-1/): Requirements, stakeholder, (top) quality goals ({{ nr_sec01_tips }} tips)
2. [**Constraints**](/section-2/): Technical and organizational constraints, conventions ({{ nr_sec02_tips }} tips)
3. [**Context and scope**](/section-3/): Business and technical context, external interfaces ({{ nr_sec03_tips }} tips)
4. [**Solution strategy**](/section-4/): Fundamental solution decisions and ideas ({{ nr_sec04_tips }} tips)
5. [**Building block view**](/section-5/): Abstractions of source code, black-/whiteboxes ({{ nr_sec05_tips }} tips)
6. [**Runtime view**](/section-6/): Runtime scenarios: How do building blocks interact ({{ nr_sec06_tips }} tips)
7. [**Deployment view**](/section-7/): Hardware and technical infrastructure, deployment ({{ nr_sec07_tips }} tips)
8. [**Crosscutting concepts**](/section-8/): Recurring solution approaches and patterns ({{ nr_sec08_tips }} tips)
9. [**Architecture decisions**](/section-9/): Important decisions ({{ nr_sec09_tips }} tips)
10. [**Quality**](/section-10/): Quality tree and quality scenarios ({{ nr_sec10_tips }} tips)
11. [**Risks and technical debt**](/section-11/): Known problems, risks and technical debt ({{ nr_sec11_tips }} tips)
12. [**Glossary**](/section-12/): Definitions of important business and technical terms ({{ nr_sec12_tips }} tips)


>Our tips are tagged by [**{{ site.tags.size }} keywords**](/keywords) that will help you navigate. Three of these stand out:
>
>* **[<font color="#dd354b">lean</font>](/keywords/#lean)**: You are looking for opportunities to shorten or  streamline you documentation pragmatically. You want to reduce efforts without loosing content or value. You are working in an agile environment and want to have lightweight documentation – based on the motto: _travel light_.
>* **[<font color="#dd354b">thorough</font>](/keywords/#thorough)**: You are working in a more formal environment, e.g. developing very large or critical systems with hard quality requirements. Your stakeholders require thoroughness, accuracy and attention to detail. Maybe your systems and their documentation have to be audited.
>* **[<font color="#dd354b">essential</font>](/keywords/#essential)**: Despite lean and agile, there are some informations about your system that you should always document; i.e. quality goals of your architecture.




# Learn more!

{% include subtle-ads/subtle-ads.html %}
