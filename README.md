# IB DP Geography Skills

Reusable [Agent Skills](https://agentskills.io/specification) for IB Diploma Programme Geography.

Four skills for the SL and HL Geography syllabus for first assessment in 2019, using the guide updated in November 2022. The paper skills use question-specific markschemes where available and include the guide's general essay bands in summarized form. The IA skill covers local fieldwork design, report planning and writing, and independent marking against criteria A–F.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1](.agents/skills/ib-geography-paper-1/SKILL.md) | “Geo Paper 1 — mark this Urban environments 10-mark essay.” | `$ib-geography-paper-1` |
| [Paper 2](.agents/skills/ib-geography-paper-2/SKILL.md) | “Geo Paper 2 — give feedback on my Section B answers using this map.” | `$ib-geography-paper-2` |
| [Paper 3 · HL](.agents/skills/ib-geography-paper-3/SKILL.md) | “Geo Paper 3 — plan my part (b) response on global networks.” | `$ib-geography-paper-3` |
| [Internal assessment](.agents/skills/ib-geography-ia/SKILL.md) | “Geo IA — help me turn my field measurements into a report plan.” | `$ib-geography-ia` |

## Install in Codex

Clone or download this repository and open it as a Codex workspace. Codex discovers the skill folders under `.agents/skills` within the workspace. To use a skill across projects, copy its entire folder, including `references/`, into `~/.agents/skills/`. For another Agent Skills-compatible host, follow that host's installation instructions.

The assessment names in the skill descriptions help a compatible agent choose the relevant skill from an ordinary prompt. Automatic selection depends on the host and prompt context. Use the explicit invocation in Codex when you want to select a specific skill. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

## Sources

This independent study resource uses the IB *Geography guide*, first assessment 2019, updated November 2022. The references give the guide's page numbers and paraphrase its bands and criteria. For exact question-level allocations, use the markscheme for the relevant exam session and paper version. [IB Geography overview](https://www.ibo.org/programmes/diploma-programme/curriculum/individuals-and-societies/geography/) · [IB specimen papers and markschemes](https://www.ibo.org/programmes/diploma-programme/assessment-and-exams/sample-exam-papers/)

The original material in this repository is available under the [MIT License](LICENSE).
