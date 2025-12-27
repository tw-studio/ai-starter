# 01-planning.md

## Purpose of the Planning Directory

The directory:

    ./01-planning/

is a **shared working space** used to explore, think, experiment, and plan potential income-generating workstreams.

This repository is a **meta-project** focused on discovery and experimentation.  
It may later spawn separate projects, each of which may have their own planning systems.

The directories under `01-planning/` are **not stages in a pipeline**.  
They are **semantic zones** that reflect *how* a file is being used, not *where it sits in a process*.

The AI must respect these zones.

---

## General Behavioral Expectations

- Do not assume a linear workflow.
- Do not infer that files must move, be promoted, or be finalized.
- Work within the directory that best matches the current intent.
- Ask for clarification when unsure which directory to use.
- Prefer clarity and usefulness over formalism.

The human is always responsible for deciding what to work on and when.

---

## Directory Semantics

### 00-inbox/

**Intent:** Raw, uncurated material.

This directory may contain:
- Brain dumps
- Scratch notes
- Pasted research
- PDFs, images, exports
- Half-formed ideas
- External content copied in for reference

Rules:
- Files here are allowed to be messy.
- Files here are not assumed to be actionable.
- Files here are not expected to be refined or structured.
- Do not treat this directory as a backlog or task list.

The presence of a file here does **not** imply future action.

---

### 01-prompts/

**Intent:** Prompts that are worth keeping.

This directory is a **library of prompts the human found valuable**, regardless of origin or form.

It may contain:
- One-off conversational prompts that worked well
- Exploratory prompts
- Long, complex prompts
- Prompt fragments or drafts
- Prompt experiments

This directory may include:

  01-prompts/raw/

for raw or unpolished prompt material.

Rules:
- This is not a “best practices” or “reusable only” folder.
- Prompts do not need to be generalized or cleaned up.
- A prompt belongs here if the human wants to keep it.
- Do not remove or rewrite prompts unless instructed.

This directory exists for **reference and reuse by choice**, not enforcement.

---

### 02-project-definitions/

**Intent:** Foundational definition of the project as a whole.

This directory serves as the **project-wide definition homebase** for the entire workspace.

It is the first place where the human and AI collaborate to express:
- what this project *is*
- what it is trying to accomplish
- what problem space it inhabits
- what constraints, boundaries, or ambitions meaningfully define it

Unlike earlier directories, this is not raw input or freeform ideation.
Content here is expected to be **intentional, synthesized, and relatively concrete**, even if it later evolves.

This directory answers questions such as:
- What is the core idea of this project?
- What is the intended outcome or direction?
- What is in scope, and what is explicitly out of scope?
- What assumptions or premises does the project rest on?
- What does “success” roughly mean at a project level?

It may contain files such as (non-exhaustive examples):
- `project-definition.md`
- `vision.md`
- `north-star.md`
- `project-scope.md`
- `problem-space.md`
- `principles.md`
- `assumptions.md`

Rules and expectations:
- Files here define the **identity and boundaries of the project**, not individual features or ideas.
- Content should aim to be clear, explicit, and readable as a reference.
- Ambiguity is acceptable if it is named directly.
- Revisions are expected as understanding improves.
- These documents may represent a concrete plan or direction, but do not imply irreversible commitment.

Relationship to other directories:
- Inputs may draw from anything in `00-inbox/` and `01-prompts/`, but those directories remain unchanged.
- This directory establishes shared context for downstream work.
- `03-proposals/` may contain many alternative or competing proposals for parts of the project, all grounded in the definitions captured here.

This directory exists to make the project **legible, grounded, and discussable as a whole**.

---

### 03-proposals/

**Intent:** Concrete proposals for specific parts of the project.

This directory is used to capture **proposed ways forward** within the context established by `02-project-definitions/`.

While `02-project-definitions/` describes what the project *is* as a whole,  
`03-proposals/` explores **what could be done inside that project**.

This directory answers questions such as:
- What are viable ways to move this project forward?
- What features, initiatives, or business directions could exist?
- What are alternative approaches to solving a defined problem?
- What are different bets the project could place?

It may contain:
- Feature proposals
- Business model proposals
- Monetization approaches
- Technical approach proposals
- Go-to-market concepts
- Validation experiments
- Competing or mutually exclusive ideas

Rules and expectations:
- Proposals should be **specific enough to evaluate**.
- Multiple, competing proposals are expected and encouraged.
- Proposals do not need to agree with one another.
- A proposal does not imply selection, approval, or commitment.
- Proposals may vary in depth, from lightweight outlines to detailed documents.

Relationship to other directories:
- Proposals are grounded in the shared context defined in `02-project-definitions/`.
- Proposals may reference assumptions, goals, or constraints defined there.
- `03-proposals/` is intentionally expansive and exploratory.
- Selected or refined proposals may later inform work in `03-core-designs/`, `04-designs/`, or `05-execution-plans/`, but no automatic transition is implied.

This directory exists to make **options explicit**, comparable, and discussable.

---

### 04-core-designs/

**Intent:** Design for understanding.

This directory is used for **core design artifacts** whose primary purpose is to make an idea *easy to understand, reason about, and discuss*.

A core design captures the **essential design decisions, structure, and open questions** of an idea, without attempting to fully specify or implement it.

