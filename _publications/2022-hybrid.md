---
title: "A hybrid architecture for labelling bilingual Māori-English tweets"
collection: publications
permalink: /publication/2022-hybrid
date: 2022-11-20
venue: "Findings of the Association for Computational Linguistics: AACL-IJCNLP 2022"
paperurl: "https://aclanthology.org/2022.findings-aacl.11/"
citation: "Trye, D., Yogarajan, V., König, J., Keegan, T. T., Bainbridge, D., & Apperley, M. (2022). A hybrid architecture for labelling bilingual Māori-English tweets. In <i>Findings of the Association for Computational Linguistics: AACL-IJCNLP 2022</i>, pp. 119-130."
---

Quick links: [paper](https://aclanthology.org/2022.findings-aacl.11.pdf), [presentation video](https://drive.google.com/file/d/1wL6IbbbpMp11QcHdDpKxq01LdXWlTFQu/view?usp=sharing), [code](https://github.com/bilingual-MET/hybrid), [slides](http://dgt12.github.io/files/IJCL_am.pdf), [corpus explorer](https://bilingual-met.github.io/hybrid), [error analysis](https://bilingual-met.github.io/hybrid/sample)

Most large-scale language detection tools perform poorly at identifying Māori text. Moreover, rule-based and machine learning-based techniques devised specifically for the Māori-English language pair struggle with interlingual homographs. We develop a hybrid architecture that couples Māori-language orthography with machine learning models in order to annotate mixed Māori-English text. This architecture is used to label a new bilingual Twitter corpus at both the token (word) and tweet (sentence) levels. We use the collected tweets to show that the hybrid approach outperforms existing systems with respect to language detection of interlingual homographs and overall accuracy. We also evaluate its performance on out-of-domain data. Two interactive visualisations are provided for exploring the Twitter corpus and comparing errors across the new and existing techniques. The architecture code and visualisations are available online, and the corpus is available on request.