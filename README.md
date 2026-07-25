# 🤖 Automata Theory & Formal Languages — Course Repository

<div align="center">

![Topic](https://img.shields.io/badge/Topic-Formal%20Languages%20%26%20Automata-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Theoretical%20Computer%20Science-brightgreen?style=for-the-badge)
![Course](https://img.shields.io/badge/Course-Automata%20Theory-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

*A structured academic archive of homework problem sets, formal mathematical proofs, language hierarchies, and exam solutions for the Automata Theory & Formal Languages course.*

</div>

---

## 📖 Table of Contents
1. [Overview](#-overview)
2. [Repository Structure](#-repository-structure)
3. [Core Topics & Methodology](#-core-topics--methodology)
   - [Regular Languages & Finite Automata](#1-regular-languages--finite-automata)
   - [Context-Free Languages & Grammars](#2-context-free-languages--grammars)
   - [Turing Machines & Computability](#3-turing-machines--computability)
4. [Persian Summary for Students (راهنمای فارسی)](#-persian-summary-for-students-راهنمای-فارسی)
5. [License & Author](#-license--author)

---

## 🔭 Overview
This repository serves as a comprehensive academic portfolio for the **Automata Theory and Formal Languages** university course. Unlike engineering courses focused on code execution, this repository focuses on **pure theoretical computer science**, rigorous mathematical proofs, algorithmic state machine design, and the boundaries of computation.

The materials documented here demonstrate a deep understanding of computational models, language hierarchies (Chomsky Hierarchy), and formal mathematical verification required for advanced computer science research and compiler design.

---

## 📂 Repository Structure

The repository is organized cleanly by evaluation types and assignment series:

```text
📦 Automata
 ┣ 📂 HWs/             # Homework problem sets, theoretical solutions, and formal proofs
 ┃ ┣ 📂 HW1/           # Regular Expressions, DFAs, NFAs, and e-NFAs
 ┃ ┣ 📂 HW2/           # Pumping Lemma for Regular Languages & State Minimization
 ┃ ┣ 📂 HW3/           # Context-Free Grammars (CFG), Derivation Trees, & Ambiguity
 ┃ ┣ 📂 HW4/           # Pushdown Automata (PDA) & Chomsky/Greibach Normal Forms
 ┃ ┗ 📂 HW5/           # Turing Machines, Decidability, & Halting Problem
 ┣ 📂 exams/           # Midterm and Final exam preparations & sample theoretical solutions
 ┃ ┣ 📂 midterm/
 ┃ ┗ 📂 final/
 ┗ 📂 slides/          # Official course lecture slides and reference materials
```

---

## 🧠 Core Topics & Methodology

### 1. Regular Languages & Finite Automata
Focuses on memoryless computation models and pattern recognition frameworks:
* **State Machines:** Designing Deterministic (DFA) and Nondeterministic Finite Automata (NFA / $\epsilon$-NFA) for complex language recognizers.
* **Transformations & Minimization:** Subset construction algorithm (NFA to DFA), state minimization (Myhill-Nerode relations), and regular expression equivalences (Kleene's Theorem).
* **Language Boundaries:** Applying the **Pumping Lemma for Regular Languages** to formally prove non-regularity.

### 2. Context-Free Languages & Grammars
Explores recursive structures, syntax trees, and stack-based computation:
* **Grammars & Syntax:** Designing Context-Free Grammars (CFG), resolving syntactic ambiguity, and converting to Chomsky Normal Form (CNF) and Greibach Normal Form (GNF).
* **Pushdown Automata (PDA):** Designing deterministic and nondeterministic PDAs by acceptance by final state or empty stack.
* **Proving Non-Context-Free Languages:** Utilizing the Pumping Lemma for CFLs to establish structural limitations.

### 3. Turing Machines & Computability
Investigates the ultimate theoretical limits of what algorithms can solve:
* **Machine Design:** Standard Turing Machines (TM), multi-tape variants, and nondeterministic TMs.
* **Computability Theory:** The Church-Turing Thesis, Turing-recognizable (recursively enumerable) vs. Turing-decidable languages.
* **Incomputability:** Formal reduction proofs establishing the undecidability of the **Halting Problem** and Rice's Theorem.

---

## 🇮🇷 Persian Summary for Students (راهنمای فارسی)

<details>
<summary><strong>کلیک کنید: توضیحات فارسی و راهنمای ساختار مخزن برای دانشجویان</strong></summary>

<br>

### درباره این ریپازیتوری
این مخزن (Repository) یک آرشیو جامع و آکادمیک از تمرین‌ها، پاسخ‌های تشریحی، اثبات‌های ریاضی و اسلایدهای درس **نظریه زبان‌ها و ماشین‌ها (Automata Theory & Formal Languages)** است. این درس پایه‌ی اصلی دروس پیشرفته‌تری مانند طراحی کامپایلر، هوش مصنوعی، و نظریه محاسب‌پذیری در رشته مهندسی کامپیوتر محسوب می‌شود.

### معرفی پوشه‌ها و محتوا
* **پوشه `HWs/` (تمرین‌های سری ۱ تا ۵):** شامل حل تشریحی مسائل مربوط به ماشین‌های متناهی (DFA/NFA)، گرامرهای مستقل از متن (CFG)، ماشین‌های پوش‌داون (PDA) و ماشین تورینگ.
* **پوشه `exams/` (آزمون‌ها):** سوالات و نمونه‌پاسخ‌های تشریحی برای آمادگی آزمون‌های میان‌ترم (`midterm`) و پایان‌ترم (`final`).
* **پوشه `slides/` (اسلایدها و منابع):** اسلایدهای رسمی تدریس درس و کتاب‌های مرجع (مانند کتاب لینز یا سیپسر).

### اهمیت این مباحث در مهندسی نرم‌افزار
برخلاف دروس برنامه‌نویسی عملی، تمرکز این درس بر روی «تفکر الگوریتمی»، «اثبات ریاضیاتی درستی سیستم‌ها» و درک مرزهای محاسب‌پذیری است که برای اپلای آکادمیک و ریسرچ در حوزه‌های تئوری کامپیوتر اهمیت حیاتی دارد.
</details>

---

## 📄 License & Author

This repository is open-source and released under the [MIT License](LICENSE). Feel free to reference these theoretical solutions and mathematical proofs for study and academic review.

<div align="center">
  <sub>Developed and maintained by <b>M. Mahdi Moradi</b> (@mahdi0x06).</sub>
</div>
