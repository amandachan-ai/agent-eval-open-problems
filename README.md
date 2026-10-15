# Five Hard Problems in Evaluating AI Agents: Working Notes

**Freeze the scenario and the success criteria, not the verbatim answer.**

Working notes for people who build LLM and agent evaluations. Each problem is laid
out as *common practice → where it falls short → better directions*, followed by a
tiering of what is solvable now, what needs trade-offs, and what needs new methods.

📖 **[Read the notes](https://amandachan-ai.github.io/agent-eval-open-problems/)**

---

## The five problems

| | |
|---|---|
| **1. Proactive agents** | Evaluate at the moment a message arrives, using only what existed then (as-of-T evaluation) |
| **2. Multi-turn interaction** | Static scenarios and criteria with dynamic dialogue; a frozen regression set plus an evolving capability pool |
| **3. Ground truth over large data** | Know the answer by construction: a fact ledger, provenance-checked gold, perturbation tests |
| **4. A prompt fix that breaks other cases** | Report per-case flips against an A/A noise baseline, not just the average |
| **5. A rigorous experiment, a mild improvement** | Estimate the ceiling first and validate the instrument before optimizing |

## About the examples

These are personal working notes, not the views of any employer or product team.
All examples are simplified or hypothetical, every number is an illustrative
assumption rather than a measurement from a real system, and no non-public data is
included.

## License

[CC BY 4.0](LICENSE) — Amanda Chan, 2026. Personal views; not those of any employer.
