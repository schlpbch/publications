# Andreas Schlapbach's Publications

A curated collection of academic papers and research publications. The early
work explores two foundational ideas in software engineering: the **π-calculus**
as a formal basis for component composition languages, and the **Meta-Object
Facility (MOF)** as a meta-meta-model for language-independent metamodel
interchange via XMI.

Later work applies **machine learning** (Gaussian Mixture Models, Hidden Markov
Models, Support Vector Machines) to handwriting recognition and writer
identification,

Recent research focuses on the design and formal verification of **LLM agentic
systems**, proposing new paradigms for agent interoperability and tool protocol
semantics.

This repository serves as a comprehensive archive of these contributions,
spanning from foundational software composition theories to cutting-edge AI
agent research.

## Publications

### Preprints

1. [The Convergence of SGD and MCP: A New Paradigm for Agentic Interoperability](2602.18764v2.pdf)
   (arXiv, 2026)
2. [Formal Semantics for Agentic Tool Protocols: A Process Calculus Approach](2603.24747v1.pdf)
   (arXiv, 2026)

### Books

3. Writer Identification and Verification
   (PhD thesis, IOS Press, DISKI series, February 2008; ISBN: 978-1-58603-825-0)
4. [Machine Learning in Document Analysis and Recognition](MainLDAR.pdf)
   (book draft, 2007)

### Journal Articles

