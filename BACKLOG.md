# Sprint Backlog

Seed ideas across the seven verticals. Pick one, propose a sprint, or add your own via PR.

Items marked `claimed` have an active sprint. Items marked `shipped` link to the writeup. Everything else is open.

---

## 1. Verifiable Credentials & Identity

- **ZAL-00 · ZK ID (NFC passport proofs on Zcash).** `claimed`. Reference project being developed independently by the initial maintainer group. Link to come once the repo is published under this org.
- **Verifiable diploma attestations.** Port eIDAS-compatible credentials into a Zcash-backed disclosure flow.
- **Age / residency proofs with shielded memos.** Selective disclosure without identifying the holder.
- **Reusable KYC receipts.** Prove a KYC check passed at institution X without re-running it at Y.

## 2. Private Credit & Underwriting

- **Shielded credit score oracle.** Submit encrypted history, receive a score range proof.
- **Private loan book.** Lender pool with shielded counterparties, public aggregate stats.
- **Collateral attestation.** Prove solvency for a loan without revealing the collateral mix.

## 3. Regulated Privacy & Selective Disclosure

- **Auditor-key toolkit.** Reference implementation for compliant selective disclosure.
- **Travel Rule companion.** Shielded transfers with off-chain counterparty exchange.
- **Tax receipt generator.** Export year-end tax data for shielded activity with user-held keys.

## 4. Institutional Settlement & Proof of Reserve

- **Private treasury PoR.** Prove total reserves ≥ total liabilities without disclosing holdings.
- **OTC settlement rail.** Two-party shielded settlement with dispute proofs.
- **Inter-institution netting.** Batched settlement with selective counterparty disclosure.

## 5. RWA Attestations

- **Shielded asset registry.** Tokenized RWA with privacy-default metadata.
- **Supply chain attestation.** Prove provenance of a good without revealing the full chain.
- **Carbon credit retirement.** Private retirement with public audit trail.

## 6. Private Voting & DAO Governance

- **Shielded voting primitive.** One-person-one-vote with membership proof.
- **Quadratic funding round tooling.** Private contributions, public round outcomes.
- **Delegation with revocation.** Shielded delegation and revocation trails.

## 7. ZK Audits & Privacy-Preserving Analytics

- **Compliance report generator.** Aggregate shielded activity into regulator-ready reports.
- **Privacy-preserving analytics SDK.** Differential-privacy building blocks for Zcash apps.
- **Proof-of-compliance for exchanges.** Prove a set of rules held over a period without disclosing trades.

---

## Adding an item

1. Fork this repo.
2. Add a bullet to the relevant vertical.
3. Open a PR with title `backlog: add <short name>`.

Keep items to one line. Detailed scoping belongs in a sprint proposal, not the backlog.
