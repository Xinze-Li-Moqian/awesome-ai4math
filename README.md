

<p align="center">
  <b>Awesome AI4Math</b>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</p>

<p align="center">
  A curated list of AI for Mathematics resources — the ecosystem reshaping mathematics.
</p>

---

## Contents

### Core Technologies
- [Proof Assistants](#proof-assistants)
  - [Dependent Type / HoTT](#dependent-type--hott) — Lean, Coq, Agda, Idris, F*, Arend, Aya
  - [HOL Family](#hol-family) — Isabelle, HOL4, HOL Light
  - [Other Important Systems](#other-important-systems) — Mizar, Metamath, PVS, ACL2
  - [Cubical Type Theory](#cubical-type-theory)
  - [Logical Frameworks](#logical-frameworks)
  - [Historical Systems](#historical-systems)
  - [Other / Emerging](#other--emerging)

### AI & Automation
- [AI for Formal Mathematics](#ai-for-formal-mathematics)
  - [Neural Theorem Provers](#neural-theorem-provers) — AlphaProof, Goedel, DeepSeek, Kimina
  - [IDE & Copilot Tools](#ide--copilot-tools) — Mozi, Lean Copilot, llmstep
  - [Search Engines](#search-engines) — LeanSearch, Loogle
  - [Infrastructure & Frameworks](#infrastructure--frameworks) — LeanDojo, Pantograph
  - [Benchmarks & Datasets](#benchmarks--datasets) — MiniF2F, PutnamBench
  - [Autoformalization](#autoformalization)
  - [Geometry Solvers](#geometry-solvers) — AlphaGeometry, Seed-Geometry
  - [Agentic CLI Tools](#agentic-cli-tools)
- [Automated Theorem Provers (Classical)](#automated-theorem-provers-classical)
  - [First-Order ATPs](#first-order-atps) — Vampire, E Prover
  - [SMT Solvers](#smt-solvers) — Z3, CVC5
  - [Integration with Proof Assistants](#integration-with-proof-assistants)

### Ecosystem
- [Companies & Organizations](#companies--organizations)
  - [AI Math Startups](#ai-math-startups) — Harmonic, Axiom, Math Inc., Morph
  - [Research Organizations](#research-organizations) — Lean FRO, Numina
  - [Academic Labs](#academic-labs) — PKU, Caltech, Princeton
  - [Big Tech AI Labs](#big-tech-ai-labs) — DeepMind, ByteDance, DeepSeek
  - [Compute Infrastructure](#compute-infrastructure) — Hyperbolic, Together AI
  - [Corporate Sponsors](#corporate-sponsors) — XTX Markets, Google.org
  - [Funding & Philanthropy](#funding--philanthropy) — AI for Math Fund, NSF, DARPA
- [Quick Links](#quick-links)
- [Timeline: Key Milestones](#timeline-key-milestones)

### Resources
- [Tools & Platforms](#tools--platforms)
- [Learning Resources](#learning-resources)
  - [YouTube Channels](#youtube-channels)
  - [Seminars](#seminars)
  - [Podcasts](#podcasts)
  - [Courses](#courses)
  - [Blogs & Newsletters](#blogs--newsletters)
- [Research & Papers](#research--papers)
  - [Preprint Platforms](#preprint-platforms)
  - [Landmark Papers](#landmark-papers)
- [Communities](#communities)
- [People](#people)

---

## Proof Assistants

### Dependent Type / HoTT

#### Lean

*Microsoft Research → Lean FRO. Created by Leonardo de Moura.*

##### Core

- [Lean 4](https://github.com/leanprover/lean4) - Functional programming language and theorem prover
- [Mathlib](https://github.com/leanprover-community/mathlib4) - The math library for Lean 4, largest unified formalized math library
- [Lake](https://github.com/leanprover/lake) - Lean's build system and package manager
- [Batteries](https://github.com/leanprover-community/batteries) - Extended standard library for Lean 4 (formerly std4)

##### Learning

- [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/) - Interactive tutorial for mathematical formalization
- [Theorem Proving in Lean 4](https://leanprover.github.io/theorem_proving_in_lean4/) - Official introduction to theorem proving
- [Functional Programming in Lean](https://leanprover.github.io/functional_programming_in_lean/) - Learn Lean as a programming language
- [Natural Number Game](https://adam.math.hhu.de/#/g/leanprover-community/nng4) - Gamified introduction to Lean proofs
- [The Mechanics of Proof](https://hrmacbeth.github.io/math2001/) - Undergraduate introduction to proofs using Lean

##### Tools

- [Lean 4 VS Code Extension](https://github.com/leanprover/vscode-lean4) - Official VS Code integration
- [Blueprint](https://github.com/PatrickMassot/leanblueprint) - Generate dependency graphs for Lean projects
- [doc-gen4](https://github.com/leanprover/doc-gen4) - Documentation generator for Lean 4
- [Paperproof](https://github.com/Paper-Proof/paperproof) - Visual proof interface for Lean
- [LeanInfer](https://github.com/lean-dojo/LeanInfer) - Run neural network inference in Lean
- [Pantograph](https://github.com/lenianiva/Pantograph) - Machine-to-machine interaction for Lean

##### Projects

- [FLT](https://github.com/ImperialCollegeLondon/FLT) - Fermat's Last Theorem formalization (in progress)
- [PFR](https://github.com/teorth/pfr) - Polynomial Freiman-Ruzsa conjecture formalization
- [Sphere Eversion](https://github.com/leanprover-community/sphere-eversion) - Formalized proof of sphere eversion
- [Liquid Tensor Experiment](https://github.com/leanprover-community/lean-liquid) - Scholze's liquid tensor experiment
- [Prime Number Theorem](https://github.com/AlexKontorovich/PrimeNumberTheoremAnd) - Prime Number Theorem and more

#### Coq / Rocq

*INRIA. Renamed to Rocq in 2024.*

- [Rocq (Coq)](https://github.com/coq/coq) - The Coq proof assistant, now renamed to Rocq
- [MathComp](https://github.com/math-comp/math-comp) - Mathematical Components library
- [Software Foundations](https://softwarefoundations.cis.upenn.edu/) - Classic introduction to Coq
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - Advanced Coq programming

#### Agda

*Chalmers University, Sweden.*

- [Agda](https://github.com/agda/agda) - Dependently typed programming language and proof assistant
- [agda-stdlib](https://github.com/agda/agda-stdlib) - Agda standard library
- [Cubical Agda](https://agda.readthedocs.io/en/latest/language/cubical.html) - Cubical type theory mode in Agda
- [Programming Language Foundations in Agda](https://plfa.github.io/) - Textbook on PL theory in Agda

#### Idris

*Created by Edwin Brady.*

- [Idris 2](https://github.com/idris-lang/Idris2) - Dependently typed language with quantitative types
- [Idris 1](https://github.com/idris-lang/Idris-dev) - Original Idris implementation
- [Type-Driven Development with Idris](https://www.manning.com/books/type-driven-development-with-idris) - Official book by Edwin Brady

#### F*

*Microsoft Research. SMT-driven verification.*

- [F*](https://github.com/FStarLang/FStar) - Verification-oriented ML dialect with dependent types
- [Everest](https://project-everest.github.io/) - Verified secure implementations using F*

#### Arend

*JetBrains. Native HoTT support.*

- [Arend](https://github.com/JetBrains/Arend) - Theorem prover with native homotopy type theory
- [Arend Lib](https://github.com/JetBrains/arend-lib) - Standard library with HoTT foundations

#### Aya

*Chinese team. Based on cubical type theory.*

- [Aya](https://github.com/aya-prover/aya-dev) - Cubical type theory based proof assistant

### HOL Family

#### Isabelle

*Cambridge & TU München.*

- [Isabelle](https://isabelle.in.tum.de/) - Generic proof assistant, primarily used with HOL
- [Archive of Formal Proofs](https://www.isa-afp.org/) - Large collection of proof libraries for Isabelle

#### HOL4

*Primary successor to the HOL system.*

- [HOL4](https://github.com/HOL-Theorem-Prover/HOL) - Interactive theorem prover for higher-order logic

#### HOL Light

*Created by John Harrison. Minimalist design.*

- [HOL Light](https://github.com/jrh13/hol-light) - Simplified HOL prover, used in Flyspeck project

#### ProofPower

*Industrial-grade HOL system.*

- [ProofPower](https://github.com/RobArthan/pp) - Tool suite for specification and proof in HOL and Z

#### IMPS

- [IMPS](https://imps.mcmaster.ca/) - Interactive Mathematical Proof System

### Other Important Systems

#### Mizar

*Tarski-Grothendieck set theory. One of the largest formalized math libraries.*

- [Mizar](http://mizar.org/) - System for formalizing mathematics
- [Mizar Mathematical Library](http://mizar.org/library/) - Extensive library of formalized mathematics

#### Metamath

*Minimalist approach to formal verification.*

- [Metamath](https://us.metamath.org/) - Tiny language for developing formal math databases
- [set.mm](https://github.com/metamath/set.mm) - Main Metamath database for set theory

#### PVS

*SRI International.*

- [PVS](https://pvs.csl.sri.com/) - Prototype Verification System

#### ACL2

*Boyer-Moore tradition.*

- [ACL2](https://www.cs.utexas.edu/users/moore/acl2/) - Computational Logic for Applicative Common Lisp

#### Nuprl

*Cornell University. Extended type theory.*

- [Nuprl](http://www.nuprl.org/) - Proof development system based on constructive type theory

#### Dafny

*Microsoft. Program verification.*

- [Dafny](https://github.com/dafny-lang/dafny) - Verification-aware programming language

#### Atelier B

*B method for industrial applications.*

- [Atelier B](https://www.atelierb.eu/) - Industrial tool for B method formal development

### Cubical Type Theory

- [cubicaltt](https://github.com/mortberg/cubicaltt) - Experimental implementation of cubical type theory
- [redtt](https://github.com/RedPRL/redtt) - Experimental proof assistant for cartesian cubical type theory
- [cooltt](https://github.com/RedPRL/cooltt) - Cool elaborator for cartesian cubical type theory (successor to redtt)
- [RedPRL](https://github.com/RedPRL/sml-redprl) - Proof assistant for computational cubical type theory
- [yacctt](https://github.com/mortberg/yacctt) - Yet another cubical type theory

### Logical Frameworks

- [Twelf](http://twelf.org/) - Implementation of the LF logical framework
- [Dedukti](https://github.com/Deducteam/Dedukti) - Universal proof checker based on λΠ-calculus modulo
- [Beluga](https://github.com/Beluga-lang/Beluga) - Proof environment for contextual modal types (McGill)
- [Abella](https://abella-prover.org/) - Interactive theorem prover based on λ-tree syntax

### Historical Systems

*Pioneering systems that shaped the field.*

- [Automath](https://www.win.tue.nl/automath/) - First proof checker (1967, de Bruijn)
- [LCF](https://www.cl.cam.ac.uk/~jrh13/papers/lcf.html) - Logic for Computable Functions (origin of ML language)
- [Nqthm](https://www.cs.utexas.edu/users/boyer/nqthm.html) - Boyer-Moore theorem prover (predecessor to ACL2)
- [LEGO](http://www.dcs.ed.ac.uk/home/lego/) - Edinburgh proof assistant
- [Matita](http://matita.cs.unibo.it/) - Coq-like system (no longer maintained)
- [MINLOG](https://www.mathematik.uni-muenchen.de/~minlog/) - System for first-order minimal logic
- [ALF](https://www.cse.chalmers.se/~bengt/papers/alfintro.pdf) - Another Logical Framework

### Other / Emerging

- [Acorn](https://github.com/acornprover/acorn) - AI-integrated theorem prover by Kevin Lacker
- [Andromeda](https://github.com/Andromedans/andromeda) - Type theory with equality reflection
- [litex](https://github.com/litexlang/golitex) - Simple formal language learnable in 2 hours ([Website](https://litexlang.com))
- [Liquid Haskell](https://github.com/ucsd-progsys/liquidhaskell) - Refinement types for Haskell
- [Rzk](https://github.com/rzk-lang/rzk) - Proof assistant for simplicial type theory

---

## AI for Formal Mathematics

*The 2024-2025 explosion of AI tools for theorem proving*

### Neural Theorem Provers

*Fully automated systems that generate formal proofs*

#### IMO-Level Systems (2025)

| System | Organization | MiniF2F | IMO 2025 | Open Source |
|--------|--------------|---------|----------|-------------|
| Seed-Prover 1.5 | ByteDance | Saturated | 5/6 Gold | ❌ |
| Aristotle | Harmonic AI | 98%+ | 5/6 Gold | ❌ |
| Goedel-Prover-V2 | Princeton | 90.4% | - | ✅ |
| Kimina-Prover | Moonshot AI | 80.7% | - | ✅ (distill) |
| DeepSeek-Prover-V2 | DeepSeek | 88.9% | - | ✅ |
| AlphaProof | DeepMind | - | Silver 2024 | ❌ |

#### Open Source Provers

- [Goedel-Prover](https://github.com/Goedel-LM/Goedel-Prover) - Princeton, SOTA open-source, scaffolded data synthesis
- [Goedel-Prover-V2](https://github.com/Goedel-LM/Goedel-Prover-V2) - 90.4% MiniF2F, self-correction mode
- [DeepSeek-Prover-V2](https://github.com/deepseek-ai/DeepSeek-Prover-V2) - 671B model, subgoal decomposition
- [Kimina-Prover](https://github.com/MoonshotAI/Kimina-Prover-Preview) - 72B, formal reasoning pattern, distilled 1.5B/7B
- [BFS-Prover](https://github.com/bytedance/BFS-Prover) - ByteDance, scalable best-first tree search
- [Morph Prover v0 7B](https://www.morph.so/) - Morph Labs, open-source conversational prover

#### Commercial/Closed Systems

- [Aristotle](https://aristotle.harmonic.fun/) - Harmonic AI, IMO Gold, API available
- [Seed-Prover](https://seed.bytedance.com/en/research) - ByteDance, Seed-Geometry for geometry
- [AlphaProof](https://deepmind.google/discover/blog/ai-solves-imo-problems-at-silver-medal-level/) - DeepMind, Nature 2025
- [Gauss](https://math.inc) - Math Inc., autoformalization agent, Strong PNT in 3 weeks

#### Research Papers

- [AlphaProof Paper](https://www.nature.com/articles/s41586-025-08998-w) - Nature, Nov 2025
- [A Survey on Deep Learning for Theorem Proving](https://github.com/zhaoyu-li/DL4TP) - Comprehensive paper list
- [Formal Mathematical Reasoning: A New Frontier in AI](https://arxiv.org/abs/2412.16075) - Position paper

### IDE & Copilot Tools

*Human-AI collaborative tools for proof development*

#### VS Code Extensions

- [Mozi Lean Copilot](https://marketplace.visualstudio.com/items?itemName=PKUAI4Math.mozi) - PKU AI4Math + IQuest, generate→verify→feedback loop, LeanSearch integration (Beta)
- [Lean Copilot](https://github.com/lean-dojo/LeanCopilot) - Caltech/LeanDojo, suggest_tactics, search_proof, premise selection
- [llmstep](https://github.com/wellecks/llmstep) - Lightweight tactic suggestions, model-agnostic
- [LLMLean](https://github.com/cmu-l3/llmlean) - OpenAI/local LLM integration

#### Cloud IDEs

- [ReasLab IDE](https://prove.reaslab.io/) - PKU BICMR, zero-install browser IDE, real-time collaboration
- [Lean 4 Web](https://live.lean-lang.org/) - Official Lean playground

#### Commercial APIs

- [Aristotle API](https://aristotle.harmonic.fun/) - Harmonic, fill sorry, counterexamples, Mathlib integration

### Search Engines

*Finding theorems and lemmas in formal libraries*

- [LeanSearch](https://leansearch.net/) - PKU BICMR (ReasLab), natural language semantic search for Mathlib4
- [Loogle](https://loogle.lean-lang.org/) - Lean FRO, type signature search (like Hoogle for Haskell)
- [LeanExplore](https://leanexplore.com/) - Multi-library search, MCP server support
- [Moogle](https://www.moogle.ai/) - Early semantic search engine

### Infrastructure & Frameworks

*Tools for building AI theorem provers*

#### Data Extraction & Interaction

- [LeanDojo](https://github.com/lean-dojo/LeanDojo) - Caltech, Python interaction, data extraction, ReProver
- [LeanDojo-v2](https://github.com/lean-dojo/LeanDojo-v2) - End-to-end framework for Lean 4
- [Jixia (稷下)](https://reservoir.lean-lang.org/@reaslab/jixia) - PKU BICMR, static analysis, ML data extraction
- [Pantograph](https://github.com/lenianiva/Pantograph) - Lean 4 interaction library

#### High-Performance Servers

- [Kimina Lean Server](https://github.com/MoonshotAI/kimina-lean-server) - Moonshot AI, high-performance REPL for RL training
- [Jixia-interactive](https://github.com/reaslab/REAL-Prover) - PKU, REAL-Prover environment

#### Agent Frameworks

- [LeanAgent](https://github.com/lean-dojo/LeanAgent) - Caltech, lifelong learning, auto PR generation
- [lean-agentic](https://github.com/agenticsorg/lean-agentic) - MCP server, vector memory, Claude Code integration
- [P2PCLAW](https://github.com/Agnuxo1/p2pclaw) - Decentralized peer-reviewed science network combining P2P collaboration, Lean 4 formal verification, AI agents, and community-driven scientific publishing

#### Retrieval & Premise Selection

- [REAL-Prover](https://arxiv.org/abs/2505.20613) - PKU, retrieval-augmented Lean prover
- [LeanSearch-PS](https://github.com/reaslab/LeanSearch) - Semantic premise selection

### Benchmarks & Datasets

*Evaluating AI theorem provers*

#### Competition Math

| Benchmark | Level | Problems | Format |
|-----------|-------|----------|--------|
| [MiniF2F](https://github.com/openai/miniF2F) | High School (IMO/AMC) | 488 | Lean/Isabelle |
| [PutnamBench](https://github.com/trishullab/PutnamBench) | Undergraduate (Putnam) | 658 | Lean 4 |
| [ProofNet](https://github.com/albertqjiang/ProofNet) | Undergraduate | 371 | Lean 3 |
| [FIMO](https://github.com/chaitanya100100/fimo) | IMO Problems | - | Lean 4 |

#### Advanced Mathematics

- [NuminaMath-LEAN](https://huggingface.co/datasets/AI-MO/NuminaMath-LEAN) - 104K competition problems formalized

#### General Benchmarks

- [Lean Workbook](https://huggingface.co/datasets/pkuai4math/Lean-Workbook) - Large-scale problem set
- [miniCTX](https://github.com/princeton-nlp/miniCTX) - In-context theorem proving
- [TPTP](https://www.tptp.org/) - Thousands of Problems for Theorem Provers

### Autoformalization

*Translating natural language to formal proofs*

- [Kimina-Autoformalizer](https://huggingface.co/AI-MO/Kimina-Autoformalizer-7B) - Numina/Moonshot, 80% MiniF2F pass rate
- [Herald](https://arxiv.org/abs/2310.16763) - Natural language annotated Lean 4 dataset
- [FormalAlign](https://arxiv.org/abs/2410.00246) - Alignment evaluation for autoformalization
- [Draft-Sketch-Prove](https://arxiv.org/abs/2210.12283) - Informal to formal pipeline

### Geometry Solvers

*Specialized systems for Euclidean geometry*

- [AlphaGeometry 2](https://deepmind.google/discover/blog/alphageometry-2/) - DeepMind, IMO geometry
- [Seed-Geometry](https://arxiv.org/abs/2507.23726) - ByteDance, instant geometry verification
- [Yuclid/Newclid](https://github.com/harmonic-fun/newclid) - Harmonic AI, open-sourced geometry solver
- [LeanGeo](https://github.com/project-numina/LeanGeo) - Numina + PKU, geometry in Lean 4

### Agentic CLI Tools

*General-purpose AI coding assistants that work with Lean*

- [Claude Code](https://docs.anthropic.com/en/docs/build-with-claude/claude-code) - Anthropic, MCP support, agentic terminal
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI, GPT-5 powered
- [Aider](https://github.com/paul-gauthier/aider) - Open source, multi-model support
- [Cline](https://github.com/cline/cline) - VS Code + CLI, autonomous agent

---

## Automated Theorem Provers (Classical)

*Traditional symbolic reasoning systems*

### First-Order ATPs

- [Vampire](https://github.com/vprover/vampire) - Most successful ATP, CASC winner
- [E Prover](https://github.com/eprover/eprover) - Efficient equational reasoning
- [SPASS](https://www.mpi-inf.mpg.de/departments/automation-of-logic/software/spass-workbench) - Automated theorem prover
- [Prover9](https://www.cs.unm.edu/~mccune/prover9/) - Resolution/paramodulation

### SMT Solvers

- [Z3](https://github.com/Z3Prover/z3) - Microsoft, most popular SMT solver
- [CVC5](https://github.com/cvc5/cvc5) - Stanford, SMT-COMP winner
- [Yices](https://yices.csl.sri.com/) - SRI, efficient SMT solver

### Integration with Proof Assistants

- [Sledgehammer](https://isabelle.in.tum.de/website-Isabelle2012/sledgehammer.html) - Isabelle + external ATPs
- [Lean-SMT](https://arxiv.org/abs/2505.15689) - Lean 4 + SMT solvers (cvc5)
- [Duper](https://github.com/leanprover-community/duper) - Superposition prover for Lean 4

---

## Companies & Organizations

### AI Math Startups

| Company | Founded | Focus | Funding | Key Product |
|---------|---------|-------|---------|-------------|
| [Harmonic AI](https://harmonic.fun/) | 2023 | Mathematical Superintelligence | $295M (Series C, $1.45B val) | Aristotle |
| [Axiom Math](https://axiommath.ai/) | 2025 | AI Mathematician | $64M Seed ($300M val) | Autoformalization + Conjecturer |
| [Math Inc.](https://math.inc/) | 2025 | Verified Superintelligence | - | Gauss (Strong PNT) |
| [Morph Labs](https://morph.so/) | 2023 | Personal AI Proof Engineer | - | Morph Prover, Trinity |

#### Company Details

**Harmonic AI** (Palo Alto)
- Founders: Vlad Tenev (Robinhood CEO), Tudor Achim
- Investors: Sequoia, Kleiner Perkins, Index Ventures, Ribbit Capital
- Achievements: IMO 2025 Gold (5/6), 98%+ MiniF2F, Erdős Problem #124
- Focus: Mathematical Superintelligence (MSI), hallucination-free AI

**Axiom Math** (San Francisco)
- Founder: Carina Hong (Stanford dropout, MIT/Oxford background)
- CTO: Shubho Sengupta (ex-Meta FAIR)
- Team: François Charton, Aram Markosyan, Hugh Leather (ex-Meta FAIR)
- Investors: B Capital (lead), Greycroft, Madrona, Menlo Ventures
- Focus: Auto-formalizer, Conjecturer, Prover, Knowledge Base

**Math Inc.**
- Founder: Christian Szegedy (ex-xAI, ex-Google, inventor of Batch Norm & adversarial examples)
- Achievements: Strong Prime Number Theorem formalization in 3 weeks (vs 18+ months human effort)
- Focus: Autoformalization at scale, verified superintelligence

**Morph Labs** (San Francisco)
- Founder: Jesse Han
- Products: Morph Prover v0 7B, Trinity autoformalization system, Infinibranch
- Focus: Cloud for superintelligence, AI-human collaboration

### Research Organizations

| Organization | Type | Focus |
|--------------|------|-------|
| [Lean FRO](https://lean-fro.org/) | Non-profit | Lean development & ecosystem |
| [Mathlib Initiative](https://leanprover-community.github.io/) | Community | Mathematical library for Lean |
| [Project Numina](https://projectnumina.ai/) | Research | AI for math, datasets, AIMO winner |

#### Organization Details

**Lean FRO** (Focused Research Organization)
- Founded: July 2023 (within Convergent Research)
- Leadership: Leonardo de Moura (Chief Architect, Lean creator), Sebastian Ullrich (Head of Engineering)
- Funders: Simons Foundation, Alfred P. Sloan Foundation, Richard Merkin Foundation, Alex Gerko ($10M, July 2025)
- Focus: Lean scalability, usability, proof automation, documentation

**Project Numina**
- Founded: Late 2023
- Founders: Jia Li, Yann Fleureau, Guillaume Lample, Stan Polu, Hélène Evain
- Partners: Hugging Face, Mistral AI, General Catalyst, Answer.AI, PKU BICMR
- Achievements: Won AIMO 2024 Progress Prize
- Products: NuminaMath, Kimina-Autoformalizer, LeanGeo

### Academic Labs

| Lab | Institution | Focus |
|-----|-------------|-------|
| [PKU BICMR AI4Math](https://bicmr.pku.edu.cn/) | Peking University | ReasLab IDE, LeanSearch, Jixia, Mozi |
| [LeanDojo](https://leandojo.org/) | Caltech | LeanDojo, Lean Copilot, LeanAgent |
| [Princeton PLI](https://pli.princeton.edu/) | Princeton | Goedel-Prover |

### Big Tech AI Labs

| Lab | Company | Key Projects | Achievements |
|-----|---------|--------------|--------------|
| [DeepMind](https://deepmind.google/) | Google | AlphaProof, AlphaGeometry 2, Gemini Deep Think | IMO 2024 Silver, IMO 2025 Gold (5/6) |
| [Seed AI4Math](https://seed.bytedance.com/) | ByteDance | Seed-Prover 1.5, BFS-Prover, Seed-Geometry | IMO 2025 Gold (5/6), 88% Putnam |
| [DeepSeek](https://www.deepseek.com/) | DeepSeek | DeepSeek-Prover-V2 (671B) | 88.9% MiniF2F, open-source |
| [Moonshot AI](https://www.moonshot.cn/) | Moonshot | Kimina-Prover, Kimina Lean Server | 80.7% MiniF2F |
| [OpenAI](https://openai.com/) | OpenAI | o1/o3 reasoning models | IMO 2025 (natural language) |
| [AWS Automated Reasoning](https://aws.amazon.com/security/provable-security/) | Amazon | Cedar, LNSym, SampCert | Lean verification for AWS services |
| [Meta FAIR](https://ai.meta.com/) | Meta | ML for theorem proving | Research on Coq/Lean |

#### Lab Details

**Google DeepMind**
- AI for Math Initiative: Funding + technology support
- Partners: Imperial College, IAS, IHES, Simons Institute, TIFR
- Technology: Provides Gemini Deep Think, AlphaEvolve, AlphaProof to collaborators

**AWS Automated Reasoning Group**
- Key person: Leonardo de Moura (Lean creator, Senior Principal Applied Scientist)
- [Cedar](https://github.com/cedar-policy/cedar-spec) - Authorization policy language with Lean verification
- Amazon Bedrock Automated Reasoning checks (2025) - Formal verification to reduce AI hallucinations

### Compute Infrastructure

*GPU and compute providers for AI4Math research*

| Provider | Type | AI4Math Relevance | Pricing |
|----------|------|-------------------|---------|
| [Hyperbolic](https://www.hyperbolic.ai/) | Decentralized GPU | Math PhD founders, [AI at Math blog](https://www.hyperbolic.ai/blog/math-and-ai) | 75% cheaper than cloud |
| [Together AI](https://www.together.ai/) | GPU cloud | 10K+ GPU cluster, open model hosting | API-based |
| [Lambda Cloud](https://lambdalabs.com/) | GPU cloud | ML research focused | On-demand |
| [io.net](https://io.net/) | Decentralized GPU (Solana) | 130+ countries, aggregates Render/Filecoin | 70% cheaper |
| [Akash](https://akash.network/) | Decentralized cloud | Reverse auction model | 80% cheaper |

#### Hyperbolic

*Most AI4Math-relevant compute provider*

- **Founders**: Jasper Zhang PhD (UC Berkeley Math), Yuchen Jin PhD
- **Funding**: $7M Seed (Polychain + Lightspeed), $12M Series (Variant)
- **Users**: 195,000+ developers including Stanford, Berkeley, Hugging Face, LMSYS
- **Technology**: Hyper-dOS, Proof of Sampling (PoSP)

### Corporate Sponsors

| Sponsor | Contribution | Total |
|---------|--------------|-------|
| [XTX Markets](https://www.xtxmarkets.com/) | AI for Math Fund, AIMO Prize, Lean FRO | $28M+ |
| [Google.org](https://www.google.org/) | AI for Math Initiative (funding + technology) | - |
| [Simons Foundation](https://www.simonsfoundation.org/) | Lean FRO, ICARM (CMU) | - |
| [Alfred P. Sloan Foundation](https://sloan.org/) | Lean FRO | - |

### Funding & Philanthropy

*A guide to AI4Math funding opportunities for researchers, startups, and builders*

#### Overview

| Type | Program | Amount | Eligibility | Status |
|------|---------|--------|-------------|--------|
| Philanthropy | AI for Math Fund | Up to $1M | Researchers/Nonprofits/Companies | 🟢 Open |
| US Gov | NSF AIMing | $500K-$1.2M | Academic institutions | 🟢 Annual |
| US Gov | DARPA expMath | TBD | Companies/Academic | 🟢 Active |
| US Gov | NSF SBIR/STTR | $50K-$2M | US startups | 🟢 Rolling |
| Foundation | Simons Foundation | $3K-millions | Academic | 🟢 Multiple |
| Accelerator | Y Combinator | $500K | Startups | 🟢 Quarterly |
| Corporate | Google AI First | $350K credits | AI startups | 🟢 Rolling |
| Corporate | NVIDIA Inception | GPU credits | AI startups | 🟢 Rolling |

#### AI for Math Fund (XTX Markets + Renaissance Philanthropy)

*Most relevant AI4Math-specific funding*

- **Total**: $18M (first round, doubled from initial $9.2M)
- **Per grant**: Up to $1,000,000
- **Duration**: Up to 24 months
- **Eligibility**: Researchers, nonprofits, **companies**, mathematicians, software engineers
- **Advisor**: Terence Tao (Fields Medalist)
- **Website**: [renaissancephilanthropy.org](https://www.renaissancephilanthropy.org/initiatives/ai-for-math-fund)
- **2025 Recipients**: [29 inaugural grants](https://www.renaissancephilanthropy.org/ai-for-math-fund-projects)

**Focus Areas**:
1. Production-ready open-source tools (autoformalization, proof generation, verified code synthesis)
2. Open datasets of theorems, proofs, math problems
3. Field building (textbooks, courses, community resources)
4. Moonshot ideas (high-risk, high-reward AI math research)

#### NSF AIMing Program

*Primary US government AI+Math funding*

- **Program**: NSF 24-554
- **Amount**: $500,000 - $1,200,000 per grant
- **Duration**: Up to 3 years
- **Annual budget**: ~$6M (6-10 projects/year)
- **Eligibility**: US academic institutions
- **Website**: [nsf.gov/funding/opportunities/aiming](https://www.nsf.gov/funding/opportunities/aiming-artificial-intelligence-formal-methods-mathematical)

#### DARPA expMath (Exponentiating Mathematics)

*DARPA frontier research program*

- **Goal**: Develop AI collaborators to accelerate pure mathematics by orders of magnitude
- **Duration**: 36 months
- **Program Manager**: Patrick Shafto
- **Website**: [darpa.mil/research/programs/expmath](https://www.darpa.mil/research/programs/expmath-exponential-mathematics)
- **Note**: Contracts only (no grants), focuses on pure mathematics

#### NSF SBIR/STTR

*Non-dilutive funding for US startups*

- **Phase I**: $50,000 - $500,000 (6-12 months)
- **Phase II**: Up to $2,000,000
- **Success rate**: Phase I ~20%, Phase II 40-60%
- **Eligibility**: US small business (51%+ US citizen/PR ownership)
- **Website**: [seedfund.nsf.gov](https://seedfund.nsf.gov/topics/artificial-intelligence/)

#### Other Programs

**Simons Foundation**
- Major funder of Lean FRO (with Sloan Foundation, Merkin Foundation)
- Simons Collaborations in MPS, Targeted Grants
- [simonsfoundation.org](https://www.simonsfoundation.org/)

**NSF ICARM** (Institute for Computer-Assisted Reasoning in Mathematics)
- Host: Carnegie Mellon University
- Funded by: NSF + Simons Foundation
- Focus: Formal methods, AI, ML for mathematical research

**AIMO Prize** (AI Math Olympiad)
- Sponsor: XTX Markets / Alex Gerko
- Goal: AI that achieves IMO gold medal
- Progress Prize 2024: Won by Project Numina

#### Accelerators & Corporate Programs

| Program | Benefit | Link |
|---------|---------|------|
| Y Combinator | $500K investment | [ycombinator.com](https://www.ycombinator.com/) |
| Google AI First | $350K cloud credits | Google Cloud |
| NVIDIA Inception | GPU credits + support | [nvidia.com/startups](https://www.nvidia.com/en-us/startups/) |

#### Application Strategy

**For Startups**:
1. AI for Math Fund - accepts companies, up to $1M non-dilutive
2. NSF SBIR/STTR - requires US entity, quick seed funding
3. Stack accelerators: YC + Google AI First + NVIDIA Inception

**For Academics**:
1. NSF AIMing - primary funding source
2. AI for Math Fund - open-source tools and datasets
3. Simons Foundation - long-term collaborations

---

## Quick Links

- 📊 [AI4Math Leaderboard](https://paperswithcode.com/task/automated-theorem-proving) - Papers with Code
- 📚 [DL4TP Survey](https://github.com/zhaoyu-li/DL4TP) - Deep Learning for Theorem Proving
- 🎓 [Formal Mathematical Reasoning](https://arxiv.org/abs/2412.16075) - Position paper on AI4Math
- 🏆 [IMO Grand Challenge](https://imo-grand-challenge.github.io/) - AI for IMO problems

**Funding**:
- 💰 [AI for Math Fund](https://www.renaissancephilanthropy.org/initiatives/ai-for-math-fund) - Up to $1M grants
- 🇺🇸 [NSF AIMing](https://www.nsf.gov/funding/opportunities/aiming-artificial-intelligence-formal-methods-mathematical) - $500K-$1.2M
- 🛡️ [DARPA expMath](https://www.darpa.mil/research/programs/expmath-exponential-mathematics) - Frontier research
- 🚀 [NSF SBIR/STTR](https://seedfund.nsf.gov/topics/artificial-intelligence/) - Startup funding

---

## Timeline: Key Milestones

| Date | Event |
|------|-------|
| Jul 2024 | AlphaProof achieves IMO silver medal |
| Jun 2024 | Harmonic AI launches with $75M Series A |
| Dec 2024 | AI for Math Fund launches ($9.2M) |
| Jul 2025 | Lean FRO receives $10M from Alex Gerko |
| Jul 2025 | Harmonic raises $100M Series B ($900M val) |
| Sep 2025 | Math Inc. completes Strong PNT in 3 weeks |
| Oct 2025 | Axiom Math emerges from stealth ($64M) |
| Nov 2025 | Harmonic raises $120M Series C ($1.45B val) |
| Nov 2025 | AlphaProof paper published in Nature |

---

## Tools & Platforms

<!-- TODO: Add more tools -->

## Learning Resources

### YouTube Channels

#### Mathematicians

- [Terence Tao](https://www.youtube.com/@TerenceTao27) - Fields Medalist on math and AI

#### Math Education

- [3Blue1Brown](https://www.youtube.com/@3blue1brown) - Beautiful math visualizations by Grant Sanderson
- [Numberphile](https://www.youtube.com/@numberphile) - Popular math content
- [Mathologer](https://www.youtube.com/@Mathologer) - Mathematical explanations
- [Stand-up Maths](https://www.youtube.com/@standupmaths) - Matt Parker's math entertainment

#### Academic Lectures

- [Oxford Mathematics](https://www.youtube.com/@OxUniMaths) - Oxford undergraduate lectures and public talks
- [Institute for Advanced Study](https://www.youtube.com/@InstituteforAdvancedStudy) - IAS talks
- [Fields Institute](https://www.youtube.com/@FieldsInstitute) - Mathematics conferences
- [Simons Institute](https://www.youtube.com/@SimonsInstituteTOC) - Theory of Computing lectures

### Seminars

- [Every Proof Assistant](https://math.andrej.com/category/every-proof-assistant/) - Survey of proof assistants, hosted by Andrej Bauer (Vimeo)
- [HOTTEST](https://www.uwo.ca/math/faculty/kapulkin/seminars/hottest.html) - HoTT Electronic Seminar Talks
- [Lean On Me](https://mathweb.ucsd.edu/~bechow/LeanOnMe/) - Lean online learning seminar organized by Ben Chow (UCSD) and Zilu Ma (UT Knoxville)

### Podcasts

- [Lex Fridman Podcast](https://www.youtube.com/@lexfridman) - Interviews with mathematicians like Terence Tao
- [The Joy of Why](https://www.quantamagazine.org/tag/the-joy-of-why/) - Steven Strogatz on Quanta Magazine

### Courses

<!-- TODO: Add courses -->

### Blogs & Newsletters

- [Xena Project](https://xenaproject.wordpress.com/) - Kevin Buzzard's blog on formalization
- [Lean Community Blog](https://leanprover-community.github.io/blog/) - Updates from the Lean community
- [Quanta Magazine](https://www.quantamagazine.org/mathematics/) - Quality math journalism

## Research & Papers

### Preprint Platforms

- [aiXiv](https://aixiv.science/) - Next-generation preprint server for AI scientists with multi-agent review system ([GitHub](https://github.com/aixiv-org/aiXiv))
- [arXiv](https://arxiv.org/) - Open-access preprint repository for scientific papers

### Landmark Papers

<!-- TODO: Add landmark papers -->

## Communities

- [Lean Zulip](https://leanprover.zulipchat.com/) - Official Lean community chat
- [Lean Discord](https://discord.gg/WZ9bs9siAv) - Lean community Discord server
- [Rocq Zulip](https://rocq-prover.zulipchat.com/) - Rocq (formerly Coq) community chat
- [Machine Learning for Theorem Proving](https://mlfortheoremproving.ai/) - Research community

## People

<!-- TODO: Add researchers and contributors -->

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first and use one resource per pull request.

## License

[MIT](LICENSE)

---

<p align="center">
  <sub>Curated with care by the community</sub>
</p>