5. Automatic Gender Detection Using on-Line and Off-Line Information
   (Pattern Analysis and Applications, 14(1):87–92, 2011;
   DOI: [10.1007/s10044-010-0178-6](https://doi.org/10.1007/s10044-010-0178-6))
6. [Automatic Gender Detection – Combining On-Line and Off-Line Systems](ijprai2008.pdf)
   (International Journal of Pattern Recognition and Artificial Intelligence, 2008)
7. [A Writer Identification System for On-line Whiteboard Data](onlineWIJournal.pdf)
   (Pattern Recognition, 2006)
8. [A Writer Identification and Verification System Using HMM Based Recognizers](journalPaperFinal.pdf)
   (Pattern Analysis and Applications, 2006)

### Book Chapters

9. [Off-line Writer Identification and Verification Using Gaussian Mixture Models](offWriIdeVerGMM.pdf)
   (book chapter, 2007)

### Conference Papers

10. Automatic Estimation of the Readability of Handwritten Text
    (EUSIPCO 2008)
11. Estimating the Readability of Handwritten Text – A Support Vector Regression Based Approach
    (ICPR 2008)
12. Writer-Dependent Recognition of Handwritten Whiteboard Notes in Smart Meeting Room Environments
    (DAS 2008; DOI: [10.1109/DAS.2008.8](https://doi.org/10.1109/DAS.2008.8))
13. Automatic Detection of Gender and Handedness from On-Line Handwriting
    (2007)
14. [Writer Identification for Smart Meeting Room Systems](LNCS-3872.pdf)
    (DAS 2006, LNCS 3872, pp. 186–195; also available as [author preprint](das06.pdf))
15. [Off-line Writer Identification Using Gaussian Mixture Models](icpr06.pdf)
    (ICPR 2006)
16. [Off-Line Writer Verification: A Comparison of a Hidden Markov Model (HMM) and a Gaussian Mixture Model (GMM) Based System](iwfhr06.pdf)
    (IWFHR 2006)
17. [Improving Writer Identification by Means of Feature Selection and Extraction](icdar05.pdf)
    (ICDAR 2005)
18. [Writer Identification Using an HMM-Based Handwriting Recognition System: To Normalize the Input or Not?](igs05.pdf)
    (IGS 2005)
19. [Off-line Handwriting Identification Using HMM Based Recognizers](icpr04.pdf)
    (ICPR 2004)
20. [Using HMM Based Recognizers for Writer Identification and Verification](iwfhr04.pdf)
    (IWFHR 2004)

### Theses & Technical Reports

21. Writer Identification and Verification
    (PhD thesis, Universität Bern, 2008 — published as book; see entry 3)
22. [Enabling White-Box Reuse in a Pure Composition Language](Schl03a.pdf)
    (Diplomarbeit, Universität Bern, December 2002)
23. [Generic XMI Support for the MOOSE Reengineering Environment](Schl01a.pdf)
    (technical report, Universität Bern, June 2001)

### Presentations

24. [IWFHR 2006 presentation slides](iwfhr06Slides.pdf)

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#aec6cf', 'primaryTextColor': '#eee', 'primaryBorderColor': '#eee', 'lineColor': '#999999', 'secondaryColor': '#b5ead7', 'tertiaryColor': '#ffdac1'}}}%%
mindmap
  root((Research Focus))
    Software Composition & Reengineering
      π-Calculus-Based Composition Language
      Agents · Forms · Channels
      XMI & XML Metadata Interchange
      MOF Meta-Meta-Model
      MOOSE Reengineering Environment
      Component-Oriented Programming
      White-Box vs Black-Box Reuse
    Handwriting & Documents
      Machine Learning - GMM · HMM · SVM
      Handwriting Recognition & Analysis
      Writer Identification - Offline & Online
      Document Analysis & Pattern Recognition
    LLM Agentic Systems
      Agent Tool Protocols - SGD & MCP
      Formal Verification & Process Calculus
      AI Governance & Schema-Driven Interoperability
```

## Document Organization

All papers are organized chronologically by publication year and venue:

- **2001** — Technical report on XMI/MOOSE (Universität Bern)
- **2002** — Diplomarbeit on white-box reuse in JPiccola (Universität Bern)
- **2004** — ICPR, IWFHR initial conferences
- **2005** — ICDAR, IGS publications
- **2006** — DAS, ICPR, IWFHR follow-up work
- **2007** — Book draft on machine learning in document analysis; book chapter on GMM-based writer identification; gender/handedness detection
- **2008** — PhD thesis book (IOS Press/DISKI); DAS whiteboard recognition; EUSIPCO, ICPR readability estimation; IJPRAI gender detection
- **2011** — Pattern Analysis and Applications gender detection journal paper
- **2026** — arXiv preprints on LLM agentic systems

## How to Use This Repository

1. **Browse papers** — All PDFs are in the root directory
2. **Review by topic** — Check the conference/journal name for specific focus
   areas
3. **Access full texts** — Each PDF contains the complete paper and results

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#aec6cf', 'primaryTextColor': '#eee', 'primaryBorderColor': '#eee', 'lineColor': '#999999', 'secondaryColor': '#b5ead7', 'tertiaryColor': '#ffdac1'}}}%%
timeline

    2001        : Schl01a
                : XMI/MOOSE Technical Report
    2002        : Schl03a
                : Diplomarbeit JPiccola
    2004 - 2006 : ICPR · IWFHR · DAS · ICDAR · IGS
                : Handwriting Recognition
                : Writer Identification
                : Document Analysis
    2007        : Book draft · Book chapter
                : Gender & Handedness Detection
    2008        : PhD thesis (IOS Press) · DAS
                : EUSIPCO · ICPR · IJPRAI
                : Readability Estimation
                : Gender Detection
    2011        : PAA
                : Gender Detection
    2026        : arXiv Preprints
                : LLM Agent Systems
                : Formal Verification
```

## About

This archive preserves research publications in:

- **Software composition grounded in the π-calculus** (agents, forms, channels)
- **Component-oriented programming and white-box/black-box reuse strategies**
- **XMI/XML metadata interchange, meta-modeling, and the MOF meta-meta-model**
- **Machine learning for document analysis** (Gaussian Mixture Models, Hidden
  Markov Models, Support Vector Machines)
- **Handwriting recognition and analysis**
- **Writer identification and verification**
- **Document image analysis and pattern recognition**
- **LLM agent systems and tool protocols (SGD, MCP)**
- **Formal verification of agentic systems**
- **AI governance and schema-driven interoperability**
