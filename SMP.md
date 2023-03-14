---
marp: true
theme: custom
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

<!-- paginate: false -->
  
 # **FAIR4RS and Software Management Plans**


**TU Delft** - [Digital Competence Centre](https://dcc.tudelft.nl)

*These slides were made with [Marp](https://marp.app/).*

---
<!-- paginate: true -->

# **Contents**

- What is FAIR for research software?
- What is a Software Management Plan?
- Why is it useful?
- When is it useful?
- How do I get started?



---
# **FAIR for Research Software**

**Findable:** registry (Citation File)

**Accessible:** publishing/archiving (GitHub, Zenodo)

**Interoperable:** integration with other software/hardware (containerization, dependencies)

**Reusable:** software quality, documentation, testing, modular coding, Continuous Integration, ...

*All quite recent:*
[*14 October 2022 - Introducing the FAIR principles for research software*](https://www.nature.com/articles/s41597-022-01710-x)

---
## A history of confusing terminology

![height:550px center](./images/reproducible-definition-grid.svg)

---

- [14 October 2022 - Introducing the FAIR principles for research software](https://www.nature.com/articles/s41597-022-01710-x)
- https://fair-software.nl/
- [Publishing data and code at TU Delft]()
- [Recommendations for Code Reuse](https://the-turing-way.netlify.app/reproducible-research/code-reuse/code-reuse-details.html)

---

## Definition of Research software

Research Software includes source code files, algorithms, scripts, computational
workflows and executables that were created during the research process
or for a research purpose. 

*Software components (e.g., operating systems, libraries, dependencies, packages, scripts, etc.) that are used for research but were not created during or with a clear research intent should be considered software in research and not Research Software.* 

---

# **Software Management Plans**

An SMP is a document that describes how a specific software project is **developed**, **maintained**, and **curated**. The goal of an SMP is to ensure that the software is usable and **maintainable** in the long term.



---

# **Why are SMP's useful?**

An SMP makes explicit what research software does, who it is for, what the outputs are, who is responsible for the release and ensures that the software stays available to the community (and for how long).


--- 

## Core requirements for an SMP

**Purpose**
What is the current reason or expected end-use for developing 
the software?

**Reliability**
The effect of software failure and/or non-maintenance on **risk of harm**, **reputation**, **research**.

**Maintenance**
The long-term effort needed to **maintain** the software as long as it might be used as a standalone tool or dependency.

---

## Medium management level

**Purpose**
Software is part of a research project or the primary research output. May be (re)used by others.

**Reliability**
Direct influence on researcher, good practices such as version control (Git) and user/technical documentation is essential.

**Maintenance**
This software’s functionality is useful to researchers both in and outside the project, making it suitable for distribution. It can have a lifespan longer than the project in which it was developed and therefore long-term sustainability becomes more important.

---

![bg right height:600px](./images/SMP_topics.png)