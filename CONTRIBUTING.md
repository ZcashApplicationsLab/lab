# Contributing to Zcash Applications Lab

> **Heads up:** ZAL is an early, unfunded community experiment. It is not affiliated with ZF, ZCG, Shielded Labs, or ZOLD, and nothing here is a commitment to pay anyone for their time. Contributions are volunteer and open-source. If that is fine by you, read on.

Thanks for your interest. The lab runs as a continuous, open-source hackathon, and there are a few ways to plug in.

## Ways to contribute

| I want to…                                     | Do this                                                                                                              |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Drop a rough idea (no prep needed)             | Open an [Idea](https://github.com/ZcashApplicationsLab/lab/issues/new?template=idea.yml)                             |
| Propose a scoped sprint (ready to lead it)     | Open a [Sprint Proposal](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-proposal.yml)        |
| Join an active sprint                          | Comment on the sprint's issue; leads will respond                                                                    |
| Review sprints                                 | Open a [Discussion](https://github.com/ZcashApplicationsLab/lab/discussions) describing your domain and availability |
| Mentor                                         | Same as above                                                                                                        |
| Improve this repo's docs, rubric, or templates | Open a PR against `main`                                                                                             |
| Surface a rough idea for someone else to run   | Open an [Idea](https://github.com/ZcashApplicationsLab/lab/issues/new?template=idea.yml)                             |
| Report a security issue                        | Email the maintainers listed in `SECURITY.md` (coming soon). Do not open a public issue.                             |

## Two ways to bring an idea

Not sure if your thought is ready for a full proposal? It probably is not, and that is fine.

- **Idea.** One or two sentences, no jargon, no homework. Use it when you have a hunch but have not scoped it, or when you want someone else to run with it. [Open an Idea](https://github.com/ZcashApplicationsLab/lab/issues/new?template=idea.yml).
- **Sprint Proposal.** Scoped, you (or your team) plan to lead it, you can commit 2 to 4 weeks. [Open a Sprint Proposal](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-proposal.yml).

If you are not sure which fits, pick Idea. A maintainer will help you shape it.

## Sprint proposals

Before opening a proposal:

1. Skim [open ideas and proposals](https://github.com/ZcashApplicationsLab/lab/issues) so you are not duplicating.
2. Read the [RUBRIC](RUBRIC.md) to see how proposals are evaluated.

Use the [Sprint Proposal template](.github/ISSUE_TEMPLATE/sprint-proposal.yml). Keep it under 500 words. Concrete beats aspirational.

## Working on an active sprint

Each accepted sprint gets its own repo under `ZcashApplicationsLab/<project>`. Contribution rules for that repo live in its own `CONTRIBUTING.md`, not here. The sprint lead sets them.

Expectations for all sprint repos:

- Apache License 2.0 unless the lead declares otherwise in the proposal
- Weekly update issue filed in **this** repo
- Final writeup filed in **this** repo before the sprint is marked shipped

## PR workflow for this repo

For changes to this repo (lab-level docs, templates, rubric):

1. Fork and branch off `main`.
2. Make your change.
3. Open a PR against `main` and fill in the PR template.
4. Two maintainer approvals required for merge.

### Commit style

[Conventional Commits](https://www.conventionalcommits.org/):

```
docs: clarify sprint handoff criteria
feat(template): add PoR vertical to proposal form
fix(rubric): typo in defensibility row
```

## Code of conduct

All spaces (issues, PRs, discussions, sprint repos, events) are governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Violations go to the maintainer group.

## License

By contributing, you agree that your contributions are licensed under Apache License 2.0 (matching this repo's [LICENSE](LICENSE)).
