---
title: "Language Model Inversion through End-to-End Differentiation"

authors:
- admin
- Kartic Subr

date: "2026-02-11T00:00:00Z"
doi: ""

publication_types: ["3"]

abstract: "Despite emerging research on Language Models (LM), few approaches analyse the invertibility of LMs. That is, given a LM and a desirable target output sequence of tokens, determining what input prompts would yield the target output remains an open problem. We formulate this problem as a classical gradient-based optimisation. First, we propose a simple algorithm to achieve end-to-end differentiability of a given (frozen) LM and then find optimised prompts via gradient descent. Our central insight is to view LMs as functions operating on sequences of distributions over tokens (rather than the traditional view as functions on sequences of tokens). Our experiments and ablations demonstrate that our DLM-powered inversion can reliably and efficiently optimise prompts of lengths 10 and 80 for targets of length 20, for several white-box LMs (out-of-the-box)."

tags: ["Differentiable Language Models", "Gradient-based Optimization", "Language Model Inversion", "Natural Language Processing"]

featured: true

url_pdf: 'https://arxiv.org/abs/2602.11044'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []

slides: ""
---
