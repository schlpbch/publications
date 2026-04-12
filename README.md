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

---

## Main Publications

- [Generic XMI Support for the MOOSE Reengineering Environment](Schl01a.pdf)
  (technical report, Universität Bern, June 2001) — implements XMI (XML Metadata
  Interchange) support for MOOSE using the **Meta-Object Facility (MOF)** as a
  meta-meta-model: DTDs are generated directly from the MOF instance of the
  FAMIX metamodel, making the XMI layer generic across any FAMIX-compliant
  language model; supervised by Dr. Stéphane Ducasse and Sander Tichelaar
- [Enabling White-Box Reuse in a Pure Composition Language](Schl03a.pdf)
  (Diplomarbeit, Universität Bern, December 2002) — proposes a migration
  strategy from class inheritance (white-box) to component composition
  (black-box) using Piccola, a scripting language grounded in the
  **π-calculus**; demonstrates how π-calculus-based channel communication and
  agent composition replace inheritance hierarchies; supervised by Prof. Dr. O.
  Nierstrasz and Nathanael Schärli

### Core Research Papers

- [Machine Learning in Document Analysis and Recognition](MainLDAR.pdf)
  (book draft, 2007)
- [A Writer Identification and Verification System Using HMM Based Recognizers](journalPaperFinal.pdf)
  (Pattern Analysis and Applications journal)
- [Off-line Writer Identification and Verification Using Gaussian Mixture Models](offWriIdeVerGMM.pdf)
  (book chapter)
- [A Writer Identification System for On-line Whiteboard Data](onlineWIJournal.pdf)
  (Pattern Recognition journal, 2006)
- [The Convergence of SGD and MCP: A New Paradigm for Agentic Interoperability](2602.18764v2.pdf)
  (arXiv, 2026)
- [Formal Semantics for Agentic Tool Protocols: A Process Calculus Approach](2603.24747v1.pdf)
  (arXiv, 2026)

### Conference Presentations

- [Writer Identification for Smart Meeting Room Systems](das06.pdf) (DAS 2006)
- [Improving Writer Identification by Means of Feature Selection and Extraction](icdar05.pdf)
  (ICDAR 2005)
- [Off-line Handwriting Identification Using HMM Based Recognizers](icpr04.pdf)
  (ICPR 2004)
- [Off-line Writer Identification Using Gaussian Mixture Models](icpr06.pdf)
  (ICPR 2006)
- [Writer Identification Using an HMM-Based Handwriting Recognition System: To Normalize the Input or Not?](igs05.pdf)
  (IGS 2005)
- [Using HMM Based Recognizers for Writer Identification and Verification](iwfhr04.pdf)
  (IWFHR 2004)
- [Off-Line Writer Verification: A Comparison of a Hidden Markov Model (HMM) and a Gaussian Mixture Model (GMM) Based System](iwfhr06.pdf)
  (IWFHR 2006)
- [IWFHR 2006 presentation slides](iwfhr06Slides.pdf)

---

```mermaid
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

---

## 📋 Document Organization

All papers are organized chronologically by publication year and venue:

- **2001** — Technical report on XMI/MOOSE (Universität Bern)
- **2002** — Diplomarbeit on white-box reuse in JPiccola (Universität Bern)
- **2004** — ICPR, IWFHR initial conferences
- **2005** — DAS, ICDAR, IGS publications
- **2006** — ICPR, IWFHR follow-up work
- **2026** — arXiv preprints on LLM agentic systems

---

## 🔍 How to Use This Repository

1. **Browse papers** — All PDFs are in the root directory
2. **Review by topic** — Check the conference/journal name for specific focus
   areas
3. **Access full texts** — Each PDF contains the complete paper and results

---

```mermaid
timeline
    title Publication Timeline
    2001        : Schl01a
                : XMI/MOOSE Technical Report
    2002        : Schl03a
                : Diplomarbeit JPiccola
    2004 - 2006 : ICPR · IWFHR · DAS · ICDAR · IGS
                : Handwriting Recognition
                : Writer Identification
                : Document Analysis
    2026        : arXiv Preprints
                : LLM Agent Systems
                : Formal Verification
```

---

## ℹ️ About

This archive preserves research publications in:

- **Software composition grounded in the π-calculus** (agents, forms, channels)
- **Component-oriented programming and white-box/black-box reuse strategies**
- **XMI/XML metadata interchange, metamodeling, and the MOF meta-meta-model**
- **Machine learning for document analysis** (Gaussian Mixture Models, Hidden
  Markov Models, Support Vector Machines)
- **Handwriting recognition and analysis**
- **Writer identification and verification**
- **Document image analysis and pattern recognition**
- **LLM agent systems and tool protocols (SGD, MCP)**
- **Formal verification of agentic systems**
- **AI governance and schema-driven interoperability**
