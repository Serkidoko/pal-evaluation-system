# PAL Agent Harness Eval Proposal

Technical GitHub Pages report for evaluating PAL's harness across arbitrary user-created agents, multi-agent systems, and workflows.

The report contains:

- a five-dimension evaluation taxonomy without an invented composite score;
- twelve platform-core harness controls;
- task routing for arbitrary custom configurations;
- rule-based, model-based, and human grader design;
- a matched regression protocol;
- a ten-task-family observed sample rechecked directly in PAL, including multi-agent delegation and invalid-URL failure handling;
- exact PAL run links, grader rules, units, explicit unknowns, and a public `evidence.json` artifact;
- operational metric formulas and missing-data rules;
- platform-core, capability-pack, journey, incident, and private-holdout suite layers.

Current decision: **HOLD / NOT RATEABLE AS A GENERAL PAL HARNESS** because cancellation, recovery, platform approval, idempotency, and broader isolation remain untested.
