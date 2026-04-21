# Governance

> **Note on status.** ZAL is a volunteer-run community experiment. It is **not affiliated with or endorsed by** ZF, ZCG, Shielded Labs, or ZOLD. There is no budget, no treasury, no legal entity, and no formal membership. This document describes an intended working model for a small volunteer group, not an existing organization with authority. It will change as the experiment runs or be deleted if the experiment ends.

## Mission

Help surface and ship working open-source applications that expand what people can build on Zcash beyond private payments. The lab produces prototypes with writeups so that builders, and anyone evaluating their work, can look at code instead of only pitch decks.

## Structure

### Maintainers

The core group that owns triage, merges, and repo-level decisions. Maintainers are listed in `.github/CODEOWNERS` once the first cohort lands.

**Responsibilities**

- Triage sprint proposals against [RUBRIC.md](RUBRIC.md)
- Assign reviewers to active sprints
- Merge PRs to this repo (docs, templates, rubric)
- Act as the public point of contact for the lab (as a community group, not as a representative of any external organization)
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

**Sprint acceptance.** Simple majority of maintainers using [RUBRIC.md](RUBRIC.md). Ties go to the proposer (accept).

**This repo's docs, rubric, and governance.** PR requires approval from two maintainers. Conflicts escalate to the full maintainer group, decided by simple majority.

**New maintainers.** Existing maintainer nominates, simple majority confirms.

**Removing maintainers.** Inactive for 6+ months triggers a review. Removal by simple majority of the remaining maintainers. Inactive maintainers can return without repeating the nomination process if within 12 months.

**Changes to this document.** Same as rubric changes: two-maintainer PR approval.

## Conflict of interest

Maintainers do not vote on sprint proposals where they are a proposer, co-proposer, or have a direct financial stake. Disclosures live in the proposal thread.

## Funding

The lab has no treasury, no budget, no fundraising, and does not disburse funds. Nothing in this repo constitutes a funding commitment by anyone.

Individual sprints are run by their authors at their own cost. If a sprint author secures funding elsewhere (their own savings, an employer, a sponsor, a grant), that is entirely between them and the funder. Any such arrangement must be disclosed in the sprint proposal and writeup for transparency, but it is not brokered, filtered, or endorsed by the lab.

## Org-level assets

- `ZcashApplicationsLab` GitHub org, admin rights held by the initial maintainer group
- Domain and social handles (when they exist), same admin group
- No treasury, no token, no DAO as of now

## Changing course

If the lab's approach stops working (sprints not shipping, proposals not arriving, no useful feedback), maintainers can vote to pause intake, restructure, or wind down. A wind-down decision requires unanimous maintainer agreement and a 30-day public notice period. Given this is an experiment, winding down is a legitimate outcome, not a failure.

## Questions

Open a [Discussion](https://github.com/ZcashApplicationsLab/lab/discussions) tagged `governance`.
