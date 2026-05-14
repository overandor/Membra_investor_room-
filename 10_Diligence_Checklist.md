# MEMBRA Diligence Checklist

## Product Evidence

- [ ] All runnable repos deploy locally or on Hugging Face
- [ ] Demo flow uses `Membra_demo_data/data/demo_bundle.json`
- [ ] QR/proof gateway records scan events
- [ ] ProofBook records proof hashes and review status
- [ ] Admin console records decisions and audit events
- [ ] Wallet records eligibility without custody claims
- [ ] KPI module exports campaign and proof reports

## Technical Evidence

- [ ] `Membra_api` exposes canonical user, asset, listing, proof, relay, wallet, and payout eligibility endpoints
- [ ] Shared object IDs are consistent across modules
- [ ] Requirements files exist for all demo runtimes
- [ ] Secrets are documented and not committed
- [ ] Stripe webhook endpoints verify signatures where live payments are used
- [ ] No private keys or seed phrases are requested or stored

## Commercial Evidence

- [ ] First customer wedge selected: physical media campaign, wearable media kit, relay, or KPI reporting
- [ ] Pricing model documented
- [ ] Demo advertiser and owner workflow documented
- [ ] Pilot target list prepared
- [ ] Claims registry maps every market claim to evidence

## Compliance Evidence

- [ ] Consent policy exists
- [ ] Proof retention policy exists
- [ ] Payout boundary policy exists
- [ ] Devnet/mainnet boundary exists for contract experiments
- [ ] Fraud/review workflow exists
- [ ] No guaranteed income claims
- [ ] No guaranteed advertiser-performance claims

## Buyer / Investor Questions

1. What exactly is live versus demo-only?
2. Which repo is the source of truth for shared data?
3. What data is collected from owners?
4. How is consent recorded?
5. How is proof reviewed?
6. What triggers payout eligibility?
7. What external rail settles money?
8. What are the first 10 pilot customers?
9. What is the narrowest wedge that can generate revenue?
10. What becomes defensible over time?

## Immediate Upgrade Path

1. Deploy `Membra_api`, `Membra_admin-`, `Membra_proofbook`, `Membra_wallet`, `Membra_ads`, `Membra_kpi`.
2. Load the demo bundle.
3. Produce screenshots and a two-minute demo script.
4. Run one live pilot with a local advertiser and three placements.
5. Convert proof and scan events into a KPI report.
6. Document payout eligibility without claiming automated settlement.
