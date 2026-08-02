# Terray Therapeutics

Terray Therapeutics is an AI-native, chemistry-first biotechnology company building an integrated
full-stack platform for small molecule drug discovery. Its EMMI platform (Experimentation Meets
Machine Intelligence) pairs a proprietary ultra-miniaturized microarray assay system and a fully
automated lab with a family of machine learning models — COATI (a chemistry foundation model trained
on roughly a billion molecules), reinforcement-learning generative models for synthesizable de novo
design, TerraBind for potency prediction, and EMMI Select for uncertainty-aware molecule selection.
Terray reports a target-molecule interaction dataset of more than 17 billion measurements, growing
by about a billion per quarter, and runs multi-target discovery collaborations with Bristol Myers
Squibb, Gilead, Calico and Odyssey Therapeutics, with investment from NVIDIA.

**No public API.** Full contract discovery on 2026-08-02 found no OpenAPI, AsyncAPI, GraphQL, MCP
server, or A2A agent card on any Terray host, and no developer portal or API documentation. Terray's
public technical surface is open-source research code on GitHub. See `review.yml` for the probe log.

- Website — https://www.terraytx.ai/
- EMMI Platform — https://www.terraytx.ai/emmi-platform
- News & Research — https://www.terraytx.ai/news-and-research
- GitHub — https://github.com/terraytherapeutics

## Artifacts

| Path | What it is |
|---|---|
| `apis.yml` | APIs.json catalog entry (identity + link properties) |
| `review.yml` | Contract-discovery probe log and applicability notes |
| `packages/` | First-party open-source libraries (COATI, COATI-LDM, TerraMax) + registry probe results |
| `llms/` | Generated `llms.txt` for the company |
| `security/` | Probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture |
| `well-known/` | Recorded `/.well-known/` probe results (all 404) |
