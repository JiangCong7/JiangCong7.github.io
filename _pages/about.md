---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) an

A data-driven personal website
==============================

Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.


Education
=========

* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
===============

* Spring 2024: Academic Pages Collaborator

  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users
* Fall 2015: Research Assistant

  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
* Summer 2015: Research Assistant

  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Skills
======

* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
=====

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service
=======

* Currently signed in to 43 different slack teams
