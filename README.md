# SDEWES Waste & Climate Analysis

This repository contains the research project behind the paper **“Do Public Environmental Narratives Reflect Waste Sector Climate Priorities? A Comparative EU and Non-EU Analysis.”**

The study compares **Macedonia** and **Spain** to investigate whether public environmental discourse reflects the actual climate priorities identified in national waste-sector greenhouse gas inventories.

## Project Overview

The project combines:

* greenhouse gas inventory analysis
* social media data collected from X
* sentiment analysis
* topic modeling
* qualitative comparison between public discourse and national mitigation priorities

The analysis covers waste-related social media posts from **8 May 2024 to 6 October 2025**.

After preprocessing and relevance filtering, the final dataset contained:

* **5,613 posts from Macedonia**
* **3,143 posts from Spain**
* **8,756 relevant posts in total**

## Methods

The NLP pipeline includes:

* **BERTweet** for sentiment analysis
* **Twitter-RoBERTa** for sentiment comparison
* **BERTopic** for topic modeling
* **UMAP** for dimensionality reduction
* **HDBSCAN** for clustering

Posts written in Macedonian and Spanish were translated into English before analysis.

## Main Findings

Both countries have solid waste disposal as the dominant source of waste-sector greenhouse gas emissions.

However, the public narratives differ substantially.

### Macedonia

Public discussion is dominated by:

* landfill fires
* illegal dumping
* waste accumulation
* smoke and odors
* visible waste-management failures

The discourse shows **partial alignment** with national climate priorities because public attention focuses mainly on immediate environmental problems rather than long-term mitigation measures.

### Spain

Public discussion focuses more strongly on:

* circular economy
* recycling
* sustainable packaging
* resource recovery
* environmental responsibility

The discourse shows **strong alignment** with national mitigation priorities.

## Repository Structure

```text
sdewes-waste-climate-analysis/
│
├── README.md
├── paper/
│   └── SDEWES_paper.pdf
├── notebooks/
├── figures/
├── tables/
└── .gitignore
```

## Paper

The full research paper is available in the [`paper`](paper/) directory.

## Authors

This project is based on the research paper:

**“Do Public Environmental Narratives Reflect Waste Sector Climate Priorities? A Comparative EU and Non-EU Analysis”**

**Authors:** Martina Spirovska, Marija Stojcheva, Aleksandra Dedinec, Jana Prodanova, Aleksandar Dedinec, Verica Taseska-Gjorgievska, Tatjana Dzambazova, Emilija Mihajloska, Dejan Dimitriev, Onur Amet, and Ljupco Kocarev.

**Affiliations:** Faculty of Computer Science and Engineering, Ss. Cyril and Methodius University, Skopje, and Macedonian Academy of Sciences and Arts.

## Technologies

Python, BERTweet, RoBERTa, BERTopic, UMAP, HDBSCAN, NLP, sentiment analysis, topic modeling
