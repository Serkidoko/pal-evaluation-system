# PAL Agent Harness Eval Proposal

Technical GitHub Pages report for evaluating PAL's harness across arbitrary user-created agents, multi-agent systems, and workflows.

The report contains:

- a five-dimension evaluation taxonomy without an invented composite score;
- twelve platform-core harness controls;
- task routing for arbitrary custom configurations;
- rule-based, model-based, and human grader design;
- a matched regression protocol;
- a ten-task, five-dimension scorecard rechecked directly in PAL, covering seven of eight capability packs and explicitly excluding untested external actions;
- exact PAL run links, grader rules, units, explicit unknowns, and a public `evidence.json` artifact;
- operational metric formulas and missing-data rules;
- a required per-trial evidence record and validity gates;
- platform-core, capability-pack, journey, incident, and private-holdout suite layers.

Current decision: **HOLD / NOT RATEABLE AS A GENERAL PAL HARNESS** because permission enforcement, pause/resume reliability, cancellation, recovery, platform approval, idempotency, and broader isolation remain unverified or incomplete.
