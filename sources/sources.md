# Source Registry

This registry is the evidence base for the visuals and notes in this repository. Use source IDs in notes and SVG footers when a visual relies on a specific factual claim.

## Core Frameworks And Reports

### SRC-OPENAI-PREPAREDNESS-2025

- Title: OpenAI Preparedness Framework, Version 2
- Publisher: OpenAI
- Date: 2025-04-15
- URL: https://cdn.openai.com/pdf/18a02b5d-6b67-4cec-ab64-68cdfbddebcd/preparedness-framework-v2.pdf
- Used for: Frontier capability categories, capability thresholds, safeguards, evaluation before deployment, and risk governance language.
- Claim boundary: Use only for OpenAI's stated framework. Do not present it as a universal industry standard.

### SRC-ANTHROPIC-RSP-UPDATED

- Title: Announcing our updated Responsible Scaling Policy
- Publisher: Anthropic
- URL: https://www.anthropic.com/news/announcing-our-updated-responsible-scaling-policy
- Used for: Responsible Scaling Policy framing, AI Safety Levels, catastrophic risk governance, safeguards linked to model capability.
- Claim boundary: Use only for Anthropic's public policy framing. Do not infer model-specific safety performance.

### SRC-NIST-AI-RMF-1

- Title: Artificial Intelligence Risk Management Framework (AI RMF 1.0)
- Publisher: National Institute of Standards and Technology
- Date: 2023-01-26
- URL: https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10
- Used for: AI risk management functions, governance vocabulary, mapping/measurement/management framing.
- Claim boundary: NIST AI RMF is voluntary guidance, not a guarantee of safe deployment.

### SRC-STANFORD-AI-INDEX

- Title: AI Index Report
- Publisher: Stanford HAI
- URL: https://hai.stanford.edu/ai-index
- Used for: Broad AI trend context, adoption, research, performance, policy, and ecosystem reporting when citing a specific report year.
- Claim boundary: Use exact year and metric when citing a specific chart or statistic.

### SRC-OECD-AI-WORK

- Title: AI and Work
- Publisher: OECD
- URL: https://www.oecd.org/en/topics/ai-and-work.html
- Used for: Occupational exposure, task-based labor framing, skills, productivity, and labor market transition context.
- Claim boundary: Exposure is not the same as automatic job loss.

### SRC-INTL-AI-SAFETY-REPORT-2025

- Title: International AI Safety Report 2025
- Publisher: International AI Safety Report
- Date: 2025-01-29
- URL: https://internationalaisafetyreport.org/publication/international-ai-safety-report-2025
- Used for: General-purpose AI capabilities and risks, scientific consensus framing, uncertainty and evidence boundaries.
- Claim boundary: Avoid compressing nuanced risk discussion into deterministic claims.

## Alignment And Evaluation

### SRC-CONCRETE-AI-SAFETY-2016

- Title: Concrete Problems in AI Safety
- Authors: Dario Amodei, Chris Olah, Jacob Steinhardt, Paul Christiano, John Schulman, Dan Mane
- Date: 2016
- URL: https://arxiv.org/abs/1606.06565
- Used for: Reward hacking, scalable supervision, safe exploration, distributional shift, accident risk.
- Claim boundary: This is a research framing, not a claim that every system exhibits every failure mode.

### SRC-DEEPMIND-SPEC-GAMING

- Title: Specification gaming: the flip side of AI ingenuity
- Publisher: Google DeepMind
- URL: https://deepmind.google/blog/specification-gaming-the-flip-side-of-ai-ingenuity/
- Used for: Specification gaming and objective proxy failure examples.
- Claim boundary: Use examples as illustrations of failure modes, not as universal behavior claims.

### SRC-METR-LONG-TASKS

- Title: Measuring AI Ability to Complete Long Software Tasks
- Publisher: METR
- URL: https://metr.org/index.html
- Related paper: https://arxiv.org/abs/2503.14499
- Used for: Capability evaluation as task-completion measurement and long software-task capability framing.
- Claim boundary: Do not reproduce trend numbers or forecasts unless citing the paper directly and preserving caveats.

## Perception Robustness

### SRC-IMAGENET-C

- Title: Benchmarking Neural Network Robustness to Common Corruptions and Perturbations
- Authors: Dan Hendrycks and Thomas Dietterich
- Date: 2019
- URL: https://arxiv.org/abs/1903.12261
- Used for: Common corruption robustness, blur/noise/weather/digital corruption categories, safety-critical robustness framing.
- Claim boundary: ImageNet-C concerns benchmarked image classification corruptions; do not overstate it as proof about all deployed perception systems.

## Related Project

### SRC-SIGNALWATCH

- Title: SIGNALWATCH
- URL: https://jgsops.dev
- Used for: Related project link and evidence-first observability positioning.
- Claim boundary: Related project, not a source for external AI safety claims unless a specific page and claim are cited.

## Citation Practice

When adding a new visual:

1. Add the source here first.
2. Write the claim in plain English.
3. Mark whether the visual is conceptual, source-derived, or measured.
4. Avoid chart axes unless the values come from a named dataset or report.
5. Add the source ID to the SVG footer and matching note.
