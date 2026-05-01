# MCAT Toy Framework: One-Page Conceptual Summary

## North Star

An MCAT toy is a small, interactive causal model that makes one scientific relationship visible, manipulable, memorable, and transferable to MCAT-style reasoning. The goal is not to make a game, a full lesson, or a beautiful simulation. The goal is to help me *feel the mechanism* well enough that I can predict, explain, and apply it.

A good toy turns this:

> "I kind of memorized this fact."

into this:

> "I can see why changing X causes Y."

The core design phrase is:

> **Show me how changing X causes Y through mechanism Z.**

---

## Core Philosophy

The project draws from explorable explanations, scientific visualization, constructionism, tools for thought, learning science, and MCAT-specific test preparation.

Key influences include Bret Victor-style explorable explanations, Nicky Case-style playful interactive learning, PhET-style scientific simulations, Papert/Kay/Resnick-style learning-by-making, Matuschak/Nielsen-style memory tools, and Niko McCarty-style visualization of biological mechanisms as inspectable systems.

The toy should make hidden science visible: gradients, flows, equilibria, forces, feedback loops, molecular transformations, graph shifts, and system bottlenecks.

The best toys are not broad. They are narrow and causal.

Bad request:

> "Make me a toy about the kidney."

Better request:

> "Make me a toy showing how increasing ADH changes water reabsorption and urine concentration."

---

## What Makes a Good MCAT Toy

Each toy should contain:

- **One concept**
- **One primary interaction**
- **One visible cause-effect relationship**
- **One misconception it repairs**
- **One MCAT-relevant takeaway**
- **One transfer question**
- **One explicit model-limits note**

The toy succeeds when I can predict what will happen before I press the button, move the slider, or run the animation.

The toy fails if it is visually impressive but conceptually noisy.

The toy may be simple or ugly. It may not be misleading.

---

## Learning Science Principles

Every toy should support active learning, not passive watching.

The basic loop should be:

1. **Prediction** - Before playing, I must predict what will happen.
2. **Interaction** - I manipulate the system and observe the result.
3. **Explanation** - I explain why the result happened.
4. **Misconception check** - The toy tests the wrong intuition I was likely to have.
5. **Transfer** - I answer an MCAT-style question using the same mechanism.
6. **Review decision** - The concept gets marked as mastered, shaky, or needing repair.

This matters because understanding is not just recognition. I need to know whether I can retrieve, explain, and transfer the idea.

---

## MCAT Scope Rules

The toy should be accurate at the MCAT level, not exhaustive at the graduate level.

Every toy should ask:

> Is this detail must-know, useful support, low-yield enrichment, or distracting?

The AAMC scope should act as the boundary. Advanced details can be included only if clearly labeled as optional or outside the main model.

A simplified toy must always include a model-limits note.

Example:

> "This toy compresses IDL formation and apolipoprotein details so you can focus on the VLDL -> LDL cargo/density relationship."

This keeps simplification from becoming misinformation.

---

## Toy Types

Most MCAT toys will fall into a few families:

- **Flow toys** - blood flow, nephron flow, electron flow, metabolic flow.
- **Gradient toys** - diffusion, osmosis, membrane potential, proton gradients.
- **Saturation toys** - enzyme kinetics, receptor saturation, transport maximum.
- **Equilibrium/balance toys** - buffers, Le Chatelier, Starling forces.
- **Sequence toys** - ETC, action potentials, muscle contraction, translation.
- **Sorting toys** - LDL/VLDL/HDL, hormone classes, immune cells.
- **Graph toys** - inhibition curves, titrations, binding curves.
- **Passage-transfer toys** - applying a mechanism to an unfamiliar MCAT-style setup.

Not every topic deserves a toy. Some facts are better handled by Anki, mnemonics, or simple quizzes. Toys are best for causal, spatial, dynamic, or graph-based confusion.

---

## The Most Important Prompt Fields

When asking for a toy, I should provide or ask the AI to infer:

```text
Concept:
What I'm studying.

My confusion:
What I keep mixing up.

Wrong mental model:
The incorrect intuition I may have.

Correct causal model:
When X changes, Y changes because Z.

Toy type:
Flow, gradient, saturation, equilibrium, sequence, sorting, graph, or passage-transfer.

Desired interaction:
Slider, toggle, drag, button, step-through animation, sorting task, or graph manipulation.

MCAT scope:
What must be included and what should be avoided.

Output:
Design spec, Codex prompt, actual code, quiz questions, or explanation.
```
