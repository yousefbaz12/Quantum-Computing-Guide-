<div align="center">

<img src="https://img.shields.io/badge/⚛️-Quantum%20Computing%20%26%20QML-blueviolet?style=for-the-badge" />

# Quantum Computing & Quantum Machine Learning
### A Complete, Curated, and Structured Knowledge Repository

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2025-orange.svg?style=flat-square)](README.md)
[![Stars](https://img.shields.io/github/stars/yourusername/quantum-computing-qml?style=flat-square&color=yellow)](https://github.com/yourusername/quantum-computing-qml)

<br/>

> **For students · researchers · developers · educators**
>
> A living knowledge base guiding you from mathematical prerequisites
> to research-level mastery in Quantum Computing and Quantum Machine Learning.

<br/>

[📚 Books](#-books) · [📄 Papers](#-papers) · [🎬 Courses & Videos](#-courses--videos) · [🧪 Frameworks](#-frameworks--tools) · [🗺️ Roadmap](#️-full-learning-roadmap) · [✅ QML Checklist](#-quantum-machine-learning-complete-checklist)

</div>

---

## 📖 Table of Contents

<details>
<summary><strong>Click to expand full table of contents</strong></summary>

- [Introduction](#-introduction)
- [Who This Is For](#-who-this-is-for)
- [Repository Structure](#-repository-structure)
- [Badge & Rating System](#-badge--rating-system)
- [📚 Books](#-books)
  - [Mathematics for QC](#mathematics-for-quantum-computing)
  - [Quantum Mechanics](#quantum-mechanics-textbooks)
  - [Quantum Computing — Core](#quantum-computing--core-textbooks)
  - [Quantum Information Theory](#quantum-information-theory)
  - [Quantum Machine Learning](#quantum-machine-learning-books)
  - [Quantum Error Correction](#quantum-error-correction)
  - [Free Lecture Notes](#free-lecture-notes)
- [📄 Papers](#-papers)
  - [Foundational](#foundational-papers)
  - [Quantum Algorithms](#quantum-algorithms-papers)
  - [QML Surveys](#qml-survey-papers)
  - [Variational Algorithms](#variational-algorithm-papers)
  - [Quantum Neural Networks](#quantum-neural-network-papers)
  - [Quantum Kernels](#quantum-kernel-papers)
  - [Barren Plateaus](#barren-plateau-papers)
  - [Quantum Advantage](#quantum-advantage--dequantization-papers)
  - [Hardware & NISQ](#hardware--nisq-papers)
- [🎬 Courses & Videos](#-courses--videos)
  - [University Courses (Free)](#university-courses-free)
  - [Online Platforms](#online-platforms)
  - [YouTube Channels](#youtube-channels)
  - [Lecture Series](#lecture-series)
- [🧪 Frameworks & Tools](#-frameworks--tools)
  - [Programming Frameworks](#programming-frameworks)
  - [Simulators](#simulators)
  - [Cloud Platforms](#quantum-cloud-platforms)
  - [Utilities](#development-utilities)
- [🗺️ Full Learning Roadmap](#️-full-learning-roadmap)
- [✅ Quantum Machine Learning — Complete Checklist](#-quantum-machine-learning-complete-checklist)
  - [Phase 0: Prerequisites Checklist](#phase-0-prerequisites-checklist)
  - [Phase 1: QC Foundations Checklist](#phase-1-quantum-computing-foundations-checklist)
  - [Phase 2: QML Core Checklist](#phase-2-qml-core-concepts-checklist)
  - [Phase 3: Algorithms Checklist](#phase-3-qml-algorithms-checklist)
  - [Phase 4: Implementation Checklist](#phase-4-implementation--coding-checklist)
  - [Phase 5: Advanced Topics Checklist](#phase-5-advanced-qml-topics-checklist)
  - [Phase 6: Research Checklist](#phase-6-research-level-checklist)
- [Projects](#-projects)
- [Datasets](#-datasets)
- [Blogs & Community](#-blogs--community)
- [Glossary Reference](#-glossary-reference)
- [Contributing](#-contributing)
- [Citation](#-citation)
- [License & Disclaimer](#-license--disclaimer)

</details>

---

## 🌌 Introduction

Quantum Computing harnesses the principles of quantum mechanics — **superposition**, **entanglement**, and **interference** — to process information in ways that are fundamentally beyond classical machines.

**Quantum Machine Learning (QML)** is the frontier where quantum computing meets artificial intelligence. It asks: can quantum algorithms provide provable or practical advantages for learning from data? This field includes variational quantum circuits as learning models, quantum kernel methods, quantum-enhanced optimization, and near-term NISQ-era algorithms.

This repository is a **single curated source of truth** — systematically organized, academically rigorous, and beginner-accessible. Resources are separated by type (books, papers, courses, tools) and every section is self-contained so you can navigate directly to what you need.

---

## 👥 Who This Is For

| Audience | What You Will Find Here |
|:---|:---|
| 🟢 **Beginners** | Step-by-step roadmap, prerequisite mathematics, intuitive introductions |
| 🎓 **Students** | Lecture notes, textbooks, free university courses |
| 💻 **Developers** | Frameworks, code examples, hands-on projects |
| 🔬 **Researchers** | Curated papers, arXiv links, open problems, datasets |
| 🏫 **Educators** | Structured curricula, categorized resources, reusable checklists |

---

## 📁 Repository Structure

```
quantum-computing-qml-resources/
│
├── README.md              ← Master file: all resources + full roadmap + QML checklist
│
├── 📚 BOOKS.md            ← Expanded textbook listings with annotations
├── 📄 PAPERS.md           ← Full annotated paper collection by topic
├── 🎬 COURSES.md          ← Detailed course descriptions and syllabi notes
├── 🎬 YOUTUBE.md          ← Video lectures and channel guides
├── 🧪 FRAMEWORKS.md       ← Framework setup guides and code examples
├── 🛠️  TOOLS.md            ← Simulators, cloud platforms, utilities
├── 💡 PROJECTS.md         ← 22 projects from beginner to research level
├── 📊 DATASETS.md         ← Quantum datasets and benchmarks
├── 📝 BLOGS.md            ← Blogs, newsletters, community resources
├── 📖 GLOSSARY.md         ← 50+ defined terms
├── 🗺️  ROADMAP.md          ← Expanded stage-by-stage learning path
└── 🤝 CONTRIBUTING.md     ← Contribution guide and resource template
```

> **Tip:** This README is your primary navigation hub. Each section links to the detailed file for deeper content.

---

## 🏷️ Badge & Rating System

| Badge | Meaning |
|:---|:---|
| `🟢 Beginner` | Accessible with basic math and programming knowledge |
| `🟡 Intermediate` | Requires linear algebra and introductory QC background |
| `🔴 Advanced` | Graduate-level rigor and mathematical depth |
| `🔬 Research` | Active research frontier; requires strong prior knowledge |
| `🆓 Free` | Freely and legally accessible |
| `💲 Paid` | Requires purchase or subscription |
| `💻 Code` | Hands-on coding content included |
| `📐 Math` | Strong mathematical focus |
| `⭐ Essential` | Considered must-read/must-do for the field |

---

## 📚 Books

> Full annotations and additional titles in [`BOOKS.md`](BOOKS.md)

---

### Mathematics for Quantum Computing

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **Linear Algebra Done Right** | Sheldon Axler | 🟢🟡 | 🆓 online | Rigorous structure-first approach. Best theory foundation. |
| **Introduction to Linear Algebra** | Gilbert Strang (MIT) | 🟢 | 💲 print / 🆓 lectures | Applied focus. Accompanied by free MIT OCW videos. |
| **Mathematics for QM** | John D. Hanson | 🟡 | 🆓 PDF | Targeted exactly at QC math needs: Hilbert spaces, Dirac notation. |
| **Div, Grad, Curl and All That** | Schey | 🟢 | 💲 | Intuitive vector calculus for physics-track learners. |

---

### Quantum Mechanics Textbooks

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **QM: The Theoretical Minimum** ⭐ | Susskind & Friedman | 🟢 | 💲 | Best first QM book for CS/math readers. No physics assumed. |
| **Feynman Lectures Vol. III** ⭐ | Feynman | 🟡 | 🆓 online | Unmatched physical intuition. Free at feynmanlectures.caltech.edu |
| **Principles of Quantum Mechanics** | Shankar | 🔴 | 💲 | Graduate-level. Standard physics-track reference. |
| **Modern Quantum Mechanics** | Sakurai & Napolitano | 🔴 | 💲 | Rigorous. Spin-first approach. Graduate standard. |

---

### Quantum Computing — Core Textbooks

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **Quantum Computation and Quantum Information** ⭐ | Nielsen & Chuang | 🟡🔴 | 💲 | **The** definitive QC textbook. Every serious student must read this. |
| **Quantum Computing: An Applied Approach** ⭐ | Jack Hidary | 🟢🟡 | 💲 / 🆓 code | Best practical intro. Code in Qiskit and Cirq throughout. |
| **Quantum Computer Science** | N.D. Mermin | 🟡 | 💲 | Written for CS readers. Rigorous without requiring physics. |
| **Quantum Algorithms via Linear Algebra** | Lipton & Regan | 🟡 | 💲 | All algorithms as matrix operations. Elegant for mathematicians. |
| **Quantum Computing Since Democritus** ⭐ | Scott Aaronson | 🟢🟡 | 💲 | Intellectually rich. Connects QC to complexity, philosophy, physics. |

---

### Quantum Information Theory

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **Quantum Information Theory** ⭐ | Mark Wilde (LSU) | 🔴 | 🆓 arXiv | Most comprehensive free QIT textbook. Graduate depth. arXiv:1106.1445 |
| **Quantum Theory of Information** | Barnett | 🟡🔴 | 💲 | Accessible QIT with physical motivation. |

---

### Quantum Machine Learning Books

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **Machine Learning with Quantum Computers** ⭐ | Schuld & Petruccione | 🟡🔴 | 💲 / 🆓 earlier ed. | **The** QML textbook. Written by researcher who derived parameter-shift rule. |
| **Supervised Learning with Quantum Computers** | Schuld & Petruccione | 🟢🟡 | 🆓 arXiv:1409.3097 | Earlier accessible version. Good starting point. |
| **Quantum Deep Learning** | Ganguly | 🟡 | 💲 | Practical focus on hybrid quantum-classical deep learning. |

---

### Quantum Error Correction

| Title | Author | Level | Access | Notes |
|:---|:---|:---:|:---:|:---|
| **Quantum Error Correction** | Lidar & Brun (eds.) | 🔴 | 💲 | Comprehensive reference. Stabilizer codes, surface codes, fault tolerance. |
| **An Introduction to QEC** | Devitt et al. | 🔴 | 🆓 arXiv:0905.2794 | Free survey. Good overview before the full textbook. |

---

### Free Lecture Notes

| Title | Author / Institution | Level | Link |
|:---|:---|:---:|:---|
| **Quantum Information Lecture Notes** ⭐ | John Preskill / Caltech | 🔴 | theory.caltech.edu/~preskill/ph229 |
| **MIT 8.370 / 18.435 QC Notes** | Shor, Chuang / MIT | 🔴 | ocw.mit.edu |
| **QC Lecture Notes** | Ronald de Wolf / CWI | 🟡🔴 | arXiv:1907.09415 |
| **PHYS 771 QC Theory** | Scott Aaronson / UT Austin | 🔴 | scottaaronson.blog |
| **Quantum Computing Notes** | John Watrous / Waterloo | 🔴 | cs.uwaterloo.ca/~watrous |

---

## 📄 Papers

> Full annotations, abstracts, and additional papers in [`PAPERS.md`](PAPERS.md)

---

### Foundational Papers

| Title | Authors | Year | Link | Why Read |
|:---|:---|:---:|:---|:---|
| **Simulating Physics with Computers** ⭐ | Feynman | 1982 | Springer | The original motivation for quantum computing. |
| **Universal Quantum Computer** ⭐ | Deutsch | 1985 | Royal Society | First formal quantum circuit model. |
| **Polynomial-Time Factorization** ⭐ | Shor | 1994 | arXiv:quant-ph/9508027 | Exponential speedup. Placed QC on the map. |
| **Quantum Database Search** ⭐ | Grover | 1996 | arXiv:quant-ph/9605043 | Quadratic speedup for search. Amplitude amplification. |
| **Quantum Teleportation** | Bennett et al. | 1993 | PRL | Foundational quantum communication protocol. |
| **No-Cloning Theorem** | Wootters & Zurek | 1982 | Nature | Fundamental limit on quantum information copying. |

---

### Quantum Algorithms Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **HHL: Linear Systems** | Harrow, Hassidim, Lloyd | 2009 | arXiv:0811.3171 | 🔴 |
| **Quantum PCA** | Lloyd, Mohseni, Rebentrost | 2014 | arXiv:1307.0401 | 🔴 |
| **BQP vs PH Separation** | Raz & Tal | 2019 | ECCC | 🔬 |
| **Quantum Walks** | Ambainis | 2003 | arXiv:quant-ph/0310064 | 🔴 |

---

### QML Survey Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Quantum Machine Learning** ⭐ | Biamonte et al. | 2017 | Nature 549 / arXiv:1611.09347 | 🟡 |
| **Introduction to QML** | Schuld, Sinayskiy, Petruccione | 2015 | arXiv:1409.3097 | 🟢🟡 |
| **Quantum Models as Kernel Methods** ⭐ | Schuld | 2021 | arXiv:2101.11020 | 🔴 |
| **QML: What Quantum Advantage?** | Dunjko & Briegel | 2018 | arXiv:1709.02779 | 🟡🔴 |

---

### Variational Algorithm Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Variational Quantum Algorithms** ⭐ | Cerezo et al. | 2021 | Nature Rev. Physics / arXiv:2012.09265 | 🟡🔴 |
| **VQE: Original Paper** ⭐ | Peruzzo et al. | 2014 | arXiv:1304.3061 | 🔴 |
| **QAOA: Original Paper** ⭐ | Farhi, Goldstone, Gutmann | 2014 | arXiv:1411.4028 | 🔴 |
| **QAOA Performance Analysis** | Bravyi et al. | 2020 | arXiv:2009.10095 | 🔬 |
| **VQE vs Classical Solvers** | Wecker et al. | 2015 | arXiv:1506.05135 | 🔴 |

---

### Quantum Neural Network Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Circuit Learning (Parameter-Shift)** ⭐ | Mitarai et al. | 2018 | arXiv:1803.00745 | 🟡 |
| **Analytic Gradients on Hardware** ⭐ | Schuld et al. | 2019 | arXiv:1811.11184 | 🟡 |
| **Power of QNNs** | Abbas et al. | 2021 | arXiv:2011.00027 | 🔴 |
| **Quantum Transfer Learning** | Mari et al. | 2020 | arXiv:1912.08278 | 🟡🔴 |
| **Expressibility and Entangling Capability** ⭐ | Sim et al. | 2019 | arXiv:1905.10876 | 🔴 |
| **Data Re-uploading** | Pérez-Salinas et al. | 2020 | arXiv:1907.02085 | 🟡 |

---

### Quantum Kernel Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Quantum Kernel Estimation** ⭐ | Havlíček et al. (IBM) | 2019 | Nature 567 / arXiv:1804.11326 | 🔴 |
| **QML Models are Kernel Methods** ⭐ | Schuld | 2021 | arXiv:2101.11020 | 🔴 |
| **Quantum Kernels for ML** | Blank et al. | 2020 | arXiv:2003.01862 | 🔴 |
| **Projected QKE** | Huang et al. | 2021 | arXiv:2107.10442 | 🔬 |

---

### Barren Plateau Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Barren Plateaus in QNNs** ⭐ | McClean et al. (Google) | 2018 | Nature Comm. / arXiv:1803.11173 | 🔴 |
| **Cost-Dependent Barren Plateaus** | Cerezo et al. | 2021 | arXiv:2001.00550 | 🔴 |
| **Noise-Induced Barren Plateaus** | Wang et al. | 2021 | arXiv:2007.14384 | 🔬 |
| **Avoiding Barren Plateaus** | Grant et al. | 2019 | arXiv:1903.05076 | 🔴 |
| **Entanglement-Induced BP** | Marrero et al. | 2021 | arXiv:2010.15968 | 🔬 |

---

### Quantum Advantage & Dequantization Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **Quantum Supremacy (Google)** | Arute et al. | 2019 | Nature 574 / arXiv:1910.11333 | 🔴 |
| **Quantum Advantage: Shallow Circuits** ⭐ | Bravyi, Gosset, König | 2018 | arXiv:1704.00690 | 🔴 |
| **Dequantizing Recommendation Systems** ⭐ | Tang | 2018 | arXiv:1807.04271 | 🔴 |
| **Dequantizing QSVT** | Chia et al. | 2020 | arXiv:1911.00035 | 🔬 |

---

### Hardware & NISQ Papers

| Title | Authors | Year | Link | Level |
|:---|:---|:---:|:---|:---:|
| **NISQ Era and Beyond** ⭐ | Preskill | 2018 | Quantum 2,79 / arXiv:1801.00862 | 🟡 |
| **Error Mitigation for NISQ** | Li & Benjamin | 2017 | arXiv:1611.09301 | 🔴 |
| **Zero-Noise Extrapolation** | Temme et al. | 2017 | arXiv:1612.02058 | 🔴 |
| **Quantum Volume** | Cross et al. (IBM) | 2019 | arXiv:1811.12926 | 🟡🔴 |

---

## 🎬 Courses & Videos

> Full course descriptions, syllabi notes, and additional resources in [`COURSES.md`](COURSES.md) and [`YOUTUBE.md`](YOUTUBE.md)

---

### University Courses (Free)

| Course | Institution | Instructor | Level | Link |
|:---|:---|:---|:---:|:---|
| **MIT 8.370 / 18.435 QC** ⭐ | MIT OCW | Shor, Chuang | 🔴 | ocw.mit.edu |
| **CS 269Q** | Stanford | Various | 🔴 | cs269q.stanford.edu |
| **PHYS 771 QC Theory** | UT Austin | Aaronson | 🔴 | scottaaronson.blog |
| **CS 191 QC** | UC Berkeley | Vazirani | 🔴 | inst.eecs.berkeley.edu/~cs191 |
| **Quantum Information Sci I & II** | MIT via edX | — | 🔴 | edx.org |

---

### Online Platforms

| Course | Provider | Level | Access | Highlight |
|:---|:---|:---:|:---:|:---|
| **IBM Quantum Learning** ⭐ | IBM | 🟢→🔴 | 🆓 | Best free platform. Real hardware access. |
| **PennyLane Codebook** ⭐ | Xanadu | 🟢🟡 | 🆓 | Interactive coding exercises. Best for QML. |
| **PennyLane QML Demos** ⭐ | Xanadu | 🟡🔴 | 🆓 | Research-grade tutorials with notebooks. |
| **Xanadu Quantum Codebook** | Xanadu | 🟢🟡 | 🆓 | Interactive code-based beginner learning. |
| **QML — University of Toronto** | edX / Coursera | 🟡🔴 | 🆓 audit | Structured academic QML course. |
| **Quantum Katas** ⭐ | Microsoft | 🟢🟡 | 🆓 | Excellent interactive exercises. quantum.microsoft.com |
| **QC for CS — Brilliant.org** | Brilliant | 🟢 | 💲 | Highly visual. Great for intuition building. |

---

### YouTube Channels

| Channel | Focus | Level | Why Watch |
|:---|:---|:---:|:---|
| **3Blue1Brown** ⭐ | Linear algebra, calculus | 🟢 | Best visual math intuition. Start here for prerequisites. |
| **Qiskit Channel** ⭐ | QC + QML | 🟢→🔴 | IBM's official channel. Includes Watrous lecture series. |
| **Quantum Sense** ⭐ | QM intuition | 🟢🟡 | Best channel for bra-ket notation and QM fundamentals. |
| **PennyLane AI** | QML research | 🟡🔴 | Research-grade QML tutorials from Xanadu team. |
| **QuTech Academy** | QC + hardware | 🟢🟡 | Well-produced. Strong on hardware concepts. |
| **PBS Space Time** | QM overview | 🟢 | High-quality popular science. Motivation and big picture. |
| **Simons Institute** | Research talks | 🔴🔬 | In-depth workshops by leading researchers. |
| **Perimeter Institute** | QM + QI | 🟢🟡 | Accessible public lectures from world-class researchers. |

---

### Lecture Series

| Series | Instructor | Level | Platform |
|:---|:---|:---:|:---|
| **Understanding QI and Computation** ⭐ | John Watrous | 🟡🔴 | YouTube (via Qiskit) |
| **Quantum Computation Lectures** | John Preskill | 🔴 | YouTube (Caltech) |
| **QC — Berkeley CS 191** | Umesh Vazirani | 🔴 | YouTube |
| **Essence of Linear Algebra** ⭐ | 3Blue1Brown | 🟢 | YouTube |
| **MIT 18.06 Linear Algebra** | Gilbert Strang | 🟢🟡 | YouTube / MIT OCW |
| **QC for CS — Microsoft Research** | Microsoft | 🟢🟡 | YouTube (1.5h, single lecture) |

---

## 🧪 Frameworks & Tools

> Full setup guides, code examples, and comparisons in [`FRAMEWORKS.md`](FRAMEWORKS.md) and [`TOOLS.md`](TOOLS.md)

---

### Programming Frameworks

| Framework | By | Best For | Differentiable | Hardware |
|:---|:---|:---|:---:|:---|
| **Qiskit** ⭐ | IBM | General QC, algorithms, real hardware | Partial | IBM Quantum (free) |
| **PennyLane** ⭐ | Xanadu | QML, gradients, hybrid models | ✅ Full | Multiple backends |
| **Cirq** | Google | NISQ research, low-level control | Partial | Google hardware |
| **TensorFlow Quantum** | Google | Hybrid QML + Keras | ✅ Full | Google (via Cirq) |
| **Amazon Braket** | AWS | Multi-provider cloud access | No | IonQ, Rigetti, OQC |
| **Q# + Azure Quantum** | Microsoft | Fault-tolerant algorithms | No | IonQ, Quantinuum |
| **Strawberry Fields** | Xanadu | Photonic / continuous-variable QC | ✅ Full | Xanadu photonic |

**QML Beginner Recommendation → Start with PennyLane**
**General QC Beginner Recommendation → Start with Qiskit**

---

### Simulators

| Tool | Type | Level | Notes |
|:---|:---|:---:|:---|
| **Quirk** ⭐ | Browser-based visual | 🟢 | algassert.com/quirk — no install, drag-and-drop |
| **IBM Quantum Composer** | Web visual + run | 🟢🟡 | Official IBM. Visual builder + real hardware. |
| **Qiskit Aer** | Python (statevector, MPS) | 🟡 | Noise models. High performance. |
| **PennyLane default.qubit** | Python (differentiable) | 🟡 | Fully differentiable. Ideal for QML. |
| **QuTiP** | Open quantum systems | 🔴 | Lindblad master equations, decoherence. |
| **Qulacs** | High-performance C++ | 🟡🔴 | Fastest CPU-based statevector simulator. |

---

### Quantum Cloud Platforms

| Platform | Hardware | Free Tier | Access |
|:---|:---|:---:|:---|
| **IBM Quantum** ⭐ | Superconducting (127–1000+ qubits) | ✅ Yes | quantum.ibm.com |
| **Amazon Braket** | IonQ, Rigetti, OQC, simulators | Partial | aws.amazon.com/braket |
| **Azure Quantum** | IonQ, Quantinuum | 💲 Pay-per-use | azure.microsoft.com/quantum |
| **Google Quantum AI** | Sycamore (70 qubits) | Research only | quantumai.google |
| **Quantinuum** | Trapped ion (highest fidelity) | No | quantinuum.com |

---

### Development Utilities

| Tool | Purpose | Level |
|:---|:---|:---:|
| **Mitiq** ⭐ | Error mitigation (ZNE, PEC) | 🟡🔴 |
| **OpenQASM** | Quantum circuit interchange format | 🟡 |
| **Toqito** | Quantum information theory (Python) | 🔴 |
| **NetKet** | Neural quantum states (JAX) | 🔴🔬 |
| **QASMbench** | Circuit benchmarking suite | 🟡🔴 |

---

---

## 🗺️ Full Learning Roadmap

> **Estimated total:** 12–24 months for full mastery (self-paced). Each stage builds on the previous.
> For full details including practice tasks and project suggestions per stage, see [`ROADMAP.md`](ROADMAP.md).

```
╔══════════════════════════════════════════════════════════════════════════╗
║              QUANTUM COMPUTING & QML — COMPLETE LEARNING PATH           ║
╠══════════════════════════════════════════════════════════════════════════╣
║                                                                          ║
║  STAGE 0 ─── Mathematical Prerequisites ──────────────── (4–8 weeks)    ║
║              │ Linear algebra · Complex numbers                          ║
║              │ Probability · Calculus basics                             ║
║              │ Tensor products · Eigendecomposition                      ║
║              ▼                                                           ║
║  STAGE 1 ─── Classical Computing Foundations ─────────── (1–2 weeks)    ║
║              │ Bits & logic gates · Boolean circuits                     ║
║              │ Complexity: P, NP, BPP, BQP                               ║
║              │ Reversible computation                                     ║
║              ▼                                                           ║
║  STAGE 2 ─── Quantum Mechanics Basics ────────────────── (3–6 weeks)    ║
║              │ Dirac notation |ψ⟩ · Superposition                        ║
║              │ Measurement & Born rule · Entanglement                    ║
║              │ No-cloning theorem · Unitary evolution                    ║
║              ▼                                                           ║
║  STAGE 3 ─── Quantum Information & Qubits ────────────── (2–4 weeks)    ║
║              │ Bloch sphere · Density matrices                           ║
║              │ Quantum channels · von Neumann entropy                    ║
║              │ Teleportation · Superdense coding                         ║
║              ▼                                                           ║
║  STAGE 4 ─── Quantum Gates & Circuits ────────────────── (2–4 weeks)    ║
║              │ Single-qubit gates: H, X, Y, Z, S, T, Rx, Ry, Rz         ║
║              │ Two-qubit gates: CNOT, CZ, SWAP, Toffoli                  ║
║              │ Universality · Circuit identities · NISQ constraints      ║
║              ▼                                                           ║
║  STAGE 5 ─── Quantum Algorithms ──────────────────────── (4–8 weeks)    ║
║              │ Deutsch–Jozsa · Bernstein–Vazirani · Simon's              ║
║              │ QFT · Phase Estimation · Grover's Search                  ║
║              │ Shor's Factoring · HHL (linear systems)                   ║
║              ▼                                                           ║
║  STAGE 6 ─── Quantum Programming ─────────────────────── (2–4 weeks)    ║
║              │ Qiskit: circuits, transpile, run on hardware              ║
║              │ PennyLane: QNodes, parameter-shift, autograd              ║
║              │ Noise models · Error mitigation (ZNE, SPAM)               ║
║              ▼                                                           ║
║  STAGE 7 ─── QML Foundations ─────────────────────────── (4–8 weeks)    ║
║              │ Data encoding strategies · Hybrid architectures           ║
║              │ Variational circuits · Quantum gradients                  ║
║              │ Quantum kernels · NISQ ML constraints                     ║
║              ▼                                                           ║
║  STAGE 8 ─── Advanced QML ────────────────────────────── (6–12 weeks)   ║
║              │ VQE · QAOA · QNNs · QGANs                                 ║
║              │ Barren plateaus · Expressibility analysis                 ║
║              │ Dequantization results · Provable advantages              ║
║              ▼                                                           ║
║  STAGE 9 ─── Research Papers & Open Problems ─────────── (Ongoing)      ║
║              │ Active literature (arXiv quant-ph daily)                  ║
║              │ Open problems: BP mitigation, QML advantage               ║
║              │ QIP / TQC conference proceedings                          ║
║              ▼                                                           ║
║  STAGE 10 ── Projects & Contributions ────────────────── (Ongoing)      ║
║              │ End-to-end implementations                                ║
║              │ Paper reproductions                                       ║
║              │ Open-source contributions                                 ║
╚══════════════════════════════════════════════════════════════════════════╝
```

### Stage-by-Stage Resource Map

| Stage | Primary Book | Primary Course | Primary Framework |
|:---|:---|:---|:---|
| 0 — Math | Axler / Strang | 3B1B · MIT 18.06 | NumPy |
| 1 — Classical | Sipser / Aaronson | — | Python |
| 2 — QM | Susskind & Friedman | Quantum Sense (YT) | — |
| 3 — QI | Nielsen & Chuang Ch.1–2 | Watrous lecture series | — |
| 4 — Gates | Nielsen & Chuang Ch.4 | IBM Quantum Learning | Qiskit |
| 5 — Algorithms | Nielsen & Chuang Ch.5–6 | MIT 8.370 | Qiskit |
| 6 — Programming | Hidary / Qiskit docs | IBM Quantum Learning | Qiskit + PennyLane |
| 7 — QML Foundations | Schuld & Petruccione | PennyLane Codebook | PennyLane |
| 8 — Advanced QML | Cerezo et al. (review) | PennyLane Demos | PennyLane + PyTorch |
| 9 — Research | arXiv quant-ph | QIP proceedings | — |
| 10 — Projects | PROJECTS.md | — | Qiskit / PennyLane |

---

---

## ✅ Quantum Machine Learning — Complete Checklist

> Use this checklist to systematically track your QML mastery.
> Check off items as you complete them. Each item is a distinct, testable concept or skill.

---

### Phase 0: Prerequisites Checklist

**Linear Algebra**
- [ ] Vectors, vector spaces, basis, span, linear independence
- [ ] Matrix multiplication, transpose, inverse
- [ ] Inner products and norms: ⟨u,v⟩ = u†v
- [ ] Outer products: |u⟩⟨v| (rank-1 matrices)
- [ ] Eigenvalues and eigenvectors: Av = λv
- [ ] Hermitian matrices: A = A†, real eigenvalues
- [ ] Unitary matrices: UU† = I, eigenvalues on unit circle
- [ ] Spectral decomposition: A = Σ λᵢ |eᵢ⟩⟨eᵢ|
- [ ] Tensor (Kronecker) product: A ⊗ B
- [ ] Partial trace: Tr_B(ρ_AB)
- [ ] Singular value decomposition (SVD)

**Complex Numbers**
- [ ] Complex number algebra: modulus, argument, conjugate
- [ ] Euler's formula: e^(iθ) = cos θ + i sin θ
- [ ] Complex inner product spaces

**Probability & Statistics**
- [ ] Probability distributions, expected value, variance
- [ ] Conditional probability, Bayes' theorem
- [ ] Random variables and sampling

**Calculus & Optimization**
- [ ] Derivatives and gradients
- [ ] Chain rule (for backpropagation analogy)
- [ ] Gradient descent: θ ← θ − α∇L
- [ ] Convex vs. non-convex optimization landscapes

**Classical ML Prerequisites**
- [ ] Supervised learning: classification and regression
- [ ] Loss functions: MSE, cross-entropy
- [ ] Overfitting, regularization, train/test split
- [ ] Neural networks: forward pass, backpropagation
- [ ] Kernel methods: SVM, kernel trick, RBF kernel

---

### Phase 1: Quantum Computing Foundations Checklist

**Qubits and Quantum States**
- [ ] Classical bit vs qubit: |0⟩ and |1⟩ as computational basis
- [ ] Superposition: |ψ⟩ = α|0⟩ + β|1⟩ with |α|² + |β|² = 1
- [ ] Bloch sphere: parametrize |ψ⟩ = cos(θ/2)|0⟩ + e^(iφ)sin(θ/2)|1⟩
- [ ] Multi-qubit systems: tensor product |00⟩, |01⟩, |10⟩, |11⟩
- [ ] n-qubit state space: 2ⁿ-dimensional complex Hilbert space
- [ ] Global phase vs. relative phase (only relative phase is observable)

**Measurement**
- [ ] Born rule: P(outcome k) = |⟨k|ψ⟩|² = |amplitude|²
- [ ] State collapse after measurement
- [ ] Expectation value: ⟨O⟩ = ⟨ψ|O|ψ⟩
- [ ] Projective measurement vs. POVM (conceptual distinction)
- [ ] Measurement in different bases (Z, X, Y basis)

**Entanglement**
- [ ] Separable states: |ψ⟩_AB = |ψ⟩_A ⊗ |ψ⟩_B
- [ ] Entangled states: not separable
- [ ] Bell states: Φ⁺, Φ⁻, Ψ⁺, Ψ⁻
- [ ] EPR paradox (conceptual understanding)
- [ ] No-signaling theorem

**Quantum Gates**
- [ ] Pauli gates: X (NOT), Y, Z (phase flip)
- [ ] Hadamard gate H: creates superposition
- [ ] Phase gates S = R_z(π/2), T = R_z(π/4)
- [ ] Rotation gates: Rx(θ), Ry(θ), Rz(θ)
- [ ] Two-qubit gates: CNOT, CZ, SWAP
- [ ] Toffoli gate (CCNOT): universal for classical computation
- [ ] Universality: {H, T, CNOT} is universal for quantum computation
- [ ] Gate decomposition: Euler angles Rz·Ry·Rz

**Quantum Circuits**
- [ ] Circuit diagrams: wire = qubit, box = gate, meter = measurement
- [ ] Sequential gates: left-to-right time ordering
- [ ] Circuit depth and width
- [ ] CNOT creates Bell state: H⊗I then CNOT on |00⟩
- [ ] Quantum teleportation circuit

**Density Matrices**
- [ ] Pure state: ρ = |ψ⟩⟨ψ|, Tr(ρ²) = 1
- [ ] Mixed state: ρ = Σ pᵢ |ψᵢ⟩⟨ψᵢ|, Tr(ρ²) < 1
- [ ] Reduced density matrix via partial trace
- [ ] von Neumann entropy: S(ρ) = −Tr(ρ log ρ)
- [ ] Fidelity: F(ρ,σ) = (Tr√(√ρ σ √ρ))²

---

### Phase 2: QML Core Concepts Checklist

**What is QML?**
- [ ] The three types of QML: QC+CC, QC+QD, QQ (quantum data)
- [ ] NISQ era constraints and what they mean for QML
- [ ] Why classical ML + quantum computing ≠ automatic speedup
- [ ] The quantum model zoo: VQC, QKE, QNN, QGAN

**Data Encoding (Feature Maps)**
- [ ] Why encoding matters: defines the hypothesis space
- [ ] Basis encoding: classical bit string → computational basis state
- [ ] Amplitude encoding: N data points → log₂(N) qubits (exponential compression)
- [ ] Angle encoding: data xᵢ → rotation angle in Rx(xᵢ) or Ry(xᵢ)
- [ ] IQP-style encoding (Havlíček feature map)
- [ ] Data re-uploading: encode data multiple times to increase expressivity
- [ ] Trade-offs: amplitude encoding is compact but hard to load; angle encoding is easy but redundant

**Parameterized Quantum Circuits (PQC)**
- [ ] PQC as a function: f(x; θ) = ⟨ψ(x,θ)|O|ψ(x,θ)⟩
- [ ] Ansatz design: hardware-efficient vs. strongly entangling layers
- [ ] Entanglement layers and their role in expressibility
- [ ] Circuit depth vs. trainability trade-off
- [ ] CNOT connectivity constraints on real hardware

**Quantum Gradients**
- [ ] Parameter-shift rule: ∂f/∂θ = [f(θ+π/2) − f(θ−π/2)] / 2
- [ ] Why parameter-shift works: eigenvalue structure of generators
- [ ] Finite-difference approximation (comparison and drawbacks)
- [ ] Natural gradient in quantum models
- [ ] Computing gradients on hardware vs. simulator

**Training Loop**
- [ ] Define cost/loss function: expectation value of observable
- [ ] Initialize parameters (random initialization, SPSA, identity blocks)
- [ ] Forward pass: run circuit, measure, compute expectation
- [ ] Backward pass: compute gradient via parameter-shift
- [ ] Update parameters: Adam, gradient descent, COBYLA, SPSA
- [ ] Validation: overfitting in QML (models often too small to overfit)

---

### Phase 3: QML Algorithms Checklist

**Variational Quantum Eigensolver (VQE)**
- [ ] Problem: find ground state energy of Hamiltonian H
- [ ] Variational principle: E(θ) = ⟨ψ(θ)|H|ψ(θ)⟩ ≥ E₀
- [ ] Jordan-Wigner / Bravyi-Kitaev transform: fermions to qubits
- [ ] Ansatz choice: UCCSD (chemistry), hardware-efficient
- [ ] Measurement strategy: Pauli decomposition of H
- [ ] Classical optimizer: COBYLA, BFGS, gradient-free options
- [ ] VQE for H₂: 2-qubit model, optimal bond distance
- [ ] Noise effect on VQE and mitigation strategies
- [ ] When VQE fails: barren plateaus, shot noise, hardware errors

**QAOA (Quantum Approximate Optimization Algorithm)**
- [ ] Problem formulation: combinatorial optimization as Ising Hamiltonian
- [ ] QAOA circuit: alternating problem unitary U_C and mixer U_B
- [ ] Parameters: γ (problem) and β (mixer) angles
- [ ] QAOA depth p: more layers → better approximation
- [ ] Max-Cut mapping: graph problem → Pauli Z Hamiltonian
- [ ] Approximation ratio at p=1 for Max-Cut: ≥ 0.6924 (proven)
- [ ] Classical optimization of γ, β angles (outer loop)
- [ ] QAOA vs. classical algorithms (no proven advantage for general problems)

**Variational Quantum Classifier (VQC)**
- [ ] Architecture: encoding layer → variational layers → measurement
- [ ] Binary classification: measure ⟨Z⟩, apply threshold
- [ ] Multi-class: multiple measurements or one-hot encoding
- [ ] Training on toy datasets (XOR, moons, circles)
- [ ] Comparison with classical SVM and neural network baselines
- [ ] Generalization bounds in QML

**Quantum Kernel Methods (QKE / QSVM)**
- [ ] Kernel function: K(x,y) = |⟨ψ(x)|ψ(y)⟩|²
- [ ] Kernel matrix computation: O(N²) circuit evaluations
- [ ] Classical SVM with quantum kernel (sklearn interface)
- [ ] Inductive bias of quantum kernels
- [ ] When quantum kernels help: quantum data, non-classical patterns
- [ ] Geometric difference and quantum kernel advantage conditions (Huang et al.)
- [ ] Relationship: all PQC models = kernel methods (Schuld 2021)

**Quantum Neural Networks (QNN)**
- [ ] Definition: PQC with layered structure analogous to neural net
- [ ] Quantum perceptron (conceptual)
- [ ] Effective dimension: analogue of VC-dimension for QNNs
- [ ] Quantum neural tangent kernel (QNTK)
- [ ] Overparameterization in QNNs: local minima avoidance
- [ ] Comparison with classical NNs: expressibility, trainability, generalization

**Quantum Generative Models**
- [ ] Quantum GAN (QGAN): quantum generator + classical discriminator
- [ ] Born machine: quantum circuit as probability distribution
- [ ] Quantum Boltzmann machine (conceptual)
- [ ] Training challenges for quantum generative models

**Quantum Transfer Learning**
- [ ] Classical pretrained network as feature extractor
- [ ] PQC as the classification head
- [ ] Fine-tuning only the quantum parameters
- [ ] Demonstrated on small image classification tasks

---

### Phase 4: Implementation & Coding Checklist

**PennyLane Fundamentals**
- [ ] Install PennyLane: `pip install pennylane`
- [ ] Create a device: `qml.device("default.qubit", wires=n)`
- [ ] Define a QNode: `@qml.qnode(dev)` decorator
- [ ] Apply gates: `qml.RX(theta, wires=0)`, `qml.CNOT(wires=[0,1])`
- [ ] Return expectation values: `return qml.expval(qml.PauliZ(0))`
- [ ] Compute gradients: `qml.grad(circuit)(params)`
- [ ] Use parameter-shift rule explicitly
- [ ] Integrate with NumPy autograd for optimization
- [ ] Integrate with PyTorch: `qml.qnn.TorchLayer`
- [ ] Integrate with TensorFlow: `qml.qnn.KerasLayer`
- [ ] Run on Qiskit/IBM hardware via `qml.device("qiskit.ibmq", ...)`

**Qiskit for QML**
- [ ] Build a parameterized circuit with `ParameterVector`
- [ ] Use `qiskit.circuit.library.ZZFeatureMap` (Havlíček encoding)
- [ ] Use `qiskit.circuit.library.RealAmplitudes` (variational ansatz)
- [ ] Compute expectation values with `Estimator` primitive
- [ ] Use `qiskit_machine_learning.algorithms.VQC`
- [ ] Use `qiskit_machine_learning.kernels.FidelityQuantumKernel`
- [ ] Combine with scikit-learn: `SVC(kernel=quantum_kernel.evaluate)`
- [ ] Run on real IBM hardware via `QiskitRuntimeService`

**Complete QML Pipeline (Hands-On)**
- [ ] Implement: VQC binary classifier on the Iris dataset (2-class)
- [ ] Implement: quantum kernel SVM on moons dataset
- [ ] Implement: VQE for H₂ ground state with PennyLane
- [ ] Implement: QAOA for Max-Cut on a 4-node graph
- [ ] Implement: hybrid quantum-classical image classifier (MNIST subset)
- [ ] Implement: data re-uploading classifier
- [ ] Implement: gradient variance analysis (barren plateau experiment)
- [ ] Implement: noise-mitigation (ZNE) on a simple circuit using Mitiq

---

### Phase 5: Advanced QML Topics Checklist

**Barren Plateaus — Deep Understanding**
- [ ] Formal definition: Var[∂L/∂θ] ∈ O(1/2ⁿ) for random circuits
- [ ] Cause 1: random initialization in high-dimensional spaces
- [ ] Cause 2: global cost functions (measuring all qubits)
- [ ] Cause 3: hardware noise (noise-induced BPs)
- [ ] Cause 4: excessive entanglement (entanglement-induced BPs)
- [ ] Mitigation 1: local cost functions (Cerezo et al. 2021)
- [ ] Mitigation 2: identity block initialization (Grant et al. 2019)
- [ ] Mitigation 3: layer-by-layer training
- [ ] Mitigation 4: structured / problem-informed ansätze
- [ ] Can reproduce BP phenomenon empirically: gradient variance vs. n

**Expressibility and Entanglement Capacity**
- [ ] Expressibility: how uniformly a PQC covers the Hilbert space
- [ ] Measure: KL divergence from Haar-random distribution (Sim et al.)
- [ ] Entanglement capability: average entanglement produced by circuit
- [ ] Trade-off: highly expressive circuits often have barren plateaus
- [ ] Hardware-efficient ansatz vs. chemically inspired (UCCSD)

**Error Mitigation (NISQ-era)**
- [ ] Zero-Noise Extrapolation (ZNE): run at multiple noise levels, extrapolate to 0
- [ ] Probabilistic Error Cancellation (PEC): quasi-probability decomposition
- [ ] Symmetry verification: post-select on known symmetries
- [ ] SPAM error correction: calibration matrices
- [ ] Clifford data regression (CDR)
- [ ] Mitiq library: implementing ZNE in 5 lines of code

**Quantum Advantage Theory**
- [ ] BPP vs. BQP: quantum computers likely can't solve all NP problems
- [ ] Query complexity separations: Grover, Simon, Bravyi-Gosset-König
- [ ] Dequantization (Tang 2018): many early QML speedups were not genuine
- [ ] When quantum advantage may hold: quantum data, quantum-generated distributions
- [ ] Current consensus: no proven practical QML advantage on classical data (as of 2025)
- [ ] Overhead problem: QRAM loading cost often negates claimed speedups

**Quantum-Classical Hybrid Architectures**
- [ ] Variational hybrid: quantum circuit + classical optimizer
- [ ] Quantum embedding in classical neural network (as a layer)
- [ ] Data parallelism: batching circuit evaluations
- [ ] Shot noise: statistical error from finite measurements
- [ ] Practical limits: shot budget, circuit depth, connectivity

---

### Phase 6: Research Level Checklist

**Literature Navigation**
- [ ] Navigate arXiv quant-ph: filter by cs.LG, quant-ph, cs.ET
- [ ] Use Semantic Scholar / Google Scholar for citation analysis
- [ ] Read a paper in 3 passes: abstract→figures→full
- [ ] Identify: what problem is solved, what is the claim, what is the evidence?
- [ ] Reproduce a main experiment from a published paper

**Current Open Problems (2024–2025)**
- [ ] Provable quantum advantage for ML on classical data: unresolved
- [ ] Practical barren plateau avoidance at scale: active research
- [ ] Noise-resilient QML: how much mitigation is enough?
- [ ] Optimal data encoding: what feature map gives genuine advantage?
- [ ] QML on quantum data: the most promising near-term path
- [ ] Fault-tolerant QML: what changes with logical qubits?
- [ ] Quantum generalization theory: rigorous sample complexity bounds

**Research Contributions**
- [ ] Identified a gap in the literature worth addressing
- [ ] Implemented a baseline from an existing paper
- [ ] Written a reproducibility report for a QML paper
- [ ] Contributed a bug fix, tutorial, or new feature to Qiskit or PennyLane
- [ ] Submitted to arXiv (preprint) or a workshop/conference

---

## 💡 Projects

> Full project descriptions with implementation guides in [`PROJECTS.md`](PROJECTS.md)

| # | Project | Level | Framework |
|:---:|:---|:---:|:---|
| 1 | Quantum state Bloch sphere visualizer | 🟢 | Qiskit |
| 2 | Quantum random number generator + statistical tests | 🟢 | Qiskit |
| 3 | Quantum teleportation protocol | 🟢 | Qiskit |
| 4 | Deutsch-Jozsa and Bernstein-Vazirani algorithms | 🟢 | Qiskit |
| 5 | Grover's search: 2, 3, 4 qubit databases | 🟡 | Qiskit |
| 6 | Quantum Fourier Transform from scratch | 🟡 | Qiskit |
| 7 | Quantum Phase Estimation | 🟡 | Qiskit |
| 8 | VQC binary classifier on toy dataset | 🟡 | PennyLane |
| 9 | Quantum kernel SVM on Iris / moons | 🟡 | PennyLane + sklearn |
| 10 | QAOA for Max-Cut (4–6 nodes) | 🟡 | PennyLane or Qiskit |
| 11 | Noise analysis + ZNE error mitigation | 🟡 | Qiskit + Mitiq |
| 12 | Shor's algorithm for N=15, 21, 35 | 🔴 | Qiskit |
| 13 | VQE for H₂ ground state energy | 🔴 | PennyLane |
| 14 | Hybrid quantum-classical image classifier | 🔴 | PennyLane + PyTorch |
| 15 | Barren plateau empirical analysis | 🔴 | PennyLane |
| 16 | Quantum GAN on 1D distribution | 🔴 | PennyLane + PyTorch |
| 17 | Data re-uploading classifier | 🟡 | PennyLane |
| 18 | Expressibility analysis of custom ansatz | 🔴 | PennyLane |
| 19 | Quantum transfer learning (ResNet + PQC) | 🔴 | PennyLane + PyTorch |
| 20 | Reproduce a published QML paper | 🔬 | Any |
| 21 | Contribute to PennyLane / Qiskit | 🔬 | Any |
| 22 | New data encoding study | 🔬 | PennyLane |

---

## 📊 Datasets

> Full dataset descriptions, formats, and usage notes in [`DATASETS.md`](DATASETS.md)

| Dataset | Provider | Contents | Use Case | Access |
|:---|:---|:---|:---|:---:|
| **PennyLane Quantum Datasets** ⭐ | Xanadu | H₂, LiH, H₂O molecular data | VQE, chemistry QML | 🆓 |
| **QML Benchmarks** | Xanadu | Standardized QML model benchmarks | Algorithm comparison | 🆓 |
| **QASMbench** | PNNL | OpenQASM circuit collection | Simulator benchmarking | 🆓 |
| **MQT Bench** | TU Munich | Multi-level circuit benchmarks | Hardware benchmarking | 🆓 |
| **PySCF Molecules** | PySCF team | Molecular Hamiltonians | VQE / quantum chemistry | 🆓 |
| Iris, Wine, Moons (sklearn) | Scikit-learn | Classical 2D/small datasets | VQC and kernel baselines | 🆓 |
| MNIST subset | Standard | Handwritten digits | Hybrid image classification | 🆓 |

---

## 📝 Blogs & Community

> Full listing with descriptions in [`BLOGS.md`](BLOGS.md)

| Resource | Type | Level | Link |
|:---|:---|:---:|:---|
| **Shtetl-Optimized** ⭐ | Research blog | 🟡🔴 | scottaaronson.blog |
| **Quantum Frontiers** | Research blog | 🟡🔴 | quantumfrontiers.com |
| **PennyLane Blog** | Research + tutorials | 🟡🔴 | pennylane.ai/blog |
| **Quantum Computing Stack Exchange** ⭐ | Q&A community | All | quantumcomputing.stackexchange.com |
| **arXiv quant-ph** ⭐ | Preprint server | 🔴🔬 | arxiv.org/archive/quant-ph |
| **Quirk Simulator** ⭐ | Browser circuit tool | 🟢 | algassert.com/quirk |
| **QOSF** | Open source org | 🟡🔴 | qosf.org |
| **Quantum Computing Report** | Industry news | 🟢🟡 | quantumcomputingreport.com |
| **Google Quantum AI Blog** | Research updates | 🟡🔴 | quantumai.google/blog |
| **IBM Research — Quantum** | Research updates | 🟡🔴 | research.ibm.com |

---

## 📖 Glossary Reference

> Full 50+ term glossary in [`GLOSSARY.md`](GLOSSARY.md)

**Quick Reference — Most Essential Terms**

| Term | One-Line Definition |
|:---|:---|
| **Qubit** | Quantum bit. State α\|0⟩ + β\|1⟩ with \|α\|² + \|β\|² = 1 |
| **Superposition** | Quantum system existing in a combination of multiple states |
| **Entanglement** | Multi-qubit correlation with no classical equivalent |
| **Unitary** | Matrix U with UU† = I. All quantum gates are unitary. |
| **Density Matrix** | ρ = \|ψ⟩⟨ψ\| for pure states; Σpᵢ\|ψᵢ⟩⟨ψᵢ\| for mixed |
| **Hamiltonian** | Operator representing total energy of a quantum system |
| **NISQ** | Noisy Intermediate-Scale Quantum (50–1000 qubits, with noise) |
| **PQC** | Parameterized Quantum Circuit — the core QML model |
| **Parameter-Shift** | ∂f/∂θ = [f(θ+π/2) − f(θ−π/2)] / 2 |
| **Barren Plateau** | Exponentially vanishing gradients in random quantum circuits |
| **VQE** | Variational Quantum Eigensolver — for ground state energy |
| **QAOA** | Quantum Approximate Optimization Algorithm |
| **Quantum Kernel** | K(x,y) = \|⟨ψ(x)\|ψ(y)⟩\|² |
| **Expressibility** | How well a PQC covers the Hilbert space of possible states |
| **BQP** | Bounded-Error Quantum Polynomial Time — quantum complexity class |

---

## 🤝 Contributing

Contributions are warmly welcomed. Every quality addition helps the community.

**To add a resource:**
1. Fork this repository
2. Use the standard template from [`CONTRIBUTING.md`](CONTRIBUTING.md)
3. Add to the correct section in the correct file
4. Submit a pull request with a brief description

**Standards enforced:** academic quality, accessible links, no promotional content, no copyright violations. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the full guide.

---

## 📌 Citation

```bibtex
@misc{quantum-computing-qml-resources,
  author       = {Contributors},
  title        = {Quantum Computing and Quantum Machine Learning Resources},
  year         = {2025},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/yourusername/quantum-computing-qml-resources}}
}
```

---

## 📜 License & Disclaimer

This repository is licensed under the **MIT License** — see [`LICENSE`](LICENSE).

The curated resources themselves are the intellectual property of their respective authors. This repository only links to external content and provides organizational structure. Resource quality is assessed carefully, but always verify information from official and peer-reviewed sources. Links may become outdated — please open a GitHub Issue if you find a broken link.

---

<div align="center">

⭐ **If this repository helps you, please star it — it helps others discover it.**

*Maintained with care by the open-source community. Last reviewed: 2025.*

</div>
