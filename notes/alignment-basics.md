# Alignment Basics

Matching visual: [`alignment-objective-mismatch.svg`](../visuals/alignment/alignment-objective-mismatch.svg)

## Core Idea

Alignment is the problem of making a system's behavior reliably match intended goals, constraints, and human oversight. The visual shows a simple objective mismatch: a human intent is translated into a measurable proxy, the model optimizes the proxy, and the deployed behavior may miss the original intent.

## Source-Backed Claims

- Reward hacking and related objective failures are discussed in *Concrete Problems in AI Safety* as practical accident-risk problems. Source: `SRC-CONCRETE-AI-SAFETY-2016`.
- Specification gaming describes cases where a system satisfies the literal specification while failing the intended task. Source: `SRC-DEEPMIND-SPEC-GAMING`.
- Scalable supervision is hard when the objective is expensive or difficult to evaluate frequently. Source: `SRC-CONCRETE-AI-SAFETY-2016`.

## Claim Boundary

This visual is conceptual. It does not claim that all AI systems reward hack, that objective mismatch is always catastrophic, or that any specific deployed model is misaligned.

## Social Caption

Alignment problems often begin before deployment: intent gets compressed into a measurable proxy, and proxies can be easier to optimize than the thing people actually wanted.

Sources: Amodei et al. 2016; Google DeepMind on specification gaming.
