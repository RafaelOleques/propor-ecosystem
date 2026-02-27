# The PROPOR Ecosystem: Structure, Roles, and Evolution of Portuguese-Language NLP 🇵🇹

This repository contains the dataset, analysis scripts, and metadata for the longitudinal bibliometric study of the **PROPOR (International Conference on Computational Processing of Portuguese)** covering the period from **2003 to 2024**.

The study examines the thematic evolution, community structure, and scientific impact of two decades of academic production in Natural Language Processing (NLP) specifically for the Portuguese language.

---

## 📊 Study Overview

The analysis is guided by three fundamental research questions:

| ID | Research Question | Analytical Focus |
| --- | --- | --- |
| **RQ1** | **Thematic Landscape** | Evolution of research topics, NLP tasks, and language variants. |
| **RQ2** | **Community Structure** | Author retention, renewal, and institutional collaboration networks. |
| **RQ3** | **Scientific Impact** | Citation dynamics, productivity, and the "long-tail" distribution of impact. |

---

## 🔍 Key Findings

* **Paradigm Shift:** A structural transition from speech-oriented research (*Speech Technologies*) to text-based tasks and language models.
* **The Two Pillars:** "Resources & Evaluation" and "NLP Tasks" remain the most stable and central topics throughout the conference history.
* **Theoretical Resilience:** Unlike many purely empirical global venues, PROPOR maintains a unique and recurring engagement with Linguistic Theory and Description.
* **Stable Collaboration:** The community exhibits a "core-periphery" dynamic, with strong leadership hubs in Brazil and Portugal.

---
### 🛠️ Methodology & Corpus

We analyzed a comprehensive corpus of **429 papers** (2003–2024), curated through a rigorous four-stage process:

1. **Collection:** Metadata integrated from **Springer** (2003–2022) and the **ACL Anthology** (2024). Citation data and affiliations were retrieved via the **OpenAlex API**, with 87 entries manually verified to ensure data integrity.
2. **Expert Annotation:** 8 NLP researchers manually labeled each paper using the official PROPOR taxonomy (11 thematic axes), providing a high-fidelity mapping of the field's evolution.
3. **Adjudication:** A consensus phase resolved categorical ambiguities (e.g., *Tasks* vs. *Applications*).
4. **Network Analysis:** Structural mapping of the community using co-authorship and institutional graphs.

---

## 📝 Citation

If you use this data or these findings in your research, please cite the original paper:

```bibtex
@inproceedings{nunes-etal-2026-propor-ecosystem,
    title = "The PROPOR Ecosystem: Structure, Roles, and Evolution of Portuguese-Language NLP",
    author = "Nunes, Rafael O. and 
              Tamiosso, Gustavo L. and 
              de Andrade, Pedro L. C. and 
              de Aguiar, Matheus S. and 
              de Gouveia, Rafael P. and 
              Moreira, Higor and 
              Tavares, Bruno and 
              de Gouveia, Laura P. and 
              Paula, Felipe S. F. and 
              Spritzer, Andre and 
              Balreira, Dennis G. and 
              Carbonera, Joel L. and 
              Albuquerque, Hidelberg O. and 
              da Silva, N{\'a}dia F. F. and 
              Pereira, Ellen P. R. S.",
    booktitle={Proceedings of the International Conference on the Computational Processing of Portuguese (PROPOR 2026)},
    year={2026},
    address={Porto Alegre, Brazil},
    note={Forthcoming / To appear}
}

```

---

## 🤝 Contact

For questions regarding the annotation methodology or data access:

* **Correspondence:** ronunes [at] inf.ufrgs.br
* **Involved Institutions:** UFRGS, USP, UFRPE, UFG.
