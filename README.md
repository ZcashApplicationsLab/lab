<p align="center">
  <img src="assets/logo-horizontal.png" alt="Zcash Applications Lab" width="720">
</p>

<h1 align="center">Zcash Applications Lab</h1>

<p align="center">
  <em>A continuous open-source hackathon for privacy-preserving applications beyond payments.</em>
</p>

<p align="center">
  <a href="https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-proposal.yml"><strong>Propose a sprint →</strong></a>
  ·
  <a href="BACKLOG.md">Backlog</a>
  ·
  <a href="RUBRIC.md">Evaluation rubric</a>
  ·
  <a href="GOVERNANCE.md">Governance</a>
</p>

---

## Why this exists

Zcash needs more working applications **beyond private payments**, and ZCG needs less idea noise.

ZAL is a triage and incubation layer: ideas in, open-source code out. We take promising application concepts, run them as time-boxed sprints, ship working prototypes with full writeups, and hand mature ones off to ZCG or grants programs with a track record instead of a pitch deck.

We are not a grants body, not a research lab, not a product studio. We are a **builder-first sandbox** for Zcash application space.

## What we ship

Every sprint produces:

- **Working code** — runnable prototype, Apache 2.0 licensed, in a dedicated repo under this org
- **Specification** — what it does, threat model, protocol sketch
- **Writeup** — design choices, tradeoffs, open questions
- **Demo** — CLI, web, or video walkthrough
- **Handoff note** — next steps, grant-readiness signal, links to relevant ZCG/ZF/ECC venues

See [SPRINT_WRITEUP_TEMPLATE](docs/SPRINT_WRITEUP_TEMPLATE.md) for the output format.

## The seven verticals

| #   | Vertical                                    | Problem                                                                                            |
| --- | ------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| 1   | Verifiable Credentials & Identity           | NFC passports, diplomas, KYC proofs on Zcash — selective disclosure without revealing the document |
| 2   | Private Credit & Underwriting               | Credit history, scoring, and lending with shielded counterparties                                  |
| 3   | Regulated Privacy & Selective Disclosure    | View keys, auditor keys, compliance-ready privacy for regulated flows                              |
| 4   | Institutional Settlement & Proof of Reserve | Treasury ops, PoR, private settlement rails                                                        |
| 5   | RWA Attestations                            | Tokenized real-world asset attestations with privacy defaults                                      |
| 6   | Private Voting & DAO Governance             | Shielded voting, delegation, quadratic funding                                                     |
| 7   | ZK Audits & Privacy-Preserving Analytics    | Audit trails, compliance reports, and analytics that preserve confidentiality                      |

Backlog items under each vertical live in [BACKLOG.md](BACKLOG.md).

## How it works

1. **Propose** — open a [Sprint Proposal](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-proposal.yml) issue. Scope is 2–4 weeks, one concrete deliverable.
2. **Triage** — maintainers evaluate against the [RUBRIC](RUBRIC.md): relevance, feasibility, team, defensibility, handoff path.
3. **Sprint** — if accepted, the team gets a repo under `ZcashApplicationsLab/<project>`, a project board, and a named reviewer. Weekly [Sprint Update](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-update.yml) posts.
4. **Ship** — code, spec, writeup, demo, handoff. [Sprint Writeup](https://github.com/ZcashApplicationsLab/lab/issues/new?template=sprint-writeup.yml) closes the loop.
5. **Hand off** — mature projects get pointed at ZCG, ZF Grants, Zcon, or independent funding with a track record already in public.

Two to three sprints run in parallel. New sprints are triaged monthly.

## Reference projects

- **[zk-credit-global-zcash](https://github.com/ZcashApplicationsLab/zk-credit-global-zcash)** — ZAL-00, the anchor project. ZK ID (NFC passport proofs) + ZK Credit (private credit history on Zcash).

## Get involved

- **Builders** — pick a backlog item or propose your own sprint
- **Reviewers** — we need domain reviewers in cryptography, compliance, credit, identity, and governance
- **Mentors** — time-boxed mentoring slots for active sprints
- **Observers** — watch the repo, comment on writeups, no commitment needed

Read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before opening your first issue or PR.

## License

All work in this org is **Apache License 2.0** unless a sprint explicitly declares otherwise in its repo.

## Related

- [Zcash Community Grants (ZCG)](https://zcashcommunitygrants.org/)
- [Zcash Foundation](https://zfnd.org/)
- [Electric Coin Co.](https://electriccoin.co/)
