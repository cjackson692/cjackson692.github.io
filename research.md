---
layout: default
title: Research & Projects — Carter Smith
description: Research projects, publications, and coursework
---

[Home](./) · [Research & Projects](./research) · [Teaching](./teaching) · [LinkedIn](https://www.linkedin.com/in/carter-smith-5b4887231) · [EVoAI Lab](https://linguistics.unt.edu/evo-ai/index.html)

---

# Research & Projects

This page enumerates research positions, publications, conference presentations, supervised theses, and selected coursework projects. Items are grouped by category and listed in reverse chronological order.

**Highlights:** one paper currently in review (*Germanic POS / error analysis*); three accepted international conference presentations under the name *Carter Smith* — GLAC 30 (2024), GLAC 31 (2025), and Protolang 9 (2025).

---

## Publications

### Neural network error analysis for understanding language change: Analyzing the distribution of syntactic categories in Early Germanic *(in review)*

**Smith, C.** (submitted). Single-author manuscript currently under peer review.

This study tests the efficacy of neural-network error analysis as a method for investigating syntactic change. A context-sensitive Bi-LSTM is trained to label syntactic categories of words in five historical Germanic languages (Old English, Old Saxon, Old High German, Old Icelandic, Gothic). Per-category accuracies are systematically examined to identify unusual error patterns both language-internally and cross-linguistically, which are then used to generate hypotheses about ongoing syntactic changes. Hypotheses are compared with the existing literature on Germanic syntactic change to validate the approach. The networks achieve high overall accuracy, and the error analysis surfaces several patterns of change previously noted using other methods. The study argues for the value of error-centric neural analysis as a tool in historical linguistics.

- **Repository:** [github.com/cjackson692/GermanicPOS](https://github.com/cjackson692/GermanicPOS)
- **Status:** In review for publication
- **Keywords:** Syntactic Change · Neural Networks · Error Analysis · Part-of-Speech Tagging · Historical Germanic

---

## Conference Presentations

All presentations below are listed under the author name **Carter Smith**.

### Using Neural Networks for Part-of-Speech Analysis to Investigate Syntactic Evolution and Change

**Smith, C.** & Hartmann, F. (September 2025). **Protolang 9**, Vienna, Austria.

Investigated using Bi-directional Long-Short Term Memory (Bi-LSTM) models to tag POS across five historical Germanic languages. Reported mono-language tagging accuracies (overall 80–91% range across OE, OS, OHG, OI, GO) and used ablation analysis to identify class-wise predictability patterns associated with observed syntactic differences. Skip-gram models on syntactic categories were used to compare cross-linguistic patterning of POS, then multilingual models were tested for cross-linguistic generalization. Findings include that lower predictive accuracy of ADJ in Old English (vs. OHG/OI/OS) tracks the more restricted attested adjective–noun ordering in OE, and that the OHG determiner shows a content-word-like learnability curve distinct from the function-word pattern observed in other languages.

- **Status:** Accepted; presented September 2025
- **Repository:** [github.com/cjackson692/GermanicPOS](https://github.com/cjackson692/GermanicPOS)

---

### Expanding Neural Part-of-Speech Analysis of Historical Germanic Languages

**Smith, C.** (May 2025). **Germanic Linguistics Annual Conference 31 (GLAC 31)**, Denton, TX.

Sole-authored expansion of the earlier GLAC 30 study, broadening the dataset from a smaller Germanic subset to Old Saxon, Old English, Old High German, Old Icelandic, and Gothic. Reported accuracies in the 87–90% range for OS / OE / OI / GO, and ~80% for OHG. Secondary ablation analyses revealed predictability trends across Determiners, Adjectives, Adverbs, Conjunctions, and Complementizers, and motivated the broader error-analysis framework subsequently developed in the *in-review* manuscript.

- **Status:** Accepted; presented May 2025

---

### Neural Part-of-Speech Analysis in Historical Germanic

**Smith, C.** & Hartmann, F. (April 2024). **Germanic Linguistics Annual Conference 30 (GLAC 30)**, Bloomington, IN.

Initial study testing Bi-LSTM neural network architectures for automatic POS annotation on a smaller Germanic subset, establishing baseline feasibility of context-sensitive neural POS tagging for low-resource historical languages and motivating subsequent multi-language and ablation work.

- **Status:** Accepted; presented April 2024

---

### Using Information-Theoretic Metrics to Compare Natural and Constructed Language

**Smith, C.** & Beeler, A. (November 2023). **DFW Metroplex Linguistic Conference**, Dallas, TX.

Co-authored talk comparing natural and constructed languages through information-theoretic metrics. Built computational language models and conducted lexicon-level analysis to operationalize cross-system comparison.

---

### Computational Information Theory Applied to Constructed Languages

Beeler, A. & **Smith, C.** (November 2023). Poster, **UNT College of Information 15th Anniversary Celebration**, Denton, TX.

Poster presentation of the same research thread as above.

---

### Accessing Roviana Language Data Through Computation

**Smith, C.** (April 2022). **UNT Scholars Day 2022**, Denton, TX.

Reported on the digitization of Roviana language data into a machine-readable format and the development of a decision-tree tool for identifying grammatical forms within the Roviana language.

---

## Research Positions

### Graduate Research Assistant — NSF *NeuraRec* Project

**University of North Texas, Department of Linguistics — EVoAI Lab** **Sept 2025 – Present** PI: Dr. Frederik Hartmann

Working as part of the [UNT EVoAI Lab](https://linguistics.unt.edu/evo-ai/index.html) on an NSF-funded project focused on developing neural models for proto-language reconstruction.

---

### Research Team Member — UNT Computational Linguistics Lab

**University of North Texas, Department of Linguistics** **Sept 2023 – Present** Supervisor: Dr. Frederik Hartmann

Working on the comparison of natural and constructed languages through information-theoretic metrics. Created computational language models and conducted in-depth lexicon analysis. Collaborated with a research team across multiple levels of academia and with outside experts.

---

### Research Assistant — Department of Linguistics

**University of North Texas** **May 2023 – July 2025** Supervisor: Dr. Frederik Hartmann

Assisted with data processing and computational modeling for studies of diachronic semantic change, language evolution, and geographical–phonological complexity.

---

### Honors Undergraduate Thesis — *Neural Part-of-Speech Analysis of Historical Germanic Languages*

**UNT Honors College / Department of Linguistics** **Jan 2025 – May 2025** Faculty Advisor: Dr. Frederik Hartmann

Completed and defended an honors thesis project entitled *Neural Part-of-Speech Analysis of Historical Germanic Languages*. Received highest marks and earned the Distinguished Honors Award. This thesis directly seeded the in-review manuscript and the Protolang 9 presentation.

- **Repository:** [github.com/cjackson692/GermanicPOS](https://github.com/cjackson692/GermanicPOS)

---

### Honors Independent Study — Roviana Language Digitization

**UNT Honors College** **Jan 2023 – May 2023** Supervisor: Dr. Peter Schuelke

Worked under the supervision of Dr. Peter Schuelke and the advisement of the UNT Honors College on a project centered on the digitization of Roviana language data into machine-readable format, and the development of a decision-tree tool for identifying particular grammatical forms within Roviana. Earned course credit through research.

---

## Code Repositories

- **[GermanicPOS](https://github.com/cjackson692/GermanicPOS)** — Bi-LSTM POS-tagging models, ablation studies, skip-gram POS-embedding analysis, and multilingual experiments across five historical Germanic languages. Supports the in-review manuscript and the GLAC 30 / GLAC 31 / Protolang 9 presentations.
- **[Group1_NanoGPT](https://github.com/cjackson692/Group1_NanoGPT)** — Group project building on the NanoGPT framework; experimentation with small-scale transformer language modeling.
- **[CSCE_5218_Group1_Project](https://github.com/cjackson692/CSCE_5218_Group1_Project)** — Graduate Deep Learning (CSCE 5218) group project; deep-learning system implementation and evaluation.
- **[cjackson692.github.io](https://github.com/cjackson692/cjackson692.github.io)** — Source for this site.

---

## Selected Coursework Projects

The following are self-directed academic projects completed during graduate and upper-level coursework. They are listed to document methodological breadth (data mining, statistical modeling, NLP, syntax, phonology, semantics, SLA).

### Lexical Density in Old English Prose: Quantitative Analysis

*LING 5075 — Dr. Xian Zhang*

Quantitative study of the relationship between text type and lexical density in Old English prose. Extracted documents from the York–Toronto–Helsinki Parsed Corpus of Old English (YCOE, Taylor 2003), computed lexical density as the ratio of content to all words across 50-word segments, and coded each document for dialect, translation status, and genre. Built sequential beta-regression models (in R, `betareg`) with lexical density as outcome and translation status, dialect, and text type as sequential predictors; verified assumptions with Shapiro–Wilk, Breusch–Pagan, and Durbin–Watson tests. Used partial point-biserial correlation to identify per-genre effects with confounds removed. The full model accounted for 37.1% of variance, with genre contributing 18.8% beyond dialect and translation status.

### Learner Corpora in Second Language Acquisition: A Literature Review

*Second Language Acquisition — Dr. Xian Zhang* Co-authored with Punn Havananda

Surveyed 25 years of learner corpus research (LCR), from foundational corpora (ICLE) to recent multilingual and process-oriented corpora (PROCEED, CLEC). Discussed methodological paradigms, findings on lexicon / syntax / discourse development, applied educational impacts including CEFR-aligned work, and directions for future LCR (non-English data, spoken resources, proficiency measurement).

### German Credit Risk — Classification and Noisy-Data Sensitivity (Project 1)

*Data Mining course (R, milestones 1 & 2)*

Preprocessing and analysis of the German credit dataset in R: standardized continuous variables, handled categorical factors, addressed class imbalance, and trained classifiers. Milestone 2 introduced 10% label noise and re-ran the pipeline to characterize how each classifier degraded under noisy supervision.

### Congressional Voting Records — Association-Rule Mining (Project 2, Milestone 1)

*Data Mining course (R)*

Applied the apriori algorithm to UCI Congressional Voting Records. Carefully handled `?` as `NA`, factorized binary vote variables, applied descriptive column names from the metadata to keep rules interpretable, and exported rule bases to CSV.

### Obesity Levels — K-Means Clustering (Project 2, Milestone 2)

*Data Mining course (R)*

Preprocessed mixed-type obesity-levels data: converted ordinal string variables (CALC, NObeyesdad) to numeric, z-scaled all numeric features, ran K-Means at multiple K, and evaluated cluster solutions.

### Time-Series Forecasting (Project 3)

*Data Mining course (R, individual project)*

Achieved stationarity through differencing and transformation, diagnosed with ACF / PACF and ADF tests, and fit ARIMA-family models for forecasting.

### Group Deep-Learning Project — CSCE 5218

*Graduate Deep Learning course*

Group project implementing and evaluating a deep-learning system. **Repository:** [CSCE_5218_Group1_Project](https://github.com/cjackson692/CSCE_5218_Group1_Project).

### NanoGPT Group Experiments

*Group project*

Experimentation with small-scale transformer language modeling building on the NanoGPT framework. **Repository:** [Group1_NanoGPT](https://github.com/cjackson692/Group1_NanoGPT).

### Hiatus and Glide Insertion in Burushaski

*LING 5300 — Phonology — Dr. S. Munshi*

Analysis of morpho-phonological hiatus resolution and glide insertion patterns in Burushaski.

### Semantic Ambiguity in Mandarin Chinese

*LING 5530 — Semantics and Pragmatics — Dr. D. Roehrs*

Overview paper analyzing types and resolution mechanisms of semantic ambiguity in Mandarin Chinese.

### Movement in Icelandic Syntax

*Graduate Syntax coursework*

Analysis of three classes of movement in Icelandic — head-to-head (V-to-T and T-to-C), DP movement (unaccusatives, raising, passives), and WH movement — with motivating data and tree representations.

---

## Personal Projects

### Comparing Constructed and Natural Languages using Information Theory

Ongoing work, in collaboration with research team members and outside experts, applying information-theoretic metrics (entropy, redundancy, lexicon-level measures) to systematically compare constructed languages with natural-language baselines. Supports the 2023 DFW Metroplex Linguistic Conference talk and UNT COI 15th Anniversary poster.
