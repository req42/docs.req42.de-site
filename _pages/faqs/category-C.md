---
layout: single
title: C - Questions on arc42 sections
permalink: /category_c/

classes: wide
header:
    overlay_color: "#1A7BB7"
    caption: "Need [**support**](https://arc42.de)?"
sidebar:
    nav: "faq-nav"
---

{% comment %}
   The following could most likely be done with Jekyll categories, BUT:
   Header names and category names differ...
{% endcomment %}

{% assign section1_posts = site.posts | where: "category", "section-requirements" | reverse %}
{% assign section2_posts = site.posts | where: "category", "section-constraints" | reverse %}
{% assign section3_posts = site.posts | where: "category", "section-context" | reverse %}
{% assign section4_posts = site.posts | where: "category", "section-solutionstrategy" | reverse %}
{% assign section5_posts = site.posts | where: "category", "section-buildingblock" | reverse %}
{% assign section6_posts = site.posts | where: "category", "section-runtime" | reverse %}
{% assign section7_posts = site.posts | where: "category", "section-deployment" | reverse %}
{% assign section8_posts = site.posts | where: "category", "section-concepts" | reverse %}
{% assign section9_posts = site.posts | where: "category", "section-decisions" | reverse %}
{% assign section10_posts = site.posts | where: "category", "section-quality" | reverse %}
{% assign section11_posts = site.posts | where: "category", "section-risks" | reverse %}
{% assign section12_posts = site.posts | where: "category", "section-glossary" | reverse %}

<ol>
  <li><a href="#c-sec-1">Requirements and Stakeholder ({{ section1_posts | size }})</a></li>
  <li><a href="#c-sec-2">Constraints ({{ section2_posts | size }})</a></li>
  <li><a href="#c-sec-3">Context ({{ section3_posts | size }})</a></li>
  <li><a href="#c-sec-4">Solution strategy ({{ section4_posts | size }})</a></li>
  <li><a href="#c-sec-5">Building block view ({{ section5_posts | size }})</a></li>
  <li><a href="#c-sec-6">Runtime view ({{ section6_posts | size }})</a></li>
  <li><a href="#c-sec-7">Deployment view ({{ section7_posts | size }})</a></li>
  <li><a href="#c-sec-8">Crosscutting concepts ({{ section8_posts | size }})</a></li>
  <li><a href="#c-sec-9">Architectural decisions ({{ section9_posts | size }})</a></li>
  <li><a href="#c-sec-10">Quality tree and -scenarios ({{ section10_posts | size }})</a></li>
  <li><a href="#c-sec-11">Risks and technical debt ({{ section11_posts | size }})</a></li>
  <li><a href="#c-sec-12">Glossary ({{ section12_posts | size }})</a></li>
</ol>

<hr class="with-no-margin"/>

<div id="search-results">


    <h2 id="c-sec-1">arc42 Section 1: Requirements and Stakeholder </h2>
    {% for post in section1_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-2">arc42 Section 2: Constraints</h2>
    {% for post in section2_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-3">arc42 Section 3: Context</h2>
    {% for post in section3_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-4">arc42 Section 4: Solution Strategy</h2>
    {% for post in section4_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-5">arc42 Section 5: Building Block View</h2>
    {% for post in section5_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-6">arc42 Section 6: Runtime View</h2>
    {% for post in section6_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-7">arc42 Section 7: Deployment View</h2>
    {% for post in section7_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-8">arc42 Section 8: Crosscutting Concepts</h2>
    {% for post in section8_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-9">arc42 Section 9: Architectural Decisions</h2>

In software engineering literature you find both
**architecture decision** and **architectural decision**.

Both mean the same thing...

    {% for post in section9_posts  %}

    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-10">arc42 Section 10: Quality Tree and Scenarios</h2>
    {% for post in section10_posts  %}
    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-11">arc42 Section 11: Risks and Technical Debt</h2>
    {% for post in section11_posts  %}
    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}

    <hr class="with-no-margin"/>
    <h2 id="c-sec-12">arc42 Section 12: Glossary</h2>
    {% for post in section12_posts  %}
    <div class="article-wrapper">
        <article>
            {% include article-header.html page=post link=true share=false  %}
        </article>
    </div>
    {% endfor %}
</div>
