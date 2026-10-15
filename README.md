# Hi, I'm Anurag 👋

I'm an AI product manager. I lead teams that ship AI products, and I build the Claude workflows my own product work runs on.

Most of my work starts the same way: a release decision that a demo can't settle. I build the smallest version that can answer it, test it against a fixed set of cases, and write the release rule down before I see the result. The parts worth sharing end up here as small repos you can run.

## Start here: three repos you can run in 30 seconds

Each runs offline with Python 3.10 or newer, no packages and no API key.

| Repo | What it shows |
|---|---|
| [**ai-product-evals**](https://github.com/aragjha/ai-product-evals) | Should the new prompt ship? A written release rule says HOLD, and why. |
| [**claude-pm-os**](https://github.com/aragjha/claude-pm-os) | Meeting notes to brief, tickets, QA checklist and release note, with a human gate at each step. |
| [**clinical-extraction-lab**](https://github.com/aragjha/clinical-extraction-lab) | Every extracted decision points at its evidence; doubtful items go to a reviewer. Synthetic notes. |

Results in these repos are labelled **fixture**: produced by a deterministic stand in, not a language model, so anyone can reproduce them for free. Live Claude runs are built and tested but not run yet; each README says so.

## Lately, I've been working on

- Claude Code agents that turn meeting notes into tickets and tickets into prototypes, with my review before anything reaches Jira
- Eval sets and release rules for LLM features: what counts as a pass is decided before the run, not after
- Evidence first extraction, where every answer points at the sentence it came from and doubtful ones go to a person
- [**prodman-stack**](https://github.com/aragjha/prodman-stack), an open source Claude Code toolkit for product managers: 15 skill packs and 56 workflows behind one `/pm` command
- Prototyping inside the product's real codebase, so engineers start from working software instead of a mockup

Everything here is built to be cloned, run and pulled apart. None of it contains employer code, data or prompts.

## Selected work, with evidence

- **NeuroAudit**, an LLM platform for reviewing clinical records (previously NeuroValidate). I built the prototype and lead the product. 2.5M records processed and 23K+ decisions signed by human reviewers. *Measured: production database, all time to Jul 2026; a record is one clinical note, a decision is one item a reviewer accepted or changed.*
- **NeuroTerminal** (previously Neuro360). My 12 day prototype shaped its query experience; the product launched publicly on 19 May 2026, and launch credit belongs to the team. *Measured: prototype repository, 18 to 30 Apr 2026; company press release.*
- **Neura**, a health diary app: v1.0 on the App Store on 3 Sep 2026, built by two people. *Measured: public App Store listing and repository history.*

*Measured* means counted from a system of record or a public listing. I publish no accuracy figure unless each prediction was checked against its own correct answer. These numbers describe my work, not the repos above.

## A bit about me

- **Director of Product Management** at NeuroDiscovery AI, where I own strategy and the roadmap for six AI products and lead the product managers, designers and engineers who build them.
- Six years in product across health, fintech, automotive, education and gaming. Before this: Senior Product Manager at Jivi AI, then Yocket, Spyne AI and OLX Autos. Details at [aragjha.com](https://aragjha.com).

If you're hiring for AI product work, or deciding whether an LLM feature is ready to ship, reach out: aragjha@gmail.com · [LinkedIn](https://www.linkedin.com/in/jha-anurag/) · [Resume](https://aragjha.com/Anurag_Jha_Resume.pdf)

Or pick a repo and try to break its release rule. If you manage it, open an issue.
