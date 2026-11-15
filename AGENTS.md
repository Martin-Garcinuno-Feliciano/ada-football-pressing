
# Project: Football Pressing Analysis

## Objective
Individual Advanced Data Analysis (HEC Lausanne, 2026) research project investigating whether pressing characteristics predict subsequent ball recovery using StatsBomb Open Data (Euro 2020, World Cup 2022, Euro 2024).

## Working principles
- Prioritise statistical validity, reproducibility, clarity and simplicity.
- Do not invent data, results, research definitions or modelling decisions.
- Treat the observation unit, successful recovery definition, prediction horizon and feature set as undecided until explicitly approved.
- Prevent target leakage: predictors must be available at the specified prediction moment.
- Consider match-level dependence and grouped evaluation.
- Prefer a simple, interpretable baseline before more advanced models.

## Code conventions
- Use Python and clear, readable code.
- Keep separate stages for data acquisition, cleaning, modelling, evaluation and figures.
- Put reusable functions in Python modules rather than duplicating code across notebooks.
- Use relative file paths, explicit random seeds and documented dependencies.
- Each notebook must run top-to-bottom from a fresh kernel.
- Add appropriate tests, especially for outcome labels and temporal logic.
- Do not introduce unnecessary frameworks or infrastructure.

## Data and reproducibility
- Preserve provenance and document cleaning decisions.
- Do not publish raw data without confirming licence and redistribution permissions.
- Keep secrets, environments, caches and editor settings out of Git.
- Ensure the complete analysis can run within the provided Nuvolos workspace.
- Generate every reported figure and table through code in the repository.

## Collaboration with Codex
- Before a substantial edit, explain the proposed approach and affected files.
- Make focused changes; do not silently expand scope.
- Do not install packages, delete data, create commits or push to GitHub unless explicitly requested.
- After changes, describe what changed, what was tested and any unresolved issues.
- Document AI-generated code and its purpose so it can be attributed in the paper's required tools appendix.

## Academic constraints
- Follow the course Requirements document over the nonbinding Shipping Guidelines.
- The project is individual; the student must understand and be able to explain all submitted work.
- The final deliverables include a reproducible public GitHub repository, SIAM-format research paper and approximately 15-minute recording.
- Substantive project work requires the teaching assistant's written proposal approval.
  