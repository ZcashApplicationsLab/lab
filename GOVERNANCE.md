# Governance

## Mission

Ship working open-source applications that expand Zcash beyond private payments, and reduce idea-stage noise for ZCG and other funding bodies by providing a track record instead of a pitch deck.

## Structure

### Maintainers

The core group that owns triage, merges, and repo-level decisions. Maintainers are listed in `.github/CODEOWNERS` once the first cohort lands.

**Responsibilities**

- Triage sprint proposals against [RUBRIC.md](RUBRIC.md)
- Assign reviewers to active sprints
- Merge PRs to this repo (docs, templates, backlog)
- Represent the lab to ZCG, ZF, ECC, and external partners
- Moderate community spaces per [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

**Criteria**

- Has shipped at least one sprint as lead or reviewer
- Active in the lab for 3+ months
- Nominated by an existing maintainer and confirmed by simple majority of maintainers

### Sprint leads

Own a single sprint end-to-end. Get a dedicated repo under `ZcashApplicationsLab/<project>` with full write access for the duration of the sprint.

**Responsibilities**

- Ship the deliverable within the sprint window (2–4 weeks)
- Post weekly [Sprint Update](.github/ISSUE_TEMPLATE/sprint-update.yml) issues
- File the final [Sprint Writeup](.github/ISSUE_TEMPLATE/sprint-writeup.yml) when code is done
- Respond to reviewer feedback

### Reviewers

Domain experts assigned per sprint. Not necessarily maintainers.

**Responsibilities**

- Unblock the sprint lead on domain-specific questions
- Review the final writeup before it is accepted
- Flag concerns early

### Contributors

Anyone opening a PR, issue, or discussion. No formal role required.

## Decision-making

**Sprint acceptance** — simple majority of maintainers using [RUBRIC.md](RUBRIC.md). Ties go to the proposer (accept).

**This repo's docs, rubric, and governance** — PR requires approval from two maintainers. Conflicts escalate to the full maintainer group, decided by simple majority.

**New maintainers** — existing maintainer nominates, simple majority confirms.

**Removing maintainers** — inactive for 6+ months triggers a review. Removal by simple majority of the remaining maintainers. Inactive maintainers can return without repeating the nomination process if within 12 months.

**Changes to this document** — same as rubric changes: two-maintainer PR approval.

## Conflict of interest

Maintainers do not vote on sprint proposals where they are a proposer, co-proposer, or have a direct financial stake. Disclosures live in the proposal thread.

## Funding

The lab itself does not disburse funds. Sprints may be self-funded, unfunded, or seek external support (ZCG, ZF Grants, independent sponsors). If a sprint receives external funding, that is disclosed in the proposal and the final writeup.

## Org-level assets

- `ZcashApplicationsLab` GitHub org — admin rights held by the initial maintainer group
- Domain and social handles (when they exist) — same admin group
- No treasury, no token, no DAO as of now

## Changing course

If the lab's approach stops working — sprints not shipping, proposals not arriving, handoffs not landing — maintainers can vote to pause intake, restructure, or wind down. A wind-down decision requires unanimous maintainer agreement and a 30-day public notice period.

## Questions

Open a [Discussion](https://github.com/ZcashApplicationsLab/lab/discussions) tagged `governance`.
