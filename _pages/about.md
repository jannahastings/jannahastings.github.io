---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computer scientist interested in developing intelligent computational systems to advance research across the biological and social sciences and the digital humanities. I am particularly interested in the interface between data science, i.e. algorithms for deriving inferences and predictions based on structured and unstructured data, and _knowledge_ science, i.e. research that amasses, integrates and harnesses what we already know and channels that back towards efforts to make novel discoveries, towards a genuinely cumulative discovery frontier.  

To this end I have actively contributed both to research in computational knowledge representation and reasoning, community-wide knowledge integration across a variety of specific fields via building standards and databases, and primary research using computational (mathematical and statistical) approaches. I have applied these interests across a range of domains including bioinformatics, cheminformatics, psychology and the social and behavioural sciences, and digital humanities. Some of the projects that I am involved in are described further below. 


Projects
======


### Ontologies

Ontologies are structured logic-based representations of domain knowledge that drive intelligent applications. They serve to structure, standardise and exchange domain knowledge, as a foundation for flexible, semantic and intelligent databases (e.g. knowledge graphs), and as inputs to data science algorithms that combine knowledge with data to derive inferences (e.g. semantic similarity, category overrepresentation analysis). 

I am involved in ontology development projects for research in the social and behavioural sciences, including for human [behaviour change](https://www.humanbehaviourchange.org/) and [addiction](https://github.com/jannahastings/addiction-ontology). The main purpose of these ontologies is to facilitate automated evidence aggregation in fields which are struggling to keep up with the body of published literature, and to structure and improve reporting of novel results to further enable cumulative domain science. 

I am also contributing to the [Open Energy Ontology](https://github.com/OpenEnergyPlatform/ontology) effort to develop an ontology to drive and unify the field of energy modelling, a prerequisite in the move away from fossil fuels towards a new energy economy. 

I currently develop the [Mental Functioning](https://github.com/jannahastings/mental-functioning-ontology/) suite of ontologies for mental health research. In the context of mental health I am particularly interested in the role that ontologies can serve as a mediator between vastly different perspectives, since in mental health research there are wide gaps between the terminology and methodological approaches between, for example, clinical research and psychological, the social sciences and the biological. 

I am also contributing to the development of ontologies for the digital humanities, in particular for classification and retrieval of literature based on rich descriptions of [themes](https://arxiv.org/abs/1905.00522) and [characters](http://ceur-ws.org/Vol-2518/paper-WODHSA4.pdf). 

Historically, I was involved in the development of the [ChEBI](https://www.ebi.ac.uk/chebi/) chemical ontology, the [CHEMINF](http://www.ontobee.org/ontology/cheminf) ontology of chemical information entities, the [eNanoMapper](http://www.enanomapper.net/) ontology for nanomaterials, and the [Basic Formal Ontology](http://basic-formal-ontology.org/) shared, standardised upper level ontology. 

Moreover, I have also worked on methods development to better harness the knowledge encoded in ontologies for research purposes, and on best practices in ontology development. 


### Computational Biology, multi-omics and metabolic modelling

For my [PhD in computational biology](https://www.repository.cam.ac.uk/handle/1810/296185), I investigated the metabolic influences on ageing in C. elegans using a variety of data science methods to study a time series dataset of interlinked gene expression and metabolite level measurements. In addition to implementing a standard workflow for each data layer of data cleaning, harmonisation, normalisation and interpretation using regression-based models, I was particularly interested in developing integrative approaches to co-analyse the two layers together in 'multi-omics' approaches. To this end I investigated methods for the data-driven inference of bipartite gene-metabolite networks.  

A particular area of my research involved the use of mathematical constraint-based modelling of metabolism harnessing an approach known as flux balance analysis. I contributed to the development of the [WormJam](https://gh.wormjam.life/) whole-genome model of C. elegans metabolism and I developed a novel method for combining time-series metabolomics data with this type of metabolic model. 


### Cheminformatics and chemical ontology

During the time I was working on the ChEBI chemical ontology I became interested in the interrelationship between computational logic-based knowledge representations (i.e. ontologies) and the chemical classifications that are based on graph-based representations of chemical structural information to achieve the objective of _structure-based chemical ontology classification_. Structure-based chemical ontology classification refers, broadly, to two interconnected sets of capabilities. The first is for a hierarchy of chemical ontology classes to be dynamic and computable (i.e. self-rearranging when content is updated), including specification of 'full' (i.e., necessary and sufficient) class definitions. The second is for novel chemical structurally defined entities (e.g. molecules) to be able to be automatically and computationally placed appropriately within this ontology hierarchy. Ontology technologies such as the semantic web standard Web Ontology Language - [OWL](https://www.w3.org/OWL/) - are able to perform very efficient automated classification of large knowledge bases based on logically encoded full class definitions. On the other hand, within the cheminformatics domain there are technologies for chemical structure encoding, defining and matching at the class level, e.g. the [SMARTS](https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html) language for specifying classes of molecules based on structural patterns. Chemical ontology [sits uneasily](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-4-8) between these two traditions with their separate technological infrastructures, and it is an exciting research frontier to create bridges between them to enable structure-based chemical ontology classification. 

My early attempt to support chemical structures from within an extension of the OWL ontology language to support graph-like structures was [reported in 2010](https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html), and this work was later [separately developed](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4040517/) into a separate logical formalism dedicated to representing and reasoning with graph-based structures and rules. However, as this formalism is not part of the core OWL ontology language it has not been widely adopted so far, and native cheminformatics technologies for performing operations with chemical structures are still more efficient. Within the cheminformatics community, the SMARTS language provides a natural formalism for encoding chemical class definitions. Both commercial and non-commercial methods have been developed to associate chemical ontology classes with SMARTS patterns for the purpose of linking cheminformatics to chemical ontology. At the time of writing, the [ClassyFire](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5096306/) algorithm is the state of the art for structure-based chemical ontology classification, with the largest knowledge base of rules and an associated ontology of 4,825 classes. However, ClassyFire does not harness OWL technology, and the SMARTS chemical class definitions are not integrated with the definitions of ontology classes, nor are the rules for selecting the most appropriate parent when several structural matches are obtained integrated. Thus, the associated chemical ontology still has to be maintained manually, and updating the integrated knowledge system can only be accomplished by updating the custom software suite. 

My ongoing research in this area includes: 
* developing an OWL-based language for formally encoding chemical class definitions
* investigating the use of machine learning for predicting chemical classes that are based on family resemblances rather than strict substructures or logical definitions










