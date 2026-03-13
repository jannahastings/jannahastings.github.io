---
layout: page
title: AI4CLINICS
description: Advancing LLMs to support evidence management and decision-making in clinics
img: assets/img/variantscape.png
importance: 3
category: evidence
related_publications: false
---

The Human-Centered Health AI group evaluates, develops and implements large language and multi-modal models for clinical applications. We currently have collaborations in the area of precision oncology, stroke, and vaccination.

*** ONCO-TP: EvidenceDB and Variantscape ***:

The extent to which a specific molecular alteration (broadly defined, including genomic variants, fusion gene or RNA products and copy number variations), or set of alterations, is therapeutically relevant ('targetable' or 'actionable'), is specified in international guidelines based on different degrees of evidence, known as 'evidence tiers'. These recommendations are based on biological rationale (e.g. if the treatment targets the pathway affected by the alteration) as well as preclinical and, preferably, clinical data. However, the majority of variations lack high-quality evidence, leaving clinicians uncertain about how to interpret an observed alteration in a given patient. Consequently, they must perform comprehensive research across diverse available evidence sources to inform treatment decisions, including the interpretation of the extent to which certain molecular variants are pathogenic or 'druggable' in the respective context. For maximally effective MTB decision-making, it is essential that each participant is able to access comprehensive and reliable information.

In collaboration with clinical researchers at the HOCH-Health Ostschweiz Kantonsspital St. Gallen and the Luzerner Kantonspital, we have developed a method to mine the published literature for variant-disease-treatment associations and provide those in a searchable database. Check our database online at [EvidenceDB](https://evidencedb.hastingslab.org/).

*** Implementation and Human Factors ***:

Our group is interested in the human experience of clinicians when interacting with AI and other digital tools, and use qualitative methods to surface hidden frustrations and gaps which help explain adoption patterns, shadow tool usage behaviours, and successful clinical implementation. Our research emphasises that to be maximally effective for the benefit of both patients and clinicians themselves, clinical AI should be optimised to support clinicians as humans.


## related publications
<div class="publications">
  {% bibliography -f papers -q @*[key=hastings_preventing_2024]* %}
  {% bibliography -f papers -q @*[key=dennstadt_implementing_2025]* %}
  {% bibliography -f papers -q @*[key=wosny_paradoxes_2024]* %}
</div>
