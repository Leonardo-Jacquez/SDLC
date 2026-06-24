# SDLC in the AI Age

**Status:** Living integrated position — June 24, 2026

## Core Premise

The core problem with today’s AI-augmented SDLC is **human fallibility**. Even experienced teams introduce variability and defects through communication issues, memory limitations, temperament, energy levels, focus, diligence, and attention. These human variables are difficult to diagnose and correct in real time. There is no reliable diagnostic that can be run on a person to identify and fix what is broken.

The framework addresses this by shifting as much consistency and rigor as possible into digital instructions, scripts, and structured adversarial processes that do not suffer from the same variability.

Because AI can now generate substantial volumes of code and implementation work extremely quickly, the traditional SDLC bottleneck has inverted. The highest-leverage human work is no longer primarily in authoring or testing code. It is in **rigorously defining the problem, the desired solution, hard constraints, security and policy requirements, approved tooling, environment characteristics, and success criteria before any significant generation begins**.

## Generation Model: Stateless Adversarial + Builder Loops

Generation should occur inside tightly controlled **stateless adversarial + builder loops**. Both the adversarial checker and the builder operate with **fresh context on every pass** and receive only the governing documents, goals, and constraints. Stateless means context from previous interactions is dropped — it does not mean the agents operate without instructions. The first instruction is always to read the current build plan, which contains all information relevant to the desired outcome.

The adversarial system uses two coordinated functions:

- One function focuses on clearly defining and pressure-testing the problem set, desired outcomes, and constraints. This creates the rubric.
- The second function measures generated artifacts against that rubric. It flags what contributes to the goal, what is deviating from it, and what required elements are missing.

The planning checker is responsible for building the artifact checker with specific alignment criteria derived from the rubric. Because both functions ultimately reference the same concrete, unchanging source data and the same rubric, they remain in alignment by design rather than by ongoing negotiation.

## Core Operating Principles

- **Determinism First**: Explicitly prefer deterministic, auditable solutions over probabilistic AI wherever they are sufficient (“never send a model to do a script’s job”).
- **Right-Sized Models**: When AI is used, decompose large problems into smaller, well-scoped problems matched to appropriately capable models operating under strict, well-designed constraints. A weaker model in a tightly constrained environment is often preferable to a stronger model given excessive freedom.
- **Realistic AI Understanding**: The framework must begin with a realistic understanding of what current AI systems actually are — their strengths, failure modes, non-determinism, and limitations — rather than treating them as generally capable.
- **AI-Assisted Constraint Definition**: AI can be used during the planning phase to help surface and refine its own operating parameters and constraints, but final governance decisions remain human.
- **Input Rigor Over Output Flexibility**: All major surfaces for misalignment (security, performance, data modeling, operational characteristics, compliance, etc.) must undergo the same rigorous definition and sharpening as the overall plan. Breaking big problems into smaller, well-scoped problems with tight constraints reduces downstream output headaches. It is preferable to be rigorous with the input than to be forced into flexibility with the output.

## Human Role and Environment Setup

With this environment properly established (governing documents, constraint sets, approved patterns, and tooling decisions), a meaningful portion of ongoing verification and coordination effort shifts toward **setting up and maintaining that environment** rather than reviewing every generated artifact in detail. Human verification load is concentrated on establishing the physical and digital environment that AI cannot create or maintain on its own.

## Handling Divergence and Reusability

When projects diverge significantly, the framework does not blindly carry over prior work. It starts by refining the build guide with the new goals, constraints, and desired outcomes. A new build plan is then defined in accordance with the updated build guide and available tooling. At that point, a deliberate decision is made whether to adjust the existing product or start fresh. Even in cases of significant divergence, many plan-agnostic pieces and processes (constraint definition discipline, stateless loop structure, rubric-based checking, and approved tooling patterns) remain reusable and allow the new effort to move faster than starting from zero.

Reusability is assessed by measuring new data, resources, or patterns against the current problem set, goals, and constraints. Alignment is treated as largely binary against the defined rubric: if it aligns, it can be leveraged; if it does not align, it is discarded or adjusted.

## Stated Goal of the Framework

The framework does not claim to make AI augmentation infallible. That would be a farce. Its purpose is to **drastically reduce the recurring problems** that appear in current AI-augmented development — late clarification, high volumes of post-generation rework, weak constraint enforcement, context poisoning, and high coordination cost caused by human variability.

Because orchestrators and swarms operating inside well-structured environments can already take a product from nothing to functional MVP in a single sitting (something that traditionally takes teams months or years), the reduction in required team size and calendar time per product is directly observable. While a strict 1-2 person model may be a stretch for some classes of work, the framework does not require a full traditional team per product.

## Acknowledgment of Uncertainty

We are in uncharted territory. Strong longitudinal data on reusability ratios, sustainable team sizes, and long-term outcomes does not yet exist. The fact that rigorous questions remain instead of settled answers is evidence that we are still in the discovery and refinement phase rather than the confident measurement phase.

The framework itself is designed to accelerate that discovery through continuous adversarial pressure on the governing information.

## Avoidance of Waterfall Rigidity

The overall approach avoids waterfall rigidity because the plan is continuously honed through adversarial feedback loops that keep the evolving work aligned with original intent. Drift is further mitigated through proven non-human systems such as version-controlled repositories and structured layering approaches. The rubric, once given proper rigor, functions as the “word of law” — it is stable by design and only changed through deliberate, high-friction updates rather than casual drift.

---

*This document represents the current integrated position and will be updated as the framework is further refined.*