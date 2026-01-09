---
layout: page
title: StrOntEx
description: Algorithms for ontology extension and ontology-based knowledge injection for small molecule metabolites
img: assets/img/StrOntEx.png
importance: 1
category: biomolecules
related_publications: false
---

This DFG- and SNF-funded project is a collaboration with the group of Prof. Dr. Till Mossakowski at the University of Osnabrück in Germany, and Dr. Fabian Neuhaus at the Otto-von-Güricke University in Magdeburg, Germany. The overall ambition of the project is to develop and enhance predictive models for structural and functional classification of chemicals for large-scale data-driven biomolecular discovery. The project has three interrelated components: methods for _chemical classification_ and _ontology extension_, methods for enhancing _interpretability_, and methods for _knowledge injection_ into predictive models through ontology pre-training.

*** Ontology extension ***: Reference ontologies in the biomedical domain are manually maintained by teams of expert curators. However, manual maintenance is slow and creates
a bottleneck, which means that their size and scope falls short of all entities in the full domain, limiting their utility. For example, the <a href="https://www.ebi.ac.uk/chebi/">ChEBI</a> (Chemical Entities of Biological Interest) ontology, despite being the largest and most widely used ontology for the domain of biologically relevant chemistry in the public domain, is dwarfed in size by the hundred million chemicals in PubChem, a database (not an ontology), which is itself not comprehensive. The manually curated portion of ChEBI only grows at a rate of around 100 entries per month, thus will only ever be able to cover a small fraction of the chemicals that are in its domain. There is therefore a huge need for automation of chemical classification into the ontology, and automation of ontology extension with additional classes, in order for the ontology to be useful without the delays of manual curation.

However, classification of hundreds of thousands of chemical entities into an ontology containing thousands of overlapping classes is a very challenging task even for state-of-the-art modern machine learning algorithms. We develop and evaluate a range of different approaches to address this challenge including approaches based on logical rules and those based on deep learning with different architectures including transformers and graphs. This work has given rise to the <a href="https://chebifier.hastingslab.org">Chebifier</a> tool in which we showcase the latest algorithmic approaches in a user-friendly interface backed up by an ensemble of different approaches. The tool is also available as a Python library.

*** Interpretability ***:

For automated systems to be adopted by human experts, it is essential that the reasons for automated outputs can be inspected. For deep learning-based algorithms this is a well-known challenge, as such systems contain a huge number of parameters without direct connection to meaningful semantics. Our project aims to advance the state of the art in interpretability methods by extracting meaningful patterns of attention and activation that can be mapped to semantically meaningful sub-structures within input molecules and target classes.  

*** Ontology pre-training ***:

During our efforts training predictive models to predict complex sets of chemical classes, we noticed that the trained models could be repurposed for downstream tasks (transfer learning) with an added advantage from having learned how to predict chemical classes. This gave rise to the 'ontology pre-training' paradigm of knowledge injection into large-scale molecular models. We first showed that adding an ontology pre-training step to a chemical language model could improve its downstream performance at toxicity prediction. Subsequently, we extended this approach to improve predictive performance of a variety of other chemical properties, including solubility.

## related publications
<div class="publications">
  {% bibliography -f papers -q @*[key=hastings_learning_2021]* %}
  {% bibliography -f papers -q @*[key=glauer_chebifier_2024]* %}
</div>
