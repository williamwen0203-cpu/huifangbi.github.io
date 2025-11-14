---
layout: publications
title: Publications
permalink: /publications/
---

This page lists my peer-reviewed journal articles, reviews, and conference contributions.
The entries are generated automatically from the BibTeX file in `_bibliography/papers.bib`.

To highlight selected works or specific categories, you can use the `keywords` field in each
BibTeX entry (e.g., `keywords = {first-author, review, coating}`) and filter them below.

---

## Selected Publications

<!--
  This section shows a subset of papers, for example your first-author or most important works.
  Make sure your BibTeX entries for these papers contain something like:
  keywords = {first-author}
-->
{% bibliography --query @*[keywords~=first-author] --max 10 %}

---

## Journal Articles

<!--
  If you use `keywords = {journal}` for journal papers, you can filter them here.
  If not, this section will simply show all entries of type "article".
-->

{% bibliography --query @article %}

---

## Review Articles

<!--
  If you tag your review papers with `keywords = {review}`, they will show up here.
  Otherwise, you can comment out this block or leave it as is.
-->

{% bibliography --query @*[keywords~=review] %}

---

## Conference Papers and Presentations

<!--
  Tag conference items with e.g. `keywords = {conference}` or make them type @inproceedings.
-->

{% bibliography --query @*[keywords~=conference] %}

---

## All Publications

<!--
  Full list of all BibTeX entries in `_bibliography/papers.bib`.
  This is useful as a complete reference list.
-->

{% bibliography %}

