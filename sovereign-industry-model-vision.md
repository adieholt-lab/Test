# Sovereign Industry Foundation Model

**A 1-trillion-parameter industry expert, post-trained in the UK on 25 years of multi-corporate engineering data.**

## The asset

Twenty-five years of design, engineering, supply chain, procurement, programme management and support data — petabyte scale, dozens of formats, held across multiple corporates. Post-trained on this corpus, a foundation model becomes an industry expert: it has read everything, forgets nothing, and reasons across domains that no single team or organisation can hold at once.

The end state is a **1T-parameter sovereign model** with the industry expert capability built in — not a bolt-on.

## Why Cosine

- **Sovereign by construction.** The only large model trained from scratch in the UK. No foreign jurisdiction over weights, data or telemetry. No export-control exposure.
- **Defence-grade.** Built for classified environments. Trains and deploys inside the customer security boundary — air-gapped or accredited cloud. Data never leaves sovereign infrastructure.
- **Provenance.** Every training sample lineage-tracked to source system, owner, classification and licence. The model can be audited on why it knows something, down to the document.
- **Sparklr.** Our training and post-training platform. Data curation, cross-format deduplication and efficient post-training reduce effective training compute by an order of magnitude versus naive fine-tuning — more experiments per pound, shorter path to a genuinely expert model.

## Delivery: demonstrate, then improve continuously

**Phase 1 — Demonstrator (8–12 weeks from data access).** Fine-tune of the Cosine base model on a scoped data slice. Proves value, de-risks data pipelines and governance.

**Phase 2 onward — Continuous post-training.** From the demonstrator, we train successively improved models on a rolling cadence as data is ingested, cleaned and released by contributors. Each iteration absorbs more corpus, more domains and more capability, converging on the 1T-parameter target. There is no single "big bang" training run — the model improves continuously, and each released iteration is deployable and useful in its own right.

| Iteration | Corpus absorbed | Model scale | Indicative training compute | Indicative duration |
|---|---|---|---|---|
| Demonstrator | ~50–100B tokens | 8–13B params | 8–16× H100-class GPUs | Days |
| Interim releases | ~1–2T tokens | 30–70B params | 128–256× H100-class GPUs | 4–8 weeks per cycle |
| Maturing releases | ~3–6T tokens | 70–180B params | 256–512× H100-class GPUs | Quarterly cadence |
| Target model | Full corpus, continuous refresh | 1T params (sparse-expert architecture) | 512–1024× H100-class GPUs | Continuous training regime |

Figures are indicative, pending Phase 0 data audit. Petabyte-scale raw corpora typically yield 2–10T usable tokens after extraction and deduplication. Sparklr's data-efficiency techniques consistently reduce these envelopes.

## Deployment compute

| Tier | Use case | Hardware per instance |
|---|---|---|
| Edge / programme site | Single-team assistant | 1–2× L40S/H100-class GPUs (quantised) |
| Enterprise | Concurrent users across a programme | 4–8× H100-class GPUs |
| Sovereign hub | Multi-corporate, high-assurance serving of the target model | Redundant GPU cluster inside accredited boundary; air-gap option |

All tiers run entirely within customer-controlled infrastructure. No external API calls.

## IP and data governance between contributing corporates

Contributors are large corporates with partial competitive overlap. Governance is engineered, not just contracted.

- **Federated ingestion.** Each contributor's data is ingested and tokenised within its own boundary or accredited enclave. Provenance metadata bound at token level.
- **Contractual firewalls.** No contributor can extract another's data from the model. Outputs filtered against source-attribution rules. Competitive-overlap domains ring-fenced or excluded by agreement.
- **Sovereign escrow.** Weights and corpus held under UK jurisdiction with pre-agreed exit and dissolution terms.
- **Asymmetric benefit, symmetric protection.** Each corporate receives a model tuned to its own estate. Shared learning accrues in generalised capability, never in disclosable specifics. Verified continuously via output attribution, canary tests and membership-inference auditing.
- **Joint governance board.** Customer board holds accept/reject authority over training runs, releases and use-case expansion.

## Commercial structure

1. **Phase 0** (fixed price): data audit, token-yield analysis, governance framework, calibrated compute plan.
2. **Continuous training service**: rolling post-training releases against an agreed cadence and capability roadmap, milestone-priced.
3. **Compute**: customer-owned, Cosine-managed, or hybrid. We specify, procure and operate as agreed.
4. **Support services**: multi-year agreement covering scheduled fine-tunes on new data, evaluation and red-teaming, platform updates, and named engineering support.

## Next step

A two-week Phase 0 workshop: we audit a sample of the corpus, calibrate the figures above against actual data, and return a costed, scheduled plan for the demonstrator.
