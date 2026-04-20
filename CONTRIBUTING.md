# Contributing to Zcash Applications Lab

> **Heads up:** ZAL is an early, unfunded community experiment. It is not affiliated with ZF, ZCG, or ECC, and nothing here is a commitment to pay anyone for their time. Contributions are volunteer and open-source. If that is fine by you, read on.

Thanks for your interest. The lab runs as a continuous, open-source hackathon — there are a few ways to plug in.

## Ways to contribute

| I want to…                                     | Do this                                                                                                              |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Propose a new sprint                           | Open a [Sprint Proposal](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-proposal.yml)        |
| Join an active sprint                          | Comment on the sprint's issue; leads will respond                                                                    |
| Review sprints                                 | Open a [Discussion](https://github.com/ZcashApplicationsLab/lab/discussions) describing your domain and availability |
| Mentor                                         | Same as above                                                                                                        |
| Improve this repo's docs, rubric, or templates | Open a PR against `main`                                                                                             |
| Flag a backlog idea                            | Open an issue tagged `backlog` or PR against [BACKLOG.md](BACKLOG.md)                                                |
| Report a security issue                        | Email the maintainers listed in `SECURITY.md` (coming soon) — do not open a public issue                             |

## Sprint proposals

Before opening a proposal:

1. Read the [RUBRIC](RUBRIC.md) and score yourself honestly
2. Check [BACKLOG.md](BACKLOG.md) — if your idea is already there, say so in the proposal
3. Skim recent proposals (open and closed) so you are not duplicating

Use the [Sprint Proposal template](.github/ISSUE_TEMPLATE/sprint-proposal.yml). Keep it under 500 words. We prefer concrete over aspirational.

## Working on an active sprint

Each accepted sprint gets its own repo under `ZcashApplicationsLab/<project>`. Contribution rules for that repo live in its own `CONTRIBUTING.md`, not here. The sprint lead sets them.

Expectations for all sprint repos:

- Apache License 2.0 unless the lead declares otherwise in the proposal
- Weekly update issue filed in **this** repo
- Final writeup filed in **this** repo before the sprint is marked shipped

## PR workflow for this repo

For changes to this repo (lab-level docs, templates, rubric, backlog):

1. Fork and branch off `main`
2. Make your change
3. Open a PR against `main` — fill in the PR template
4. Two maintainer approvals required for merge

### Commit style

[Conventional Commits](https://www.conventionalcommits.org/):

```
docs: clarify sprint handoff criteria
feat(template): add PoR vertical to proposal form
fix(rubric): typo in defensibility row
```

## Code of conduct

All spaces — issues, PRs, discussions, sprint repos, events — are governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Violations go to the maintainer group.

## License

By contributing, you agree that your contributions are licensed under Apache License 2.0 (matching this repo's [LICENSE](LICENSE)).
