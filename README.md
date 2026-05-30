# AI Safety Visuals

Evidence-first visual explainers for AI safety, evaluation, robustness, and intelligent systems.

This repository is a visual knowledge base for explaining AI safety without hype. It collects source-backed diagrams, markdown explainers, reusable social graphics, and visual notes about alignment, frontier risk frameworks, job exposure, evaluation, monitoring, and perception robustness.

Related project: [SIGNALWATCH](https://jgsops.dev)

## What This Is

- A public library of SVG-first explainers for AI safety and robustness.
- A source-backed reference for turning complex technical ideas into calm, readable visuals.
- A reusable asset base for GitHub, LinkedIn, X, talks, and educational writing.
- A place to separate conceptual diagrams from measured evidence.

## What This Is Not

- Not a web app.
- Not a dashboard.
- Not an AI wrapper.
- Not a prediction engine.
- Not a collection of fabricated statistics, unsourced timelines, or fake charts.

## Visual Collections

| Collection | Focus | Initial asset |
| --- | --- | --- |
| Alignment Basics | Objective mismatch, proxy goals, reward hacking, oversight difficulty | [`alignment-objective-mismatch.svg`](visuals/alignment/alignment-objective-mismatch.svg) |
| Capability vs Alignment | Why evaluation and monitoring pressure rises as systems become more capable | [`capability-vs-alignment-gap.svg`](visuals/capability-vs-alignment/capability-vs-alignment-gap.svg) |
| Job Displacement & Task Exposure | Task automation versus full job replacement, transition risk, reskilling pressure | [`task-automation-vs-job-replacement.svg`](visuals/job-displacement/task-automation-vs-job-replacement.svg) |
| Evaluation & Monitoring | Limits of pre-deployment benchmarks, post-deployment monitoring, red teaming | [`evaluation-after-deployment.svg`](visuals/evaluation/evaluation-after-deployment.svg) |
| Perception Robustness | Low light, blur, occlusion, confidence collapse, temporal inconsistency | [`perception-failure-modes.svg`](visuals/perception-robustness/perception-failure-modes.svg) |
| AI Safety Timeline | Source-backed milestones only | Planned |

## Source Policy

Every factual claim must be traceable to a source in [`sources/sources.md`](sources/sources.md) or clearly marked as a conceptual explanation.

Rules:

- No fabricated statistics.
- No invented timelines.
- No fake expert quotes.
- No misleading charts.
- No claim should imply measurement when the visual is conceptual.
- If a source is uncertain, unavailable, or contested, the visual should say so rather than fill the gap.

Preferred source types:

- Official safety frameworks and standards.
- Government or intergovernmental reports.
- Research papers directly relevant to the concept.
- Evaluation organizations with public methodology.
- Primary source documentation where possible.

## How To Use

Use the SVGs directly in posts, decks, README files, and essays. For raster export, open the SVG in a vector editor or browser and export to PNG at 2x or 3x scale.

Suggested workflows:

- Use the visual as the first slide or social card.
- Link the matching note as the evidence trail.
- Keep captions short and source-aware.
- When editing, preserve the source footer and avoid adding unsourced numbers.

## Initial Explainers

- [`notes/alignment-basics.md`](notes/alignment-basics.md)
- [`notes/capability-vs-alignment.md`](notes/capability-vs-alignment.md)
- [`notes/job-displacement.md`](notes/job-displacement.md)
- [`notes/evaluation-monitoring.md`](notes/evaluation-monitoring.md)
- [`notes/perception-robustness.md`](notes/perception-robustness.md)

## Social Post Copy

Reusable LinkedIn/X copy examples are in [`templates/social-post-copy.md`](templates/social-post-copy.md). The copy is written to avoid unsupported claims and to point readers back to sources.

## Roadmap

- Add a source-backed AI safety timeline.
- Add PNG exports for each visual.
- Add framework comparison cards for OpenAI, Anthropic, NIST, and other public frontier AI safety frameworks.
- Add visual notes on red teaming, benchmark leakage, distribution shift, and model observability.
- Add export guidance for LinkedIn carousel and X image formats.
- Add alt text files for accessibility and reuse.

## License And Attribution

The repository content is intended for reuse with attribution. See [`LICENSE`](LICENSE) and [`ATTRIBUTION.md`](ATTRIBUTION.md).

When reusing a visual, credit:

> AI Safety Visuals, source-backed visual explainers for AI safety and robustness.

Do not imply that source organizations endorse these visuals unless they have explicitly done so.
