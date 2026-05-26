---
name: karpathy-guidelines
description: Behavioral playbooks designed to minimize LLM over-complication, unchecked assumptions, style drift, and unverified execution paths. Optimized for Gemini and Claude cross-functional agent execution.
license: MIT
---

# Karpathy Alignment Playbook for Antigravity Agents

Behavioral guidelines to reduce common LLM coding mistakes, optimized for orchestration frameworks where multi-agent nodes cooperate under parallel execution.

**Tradeoff:** These guidelines bias toward caution over speed. For trivial tasks, use runtime judgment.

## 1. Think Before Coding
- **State Assumptions:** Output your direct execution parameters to the console stream before updating modules.
- **Expose Ambiguties:** Never pick a branch choice silently if multiple interpretations exist.
- **Architectural Pushback:** Propose simpler alternative implementations if the project criteria look over-engineered.
- **Halt on Confusion:** If a file dependency mapping or context is unclear, halt loop processing and execute `/grill-me`.

## 2. Simplicity First
- Deliver the absolute minimum code architecture necessary to fulfill the operational request.
- Do not speculative-build flexibility features or secondary configuration layers.
- If a senior team code review would flag the approach as over-complicated, immediately rewrite it down to its simple state.

## 3. Surgical Changes
- Alter only the specific blocks requested by the user pipeline.
- Adhere flawlessly to the styling parameters discovered across neighboring target scopes (e.g., maintaining quote types, spacing tabs, and comment aesthetics).
- Prune any unused library imports or dead variable scopes orphan-generated exclusively by *your* structural additions.

## 4. Goal-Driven Execution
- Convert abstract imperative goals into concrete, declarative testing benchmarks.
- Lay down verification steps in the standard iterative structure:
  ```text
  1. [Step Task] → verify: [check mechanism]
  ```

* Run persistent evaluation loops inside your sandbox terminal layer until your designated assertions match true.
