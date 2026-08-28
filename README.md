# Awesome AI-Powered Literature Discovery

A curated collection of research papers, datasets, AI tools, GitHub implementations, and learning resources related to **AI-powered academic literature discovery**. This repository accompanies the research paper *A Comparative Evaluation of AI-Powered Literature Discovery Tools Across Disciplines*.

The repository focuses on how AI can help researchers discover, organize, connect, and evaluate scholarly literature across different academic disciplines.

## Table of Contents

* [Topic Overview](#topic-overview)
* [AI-Assisted Research Paper](#ai-assisted-research-paper)
* [Citation Integrity Audit](#citation-integrity-audit)
* [Curated Research Papers](#curated-research-papers)
* [Datasets](#datasets)
* [Tools and Libraries](#tools-and-libraries)
* [GitHub Implementations](#github-implementations)
* [Tutorials and Learning Resources](#tutorials-and-learning-resources)
* [Recommended Workflow](#recommended-workflow)
* [Limitations](#limitations)
* [License](#license)

---

## Topic Overview

The rapid growth of academic publications makes it increasingly difficult for researchers to find relevant literature. Traditional academic databases provide keyword, author, subject, and citation searches, but they may not easily reveal less obvious relationships between publications.

AI-powered literature discovery tools use techniques such as semantic search, natural-language processing, machine learning, citation analysis, and knowledge graphs to improve scholarly discovery. This project focuses on **Semantic Scholar, Elicit, ResearchRabbit, Connected Papers, and Litmaps**.

The research compares these tools across **computer science, biomedical science, social science, and humanities** using six criteria: relevance, coverage, novel discovery, efficiency, usability, and transparency.
The main conclusion is that there is no single best tool for every research task. Semantic Scholar and Elicit are useful for semantic and question-oriented discovery, while ResearchRabbit, Connected Papers, and Litmaps are particularly useful for citation-network exploration.

---

## AI-Assisted Research Paper

### A Comparative Evaluation of AI-Powered Literature Discovery Tools Across Disciplines

**Description:**
This research paper compares five AI-powered literature discovery tools across four academic disciplines. It evaluates relevance, coverage, novel discovery, efficiency, usability, and transparency and proposes a hybrid workflow combining AI tools with conventional academic databases and human judgment.

**Paper:** [View Research Paper](paper/AI_Assisted_Research_Paper.pdf)

> **Note:** The results in the paper are explicitly described as illustrative/hypothetical rather than empirical measurements.

---

## Citation Integrity Audit

The references and claims used in this project were checked against the original papers and authoritative scholarly sources where available. Important bibliographic information should always be verified before using a reference.

**Audit:** [View Citation Integrity Audit](citation-audit/Citation_Integrity_Audit.pdf)

---

# Curated Research Papers

## Survey and Review Papers

1. **Artificial Intelligence in Literature Review Synthesis** — Mtotywa et al. (2026)
   [Paper](https://www.mdpi.com/2227-9709/13/3/43) — Discusses AI-assisted literature-review synthesis.

2. **Developing a Critical Imagination for AI-Assisted Literature Reviews** — Foley et al. (2025)
   [DOI](https://doi.org/10.1177/16094069251316249) — Examines responsible and reflexive AI use.

3. **Artificial Intelligence Tools in Biomedical Research: Part 1** — Sen (2026)
   [DOI](https://doi.org/10.1177/15230864251405885) — Reviews AI tools for biomedical literature search.

4. **Artificial Intelligence for Research Lifecycle: Challenges and Opportunities** — Yaroshenko & Iaroshenko (2023)
   [Paper](https://unilibnsd.ust.edu.ua/article/view/294639) — Discusses AI across the research lifecycle.

5. **Our AI-Powered Discoveries Are Trapped in a Predigital System** — Chew (2026)
   [Paper](https://www.jmir.org/2026/1/e96018) — Discusses challenges in AI-powered academic discovery.

## Foundational and Methods Papers

6. **Construction of the Literature Graph in Semantic Scholar** — Ammar et al. (2018)
   [ACL](https://aclanthology.org/N18-3011/) — Introduces the Semantic Scholar literature graph.

7. **S2ORC: The Semantic Scholar Open Research Corpus** — Lo et al. (2020)
   [ACL](https://aclanthology.org/2020.acl-main.447/) — Large scholarly corpus for NLP and text mining.

8. **SPECTER: Document-level Representation Learning using Citation-informed Transformers** — Cohan et al. (2020)
   [Paper](https://aclanthology.org/2020.acl-main.754/) — Uses citation information for scientific document representations.

9. **SciDocs: A Dataset and Evaluation Suite for Scientific Document Representations**
   [GitHub](https://github.com/allenai/scidocs) — Benchmark for scientific document representations.

10. **ASReview: A Machine Learning Framework for Efficient Systematic Reviews** — van de Schoot et al. (2021)
    [Nature](https://www.nature.com/articles/s42256-020-00287-7) — Machine learning for literature screening.

## AI Research Assistants and Literature Review

11. **The Development of a RAG-Based Artificial Intelligence Research Assistant (AIRA)** — Vakilzadeh & Wood (2026)
    [Paper](https://publications.aaahq.org/jis/article-abstract/40/1/77/13751) — Research assistant using retrieval-augmented generation.

12. **Harnessing Artificial Intelligence for Advancing Medical Manuscript Composition** — Singh et al. (2024)
    [Cureus](https://www.cureus.com/articles/308672-harnessing-artificial-intelligence-for-advancing-medical-manuscript-composition-applications-and-ethical-considerations) — Discusses AI use and ethical considerations in research writing.

13. **Large Language Models in Radiography Research: A Narrative Review** — Rainey et al. (2026)
    [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1078817425003888) — Reviews LLM applications in radiography research.

14. **Augmenting Art Historical Research** — Hutson (2025)
    [Springer](https://link.springer.com/chapter/10.1007/978-3-032-02920-1_3) — Discusses AI in humanities/art-history research.

15. **PRISMA 2020: An Updated Guideline for Reporting Systematic Reviews** — Page et al. (2021)
    [PRISMA](https://www.prisma-statement.org/prisma-2020) — Important reporting standard for systematic reviews.

## Evaluation and Scholarly Retrieval

16. **OpenAlex: A Fully-Open Index of Scholarly Works** — Priem et al.
    [Paper](https://arxiv.org/abs/2205.01833) — Open scholarly knowledge graph.

17. **SPECTER: Citation-Informed Scientific Document Embeddings**
    [GitHub](https://github.com/allenai/specter) — Implementation for scientific document representations.

18. **SYNERGY: Open Machine Learning Dataset on Study Selection in Systematic Reviews** — De Bruin et al. (2023)
    [GitHub](https://github.com/asreview/synergy-dataset) — Dataset for information-retrieval and systematic-review research.

19. **Scientific Document Representation Evaluation**
    [SciDocs](https://github.com/allenai/scidocs) — Evaluation tasks for scientific document representations.

20. **S2ORC: Semantic Scholar Open Research Corpus**
    [GitHub](https://github.com/allenai/s2orc) — Scholarly corpus for NLP and scientific text mining.

---

# Datasets

| Dataset      | Description                                         | Use                                 | Source                                                 |
| ------------ | --------------------------------------------------- | ----------------------------------- | ------------------------------------------------------ |
| **OpenAlex** | Open scholarly knowledge graph                      | Citation and literature analysis    | [OpenAlex](https://openalex.org/)                      |
| **S2ORC**    | Scholarly papers and citation data                  | NLP and literature mining           | [S2ORC](https://github.com/allenai/s2orc)              |
| **SYNERGY**  | 169,288 academic records from 26 systematic reviews | Information retrieval and screening | [SYNERGY](https://github.com/asreview/synergy-dataset) |

SYNERGY contains titles, abstracts, authors, references, topics, and inclusion labels, making it useful for information-retrieval experiments.

---

# Tools and Libraries

1. **[Semantic Scholar](https://www.semanticscholar.org/)** — AI-powered academic search and citation discovery.
2. **[Elicit](https://elicit.com/)** — Question-oriented literature discovery and evidence extraction.
3. **[ResearchRabbit](https://www.researchrabbit.ai/)** — Citation and author-network exploration.
4. **[Connected Papers](https://www.connectedpapers.com/)** — Visual exploration of related papers.
5. **[Litmaps](https://www.litmaps.com/)** — Citation mapping and literature monitoring.

Semantic Scholar also provides an Academic Graph API for papers, authors, citations, venues, and related scholarly data.

---

# GitHub Implementations

1. **[S2ORC](https://github.com/allenai/s2orc)** — Scholarly text and citation corpus.
2. **[SPECTER](https://github.com/allenai/specter)** — Scientific document representation model.
3. **[SciDocs](https://github.com/allenai/scidocs)** — Scientific document evaluation suite.
4. **[ASReview](https://github.com/asreview/asreview)** — Machine-learning-assisted systematic-review screening.
5. **[SYNERGY Dataset](https://github.com/asreview/synergy-dataset)** — Dataset for systematic-review information retrieval.

---

# Tutorials and Learning Resources

1. **[Semantic Scholar API Tutorial](https://www.semanticscholar.org/product/api/tutorial)** — Learn to work with scholarly data.
2. **[Semantic Scholar API](https://www.semanticscholar.org/product/api)** — Official API documentation.
3. **[OpenAlex Documentation](https://developers.openalex.org/)** — Learn to query scholarly data.
4. **[ASReview Documentation](https://asreview.readthedocs.io/)** — Guide to AI-assisted systematic reviews.
5. **[PRISMA 2020](https://www.prisma-statement.org/prisma-2020)** — Systematic-review reporting guidance.

---

# Recommended Workflow

The research paper proposes a five-stage workflow:

1. **Initial Search** — Use conventional databases and Semantic Scholar.
2. **Question-Oriented Discovery** — Use Elicit.
3. **Citation Expansion** — Use ResearchRabbit, Connected Papers, or Litmaps.
4. **Verification** — Check important publications against original and authoritative sources.
5. **Critical Evaluation** — Evaluate methodology, evidence, limitations, and relevance.

The goal is to use AI as a **research assistant**, not as a replacement for scholarly judgment.

---

# Limitations

AI-powered literature discovery has several limitations:

* Incomplete database coverage
* Algorithmic bias
* Incorrect or hallucinated information
* Changing search rankings
* Reproducibility problems
* Over-reliance on AI recommendations

Researchers should always verify important references and critically evaluate the original research.

---

# License

This repository's original content is released under the **MIT License**.

Third-party papers, datasets, software, trademarks, and other resources remain under their respective licenses.

See [LICENSE](LICENSE) for details.

---

## Disclaimer

This repository is intended for educational and research purposes. AI-powered tools should support literature discovery but should not replace researcher verification, critical reading, or scholarly judgment.