These documents are written for **fast, high-bandwidth comprehension** by an intelligent reader.

---

#### What a Core Design Is

A core design:
- expresses the key design choices being made
- surfaces important tradeoffs
- names assumptions explicitly
- identifies unresolved design questions
- provides a coherent mental model of the system or idea

A useful mental model for scope is:
> *“Something a smart reader can fully grok in a single sitting.”*  
(roughly a six-pager in spirit, not as a hard rule)

Core designs aim to answer:
- What is the shape of this thing?
- What are the most important decisions?
- What matters most, and why?
- Where are the risks or unknowns?
- What would need to be true for this to work?

---

#### What a Core Design Is Not

A core design is **not**:
- a full technical specification
- a task breakdown
- an implementation guide
- a document optimized for direct execution by an AI
- an exhaustive treatment of every edge case

Those belong elsewhere.

---

#### Relationship to Proposals

Core designs often draw from ideas captured in `03-proposals/`, but this is **not required**.

The separation between proposals and core designs is intentional:
- Proposals capture *possibilities*
- Core designs interrogate *viability and structure*

Multiple core designs may exist for:
- a single proposal
- variations of the same idea
- alternative interpretations of the same problem

Preserving both artifacts allows reasoning to evolve without erasing earlier thinking.

---

#### Typical Content

A core design may include:
- conceptual system diagrams (described in text)
- component breakdowns at a high level
- data or information flows
- key constraints
- assumptions and premises
- explicit tradeoffs
- open questions to be resolved later
- rationale for major design choices

Clarity and insight are valued more than completeness.

---

#### Expectations and Rules

- Documents should be concise and readable.
- Design decisions should be explicit.
- Open questions should be clearly labeled.
- Revisions are expected as understanding deepens.
- Do not overwrite prior work unless explicitly instructed.

---

#### Relationship to Other Directories

- Core designs may reference project definitions and proposals as inputs.
- Core designs often precede more detailed design work.
- More exhaustive, execution-oriented specifications belong in `05-designs/`.

This directory exists to make ideas **clear, debatable, and ready for deeper specification when appropriate**.

---

### 05-designs/

**Intent:** "Design for execution." Detailed thinking about *how* something could be built or operated.

This directory is used for **detailed design specifications** whose purpose is to enable precise, correct implementation.

Designs here are expected to be sufficiently detailed that:
- an AI could implement them directly, or
- a long, multi-step execution workflow could be driven from them with minimal ambiguity.

These documents prioritize **precision, completeness, and correctness** over brevity.

---

#### What Belongs Here

Design files in this directory may include:
- full technical specifications
- detailed architecture documents
- data schemas and models
- API contracts
- state machines
- edge cases and failure modes
- non-functional requirements
- explicit constraints and invariants

The goal is to remove interpretation wherever possible.

---

#### Relationship to Core Designs

Designs here often build on one or more documents from `04-core-designs/`, but this is not required.

The separation is intentional:
- `04-core-designs/` optimize for fast comprehension and reasoning
- `05-designs/` optimize for accurate execution

It is acceptable to have:
- multiple detailed designs for the same core design
- designs that supersede or refine earlier ones
- designs that are never implemented

Earlier artifacts should be preserved.

---

#### Expectations and Rules

- Ambiguity should be minimized or explicitly resolved.
- Open questions should be clearly identified if unavoidable.
- Assumptions should be stated, not implied.
- Designs may be long and detailed.
- Do not overwrite prior work unless explicitly instructed.

---

#### Relationship to Other Directories

- Designs here may inform execution plans in `06-execution-plans/`.
- This directory is not for task lists or progress tracking.
- This directory is not for exploratory ideation.

This directory exists to make implementation **possible, repeatable, and correct**.

---

### 06-execution-plans/

**Intent:** Explicit plans of action.

This directory may contain:
- Step-by-step plans
- Checklists
- Build plans (human or AI)
- Validation plans
- Short-term execution guides

Rules:
- Content here should be actionable and specific.
- Vague language should be avoided.
- Plans may still be abandoned or revised.

Presence here implies **intent to try**, not obligation to finish.

---

### 07-decisions/

**Intent:** Optional documentation of intentional choices.

Notes:
- This directory may be empty.
- Decisions are not required during exploration.
- If used, documents should capture *why* something was chosen or rejected.

Rules:
- Do not create decision documents unless explicitly instructed.
- If decision documents exist, respect them.
- Do not infer decisions that are not written.

---

### key-chats/

**Intent:** Preservation of important conversations.

This directory may contain:
- Chat transcripts
- Summaries of key discussions
- Reasoning worth keeping

Rules:
- Treat content as historical reference.
- Do not modify unless instructed.
- Do not extract tasks or plans automatically.

---

### dev-journal.md

**Intent:** Human-only personal working notes.

Rules:
- Do NOT edit.
- Do NOT reorganize.
- Do NOT summarize.
- Do NOT add tasks.
- Do NOT infer intent unless explicitly asked.

This file is outside the AI workflow.

---

## Default Guidance

When operating in this repository:

- Optimize for usefulness to the human.
- Avoid imposing process where none is desired.
- Treat structure as a support system, not a constraint.
- Exploration is the primary goal.
