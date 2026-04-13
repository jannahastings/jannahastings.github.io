---
layout: post
title: New article published! A method to detect trends in the mental health literature
date: 2026-04-13
inline: false
related_posts: false
---
Can we automatically detect emerging trends and essential new directions for promising new research directions from the published mental health literature? :sparkles:

Recently, we published a method that aims to do just this - using a mix of embedding-based topic modelling with time series models and forecasting. In broad outline, the method first detects topics in the published literature for the previous decade, and then builds a time series model of the number of publications per topic. To predict trendiness, the method probes whether a given topic has recently outperformed its predicted evolution time series - and if so, assigns a rank to track by how much. 

This is part of our work stream in the GALENOS project (galenos.org.uk) that aims to do more with AI to address unanswered questions and prioritise new directions for better treatments to improve lives for those affected by mental health.

To learn more, read the paper: [Automatically detecting trends and open questions from mental health publications: a Wellcome-funded GALENOS project](https://mentalhealth.bmj.com/content/29/1/e302379)
