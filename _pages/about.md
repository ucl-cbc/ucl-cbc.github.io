---
layout: about
title: Home
permalink: /

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: false # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Based at UCL's [Great Ormond Street Institute of Child Health](https://www.ucl.ac.uk/child-health/great-ormond-street-institute-child-health),
the ICH Computational Biology Club meets once a month to discuss recent
computational topics and papers, often presented by their authors.

It is co-organised by [Yara Sanchez Corrales](https://profiles.ucl.ac.uk/77936-yara-elena-sanchez-corrales) and [George Hall](https://ghall.co.uk), two postdoctoral research fellows in the lab of [Prof Sergi Castellano](https://www.castellanolab.net/). If you are interested in speaking, please [get in touch](mailto:y.sanchez-corrales@ucl.ac.uk;george.hall@ucl.ac.uk)! Our club hosts both internal and external speakers.

A list of our previous and upcoming sessions can be found [here](./talks).

<br>

<center><h4><u>Next session</u></h4></center>

**Speaker:** Elisabetta Sciacca (Queen Mary University of London)

**Title:** What If Molecular Relationships Matter More Than Individual Genes?

**Abstract:** Traditional Differential Gene Expression analysis (DGE) leaves researchers with hundreds of 'significant' genes but no clear biological story. We developed multiDEGGs, a CRAN package for differential network analysis which enables interactive exploration of differential interactions (with statistical significance) from single or multi-omics datasets.
<br>
Beyond biomarker discovery, the differential interactions can be used for prediction purposes.
<br>
The package facilitates seamless integration into cross-validation machine learning pipelines, serving as feature selection and augmentation tool.
<br>
We systematically compared multiDEGGs against five traditional feature selection methods. On average, AUC values obtained with multiDEGGs showed an improvement of 0.10 compared to conventional filters.

**Where:** In-person at the Zayed Centre for Research and online via Zoom

**When:** Thursday 20 November at 2pm

<br><br>

<center>
<script>(function() { function load() { window.addEventListener('message', (event) => { if (event.data.type === 'beehiiv:styles') { const height = event.data.payload.height; const width = event.data.payload.width; const src = event.data.payload.src; const borderRadius = event.data.payload.borderRadius || '0px'; const boxShadow = event.data.payload.boxShadow || 'none'; const iframe = document.querySelector(`iframe.beehiiv-embed[src="${src}"]`); iframe.style.width = width; iframe.style.height = height; iframe.style.borderRadius = borderRadius; iframe.style.boxShadow = boxShadow; } else if (event.data.type === 'beehiiv:success-toast') { const template = event.data.payload.templateString; const doc = (new DOMParser()).parseFromString(template, "text/html"); const fragment = document.createDocumentFragment(); [...doc.body.childNodes].forEach(node => fragment.appendChild(node)); document.body.appendChild(fragment); setTimeout(() => document.querySelector("#beehiiv-toast").remove(), 5000); } }); document.querySelectorAll('iframe.beehiiv-embed').forEach((iframe) => { iframe.contentWindow.postMessage({ type: 'beehiiv:loaded' }, '*'); }); } if (window.document.readyState === 'complete') { load(); } else { window.addEventListener('load', load); } })();</script><iframe src="https://subscribe-forms.beehiiv.com/0e5da7cc-2116-495f-bea9-e9fcfb1048fd" class="beehiiv-embed" data-test-id="beehiiv-embed" frameborder="0" scrolling="no" style="width: 561px; height: 208px; margin: 0; border-radius: 0px 0px 0px 0px !important; background-color: transparent; box-shadow: 0 0 #0000; max-width: 100%;"></iframe>
</center>
