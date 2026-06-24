# SDLC in the AI Age

**Status:** Living integrated position — June 23, 2026

## Core Premise

The core problem with today’s AI-augmented SDLC is **human fallibility**. Even experienced teams introduce variability and defects through communication issues, memory limitations, temperament, energy levels, focus, diligence, and attention. These human variables are difficult to diagnose and correct in real time. There is no reliable diagnostic that can be run on a person to identify and fix what is broken.

The framework addresses this by shifting as much consistency and rigor as possible into digital instructions, scripts, and structured adversarial processes that do not suffer from the same variability.

Because AI can now generate substantial volumes of code and implementation work extremely quickly, the traditional SDLC bottleneck has inverted. The highest-leverage human work is no longer primarily in authoring or testing code. It is in **rigorously defining the problem, the desired solution, hard constraints, security and policy requirements, approved tooling, environment characteristics, and success criteria before any significant generation begins**.

## Generation Model: Stateless Adversarial + Builder Loops

Generation should occur inside tightly controlled **stateless adversarial + builder loops**. Both the adversarial checker and the builder operate with **fresh context on every pass** and receive only the governing documents, goals, and constraints. This design prevents context accumulation, poisoning, anchoring, and other biases that degrade output quality during long sessions.

The adversarial system uses two coordinated functions:

- One function focuses on clearly defining and pressure-testing the problem set, desired outcomes, and constraints. This creates the rubric.
- The second function measures generated artifacts against that rubric. It flags what contributes to the goal, what is deviating from it, and what required elements are missing.

These two functions do not conflict because the definition function sets the standard against which the measurement function operates.

## Core Operating Principles

- **Determinism First**: Explicitly prefer deterministic, auditable solutions over probabilistic AI wherever they are sufficient (“never send a model to do a script’s job”).
- **Right-Sized Models**: When AI is used, decompose large problems into smaller, well-scoped problems matched to appropriately capable models operating under strict, well-designed constraints. A weaker model in a tightly constrained environment is often preferable to a stronger model given excessive freedom.
- **Realistic AI Understanding**: The framework must begin with a realistic understanding of what current AI systems actually are — their strengths, failure modes, non-determinism, and limitations — rather than treating them as generally capable.
- **AI-Assisted Constraint Definition**: AI can be used during the planning phase to help surface and refine its own operating parameters and constraints, but final governance decisions remain human.

## Human Role and Environment Setup

With this environment properly established (governing documents, constraint sets, approved patterns, and tooling decisions), a meaningful portion of ongoing verification and coordination effort shifts toward **setting up and maintaining that environment** rather than reviewing every generated artifact in detail. Human verification load is concentrated on establishing the physical and digital environment that AI cannot create or maintain on its own.

## Handling Divergence and Reusability

When projects diverge significantly, the framework starts fresh with the new goals and constraints rather than carrying over potentially misaligned prior work. However, because substantial work on constraint definition, approved patterns, and aligned checker/builder behavior already exists, the system can operate faster on the new problem than starting from zero.

Reusability is assessed by measuring new data, resources, or patterns against the current problem set, goals, and constraints. Alignment is treated as largely binary: if it aligns, it can be leveraged; if it does not align, it is discarded or adjusted.

## Stated Goal of the Framework

The framework does not claim to make AI augmentation infallible. That would be a farce. Its purpose is to **drastically reduce the recurring problems** that appear in current AI-augmented development — late clarification, high volumes of post-generation rework, weak constraint enforcement, context poisoning, and high coordination cost caused by human variability.

Because orchestrators and swarms are already being used to build functional applications in minutes, the reduction in required team size per product is observable in practice. While a strict 1-2 person model may be a stretch for some classes of work, the framework does not require a full traditional team per product.

## Acknowledgment of Uncertainty

We are in uncharted territory. Strong longitudinal data on reusability ratios, sustainable team sizes, and long-term outcomes does not yet exist. The fact that rigorous questions remain instead of settled answers is evidence that we are still in the discovery and refinement phase rather than the confident measurement phase.

The framework itself is designed to accelerate that discovery through continuous adversarial pressure on the governing information.

## Avoidance of Waterfall Rigidity

The overall approach avoids waterfall rigidity because the plan is continuously honed through adversarial feedback loops that keep the evolving work aligned with original intent. This resembles a human-in-the-reinforcement-learning loop, where the adversarial function acts as the critic that prevents drift while the builder function executes within the current constraints.

---

*This document represents the current integrated position and will be updated as the framework is further refined.*